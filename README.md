# FiveM Default Clothing Images

A snapshot of the image files supplied with **v0id Studio**, published in the `clothing/` directory. The files are copied from the source image folder with their original names and contents.

## Contents

- Freemode clothing and accessory renders for male and female characters
- Component (`c`) and prop (`p`) images
- The source folder's additional image and placeholder files, preserved as supplied

The collection contains both PNG and WebP files. Image dimensions and transparency may vary by source file; consumers should inspect the image rather than assume a fixed canvas size.

## File names

Clothing files use this pattern:

```text
<gender>_<type><id>_<drawable>_<texture>.png
```

- `gender`: `male` or `female`
- `type`: `c` for a component or `p` for a prop
- `id`: component or prop slot number
- `drawable`: drawable variation
- `texture`: texture variation

Examples:

- `male_c11_522_0.png` — male component slot 11, drawable 522, texture 0
- `female_p0_14_0.png` — female prop slot 0, drawable 14, texture 0

## Component slots

| ID | Component |
| ---: | --- |
| 1 | Mask |
| 3 | Arms / hands |
| 4 | Legs |
| 5 | Bags |
| 6 | Shoes |
| 7 | Accessories |
| 8 | Undershirts |
| 9 | Body armor |
| 10 | Decals |
| 11 | Tops |

Common prop slots include `p0` hats, `p1` glasses, `p2` ears, `p6` watches, and `p7` bracelets.

## Source and updates

The source for this snapshot is `v0id-studio/data/images`. When the source image set changes, the `clothing/` directory should be replaced with that complete source directory so filenames and file contents stay in sync.

## Usage and rights

These images depict Grand Theft Auto V assets owned by Rockstar Games. Their presence in this repository does not grant rights to the underlying game assets. Check the applicable rights and terms before redistribution or commercial use.
