# Print_r is PHP Snippets - VScode extension

[![VScode](https://img.shields.io/badge/Extension-VScode-blueviolet.svg)](https://marketplace.visualstudio.com/items?itemName=KrishnaKanhaiya.printr)
![Snippets](https://img.shields.io/badge/Type-Snippets-yellow.svg)
![PHP8](https://img.shields.io/badge/PHP-8-blue.svg)
![PHP5](https://img.shields.io/badge/PHP-%5E5.4-blue.svg)
[![MIT](https://img.shields.io/badge/License-MIT-%2300C853.svg)](https://github.com/krishnaarga/print_r/blob/main/LICENSE)

## Snippets Demo
![demo](https://raw.githubusercontent.com/krishnaarga/print_r/main/images/demo.gif)

## Features

### PHP Tags
| Snippet | Output |
| ---   | --- |
| !er   | ![er](https://raw.githubusercontent.com/krishnaarga/print_r/main/images/er.png) |
| !ppe  | ![ppe](https://raw.githubusercontent.com/krishnaarga/print_r/main/images/ppe.png) |
| !pp   | ![pp](https://raw.githubusercontent.com/krishnaarga/print_r/main/images/pp.png) |
| !ter  | `$veriable = condition ? if_true : if_false;` |

### Function
| Snippet | Output |
| ---   | --- |
| !fn   | `function functionName(){ ... }` |
| !fna  | `function functionName(Type $args){ ... }` |

### Array
| Snippet | Output |
| ---   | --- |
| !ar   | `[value, value];` |
| !ark  | `['key' => value, 'key' => value];` |

### Class & Interface
| Snippet | Output |
| ---   | --- |
| !cc   | Doc Comment for Class |
| !cl   | `class ClassName{ ... }` |
| !cle  | `class ClassName extends ParentClass{ ... }` |
| !cli  | `class ClassName implements Interfaces{ ... }` |
| !clei | `class ClassName extends ParentClass implements Interfaces{ ... }` |

## Known Issues
If suggestions menu does not open, press `Ctrl+space` to open it manually.

Sometimes IntelliSense freezes loading or simply doesn't select the called snippet. Backspace and try again, it should work.

## Release Notes
All notable changes to this project will be documented in [CHANGELOG.md](https://github.com/krishnaarga/print_r/blob/main/CHANGELOG.md).

## License
[MIT](https://github.com/krishnaarga/print_r/blob/main/LICENSE) License