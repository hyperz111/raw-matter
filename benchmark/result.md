# Benchmarks

> This benchmark is using different content (salted) in every iterations.

## complex

```text
front-matter × 4,613 ops/sec ±0.18% (4,569 runs sampled)
gray-matter × 3,691 ops/sec ±0.36% (3,490 runs sampled)
gray-matter+yaml_disabled × 10,977 ops/sec ±0.25% (10,286 runs sampled)
raw-matter × 226,460 ops/sec ±0.04% (203,134 runs sampled)
raw-matter+yaml × 6,586 ops/sec ±0.12% (6,527 runs sampled)
```

## empty

```text
front-matter × 3,046,804 ops/sec ±0.03% (2,206,715 runs sampled)
gray-matter × 142,126 ops/sec ±0.05% (119,716 runs sampled)
gray-matter+yaml_disabled × 166,463 ops/sec ±0.05% (143,967 runs sampled)
raw-matter × 8,380,917 ops/sec ±0.04% (5,515,140 runs sampled)
raw-matter+yaml × 8,414,659 ops/sec ±0.04% (6,238,856 runs sampled)
```

## matter

```text
front-matter × 108,695 ops/sec ±0.04% (105,400 runs sampled)
gray-matter × 44,360 ops/sec ±0.12% (39,315 runs sampled)
gray-matter+yaml_disabled × 80,002 ops/sec ±0.09% (69,824 runs sampled)
raw-matter × 1,397,372 ops/sec ±0.03% (1,150,642 runs sampled)
raw-matter+yaml × 143,249 ops/sec ±0.03% (133,102 runs sampled)
```

## no-content

```text
front-matter × 111,654 ops/sec ±0.04% (107,150 runs sampled)
gray-matter × 45,146 ops/sec ±0.10% (41,036 runs sampled)
gray-matter+yaml_disabled × 80,703 ops/sec ±0.08% (71,632 runs sampled)
raw-matter × 1,352,684 ops/sec ±0.03% (1,297,902 runs sampled)
raw-matter+yaml × 142,995 ops/sec ±0.04% (120,226 runs sampled)
```

## no-matter

```text
front-matter × 1,297,447 ops/sec ±0.03% (1,246,917 runs sampled)
gray-matter × 103,912 ops/sec ±0.07% (86,306 runs sampled)
gray-matter+yaml_disabled × 103,220 ops/sec ±0.07% (92,319 runs sampled)
raw-matter × 2,444,189 ops/sec ±0.03% (2,146,581 runs sampled)
raw-matter+yaml × 2,610,780 ops/sec ±0.04% (1,585,465 runs sampled)
```
