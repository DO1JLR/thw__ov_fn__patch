 THW Patch
===========
## OV Friedrichshafen

In diesem git Repository findet ihr den Patch des THW - Ortsverband  Friedrichshafen.
In der History dieses Repos gibt es einen Einblick in unterschiedliche varrianten. Der finalen Patch als Vektrorgrafik is dieser:

![THW Path OV FN](thw_patch_ov_fn.svg)

# Lizenz:
[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/de/)
```
Urheber: L3D <l3d@c3woc.de>
https://creativecommons.org/licenses/by/3.0/de/
```

## Tipps for exporting
*Mit folgenden parametern lässt sich ein PDF mit 300 DPI aus dem SVG exportieren*
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

## Git Mirrors
Dieses git Repo findet man an folgenden Orten:
+ Github: [github.com/DO1JLR/thw__ov_fn__patch](https://github.com/DO1JLR/thw__ov_fn__patch.git)
+ Gitea: [git.l3d.ch/thw/patch_ov_fn](https://git.l3d.ch/thw/patch_ov_fn.git)
