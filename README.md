# thw__ov_fn__patch
Designentwurf eines Patch für den THW OV Friedrichshafen.

![THW Path OV FN](thw_patch_ov_fn.svg)

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
