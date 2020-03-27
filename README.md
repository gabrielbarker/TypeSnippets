# TypeSnippets

A selection of useful typescript snippets, focusing on commonly used, verbose snippets.

## Snippets

#### Exports

- `xd` - `export default`

* `xdc` - creates an empty class to be exported by default - `export default class ClassName {...}`
* `xdi` - creates an empty interface to be exported by default - `export default interface InterfaceName {...}`
* `xe` - creates an empty enum to be exported - `export enum EnumName {...}`

#### Alt-Exports

- `xdc-alt` - creates an empty class to be exported by default after declaration - `class ClassName {...} export ClassName;`
- `xdi-alt` - creates an empty interface to be exported by default after declaration - `interface InterfaceName {...} export InterfaceName;`
- `xe-alt` - creates an empty enum to be exported after declaration - `enum EnumName {...} export EnumName;`

#### Imports

- `id` - creates an import statement for a package and it's default export - `import PackageName from 'PackageName';`

#### Arrow Functions

- `arrow` - creates an arrow function - `(params) => {...}`
- `arrow-inline` - creates an inline arrow function - `(params) => ...`

#### Generic Functions

- `generic` - creates a declaration for a generic function - `function FunctionName<TypeParameter>(params) {...}`
