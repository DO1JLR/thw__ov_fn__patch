# thw__ov_fn__patch
Designentwurf eines Patch für den THW OV Friedrichshafen.

![Path #1A](thw_patch_1a.svg)
![Path #1B](thw_patch_1b.svg)
![Path #1C](thw_patch_1c.svg)
![Path #2A](thw_patch_2a.svg)
![Path #2B](thw_patch_2b.svg)
![Path #2C](thw_patch_2c.svg)
![Path #3A](thw_patch_3a.svg)
![Path #3B](thw_patch_3b.svg)
![Path #3C](thw_patch_3c.svg)
![Path #4A](thw_patch_4a.svg)
![Path #4B](thw_patch_4b.svg)
![Path #4C](thw_patch_4c.svg)

# Lizenz:
[CC-BY-3.0](https://creativecommons.org/licenses/by/3.0/de/)
```
Urheber: L3D <l3d@c3woc.de>
https://creativecommons.org/licenses/by/3.0/de/
```

## Tipps for exporting
```bash
for i in *.svg
do
    echo "Export: $i"
    inkscape \
    --actions="export-filename:$i.pdf; export-do;"\
    --export-dpi 300 \
    $i
done

# pdftk PDF1.pdf PDF2.pdf cat output PDF3.pdf
```
