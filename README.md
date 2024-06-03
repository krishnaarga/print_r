# Print_r is a PHP Snippets - VScode extension

[![VScode](https://img.shields.io/badge/Extension-VScode-blueviolet.svg)](https://marketplace.visualstudio.com/items?itemName=KrishnaKanhaiya.printr)
![Snippets](https://img.shields.io/badge/Type-Snippets-yellow.svg)
![PHP8](https://img.shields.io/badge/PHP-8-blue.svg)
![PHP5](https://img.shields.io/badge/PHP-%5E5.4-blue.svg)
[![MIT](https://img.shields.io/badge/License-MIT-%2300C853.svg)](https://github.com/krishnaarga/print_r/blob/main/LICENSE)

## Features

### PHP Tags
| Shortcut | Output |
| ---      | ---    |
| er       | ![er](https://raw.githubusercontent.com/krishnaarga/print_r/main/images/er.png) |
| ppe      | ![ppe](https://raw.githubusercontent.com/krishnaarga/print_r/main/images/ppe.png) |
| pp       | ![pp](https://raw.githubusercontent.com/krishnaarga/print_r/main/images/pp.png) |
| ter      | `$veriable = condition ? if_true : if_false;` |

### Function
| Shortcut | Output |
| ---      | ---    |
| fn       | `function functionName(){ ... }` |
| fna      | `function functionName(Type $args){ ... }` |

### Array
| Shortcut | Output |
| ---      | ---    |
| ar       | `['value1', 'value2', 'value3', 'value4', 'value5'];` |
| ark      | `['key1' => 'value1', 'key2' => 'value2', 'key3' => 'value3'];` |

### Class & Interface
| Shortcut | Output |
| ---      | ---    |
| cc       | Doc Comment for Class |
| cl       | `class ClassName{ ... }` |
| cle      | `class ClassName extends ParentClass{ ... }` |
| cli      | `class ClassName implements Interfaces{ ... }` |
| clei     | `class ClassName extends ParentClass implements Interfaces{ ... }` |
| pf       | `public function functionName(){ ... }` |
| psf      | `public static function functionName(){ ... }` |

### Work with CSV
| Shortcut   | Output    |
| ---        | ---       |
| csvread    | Read Existing CSV file or from form. |

## Known Issues
If suggestions menu does not open, press `Ctrl+space` to open it manually.

Sometimes IntelliSense freezes loading or simply doesn't select the called snippet. Backspace and try again, it should work.

## Release Notes
All notable changes to this project will be documented in [CHANGELOG.md](https://github.com/krishnaarga/print_r/blob/main/CHANGELOG.md).

## License
[MIT](https://github.com/krishnaarga/print_r/blob/main/LICENSE) License
