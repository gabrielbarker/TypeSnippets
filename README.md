# TypeSnippets [![Version](https://vsmarketplacebadge.apphb.com/version/gabrielbarker.typesnippets.svg)](https://marketplace.visualstudio.com/items?itemName=gabrielbarker.typesnippets)

A selection of useful TypeScript snippets, focusing on commonly used, verbose snippets.

## Snippets

### Exports

| Snippet   | Description                                                            | Example                                               |
| --------- | ---------------------------------------------------------------------- | ----------------------------------------------------- |
| `xd`      | creates a default export statement                                     | `export default`                                      |
| `xdc`     | creates an empty class to be exported by default                       | `export default class ClassName {...}`                |
| `xdi`     | creates an empty interface to be exported by default                   | `export default interface InterfaceName {...}`        |
| `xe`      | creates an empty enum to be exported                                   | `export enum EnumName {...}`                          |
| `xdc-alt` | creates an empty class to be exported by default after declaration     | `class ClassName {...} export ClassName;`             |
| `xdi-alt` | creates an empty interface to be exported by default after declaration | `interface InterfaceName {...} export InterfaceName;` |
| `xe-alt`  | creates an empty enum to be exported after declaration                 | `enum EnumName {...} export EnumName;`                |

### Imports

| Snippet | Description                                                       | Example                                   |
| ------- | ----------------------------------------------------------------- | ----------------------------------------- |
| `imp`   | creates an import statement for a package                         | `import { elements } from 'PackageName';` |
| `impd`  | creates an import statement for a package and it's default export | `import PackageName from 'PackageName';`  |

### Functions

| Snippet        | Description                                  | Example                                              |
| -------------- | -------------------------------------------- | ---------------------------------------------------- |
| `arrow`        | creates an arrow function                    | `(params) => {...}`                                  |
| `arrow-inline` | creates an inline arrow function             | `(params) => ...`                                    |
| `generic`      | creates a declaration for a generic function | `function FunctionName<TypeParameter>(params) {...}` |
