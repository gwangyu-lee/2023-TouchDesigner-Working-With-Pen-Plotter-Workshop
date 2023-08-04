![poster square](https://github.com/gwangyu-lee/2023-TouchDesigner-Working-With-Pen-Plotter-Workshop/assets/79373845/20527fc5-45db-4146-9ab9-d7ad12628f7f)

# 2023-TouchDesigner-Working-With-Pen-Plotter-Workshop
The project files of TouchDesigner Working With Pen Plotter Workshop

## Inkscape
[Inkscape 1.3](https://inkscape.org/release/inkscape-1.3/)

## Axidraw
[Axidraw](https://wiki.evilmadscientist.com/Axidraw_Software_Installation)

## SVG Fonts
[SVG Fonts](https://gitlab.com/oskay/svg-fonts)

## Svgwrite

### Windows
[Python 3.10](https://www.python.org/downloads/release/python-3100/)  

Open cmd and type:

`py -m pip install --target="C:/Users/USERNAME/AppData/Local/Programs/Python/Python310/Lib/site-packages" svgwrite`
Please change USERNAME.

### MacOS
[Python 3.10](https://www.python.org/downloads/release/python-3100/)    

Open terminal and type:

`curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`  

`python3 get-pip.py`  

`python3 -m pip install --target=/Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10/site-packages svgwrite`

### TouchDesigner

Add Python 64-bit module path.

![python module path](https://github.com/gwangyu-lee/2023-TouchDesigner-Working-With-Pen-Plotter-Workshop/assets/79373845/3d82d935-62e4-4667-8ce3-1c4bc36c8723)

#### Windows
`C:/Users/USERNAME/AppData/Local/Programs/Python/Python310/Lib/site-packages`

#### MacOS
`/Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10/site-packages`

## Reference
[SOP to SVG](https://github.com/raganmd/touchdesigner-sop-to-svg)
