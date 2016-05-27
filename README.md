LV-string2hex-view
==

Render LabVIEW string into hex display. 

[中文版](README_chi.md)

## How does it work?

Pull any string you want to display into the `string2hex.vi` subVI. The below figure is the result.

![](example_screen.png)

Features: 

- Line numbers in hex code (e.g. `#000F`)
- Raw data display in hex code (e.g. ...`EB90 0001`...)
- The corresponded ASCII string

## How to use?

There is only a core file `string2hex.vi`:

- **Input terminal**: LabVIEW string to be display as hex view, or byte array (need type cast)
- **Output terminal**: hex-viewed LabVIEW string
- **Optional terminal**: the seperated string (default `"=>"`). Wired any string you want. 
