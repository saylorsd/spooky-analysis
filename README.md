# Spooky Analysis :ghost:
A serious geographic analysis of the spookiness of Allegheny County using open data.

## Spook Generators
The following things have been determined to generate ghosts and all-around spookiness.
1. Cemeteries [[data](https://data.wprdc.org/dataset/allegheny-county-cemetery-outlines)]
2. Dead Animals(roadkill and the like) [[data](https://data.wprdc.org/dataset/311-data)]
3. Dead Trees [[data](https://data.wprdc.org/dataset/311-data)]

## Spookiness Levels
Spookiness can be measured on a 0 - 1 scale with `0` meaning absolutely no spookiness and `1` meaning the spookiest darn thing you've ever experienced.

## Spookiness Functions
Spook generators radiate spookiness at various rates.  
`b` - base spookiness level. `{b ∈ R | 0 ≤ b ≤ 1}`  
`d` - distance from edge of generator  

| Generator | GeoType | Base Spookiness |S(b, d)          |
|-----------|---------|-----------------|-----------------|
| cemetery  | polygon | `b = .6`        | `S(d) => `      |
