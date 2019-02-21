# macOS

## brew
`brew info <formula>`
`brew switch <formula> <version>`

# c++

# std/stl
`std::boolalpha`

## OpenCV
type2str

# python

## conda
`conda info --envs`
`conda env remove -n caffe2`

# Ubuntu

## Switch left_ctrl and left_alt:
```
apt-get install dconf-tools
dconf write "/org/gnome/desktop/input-sources/xkb-options" "['ctrl:swap_lalt_lctl','ctrl:swap_ralt_rctl']"
```

## Application.desktop directory
`/usr/share/applications/`

## Set dynamic libraries/shared libraries path
`export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:<additional_path>`

## Decompress tar.gz
`tar -xvzf <file_name.tar.gz>`