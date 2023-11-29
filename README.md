# VSCode Dark+ Theme For Qt Creator

I tried my best to port the default Dark+ theme from VS Code into Qt Creator, as I find it quite nice, but I cannot replicate it 1:1 due to the limitations of Qt's theme engine, for example Qt doesn't differentiate between keywords like `const`, `namespace`, and `enum` which would be blue in VSCode, and keywords like `if`, `operator`, `return`, which would be purple in VSCode; it's either one or the other in Qt, so I've included both options to choose from, purple keywords (what I prefer), but also blue keywords. I hope you enjoy!

## Installation
Just move one or both of the `.xml` files of your choice into your Qt Creator styles folder. The location of this folder depends on your operating system, but there are typically two: one that's part of the Qt installation folder, which contains Qt's default themes, and themes placed there cannot be modified, and then there's the recommended folder which is usually located somewhere in your user directory.

_From: https://doc.qt.io/qtcreator/creator-quick-tour.html#location-of-settings-files_

### Windows Location

**In Qt5**

- Full Path: `C:\Users\%USERNAME%\AppData\Roaming\QtProject\qtcreator\styles`

  ​				  `C:\Users\%USERNAME%\AppData\Roaming\QtProject\qtcreator\themes`

- Shortcut: `%appdata%\QtProject\qtcreator\styles`

  ​                 `%appdata%\QtProject\qtcreator\themes`

**In Qt6**

- Full Path:`G:\QT6\Tools\QtCreator\share\qtcreator\styles`
  	 			 `G:\QT6\Tools\QtCreator\share\qtcreator\themes`

### Linux Location
- `~/.local/share/data/QtProject/qtcreator`

### OSX Location
- `~/Library/Application Support/QtProject/Qt`

## Previews
Font used in the screenshots:  [MonoLisa](https://www.monolisa.dev/)

### Purple Keywords Preview 
![](screenshots/purple1.png)
![](screenshots/purple2.png)
![](screenshots/purple3.png)

### Blue Keywords Preview
![](screenshots/blue1.png)
![](screenshots/blue2.png)
![](screenshots/blue3.png)

### Comments
![image-20221120110327601](screenshots/image-20221120110327601.png)
