# Schematics React

Schematics generators for React

## Installation
- npm:
  ```bash
  npm install -g @angular-devkit/schematics-cli
  npm link '../relative_path'
  ```

## Usage

```bash
schematics schematics-react:<generator name> <arguments>
```

## Available generators

### Component
Creates a React component.

Example:
```bash
schematics schematics-react:component /src/components/myComponent
```

with alias:
```bash
schematics schematics-react:c /src/components/myComponent
```

#### Parameters
| Type | Name | Description | Default |
|------|:----:|------------:|--------:|
| *required* {string} | name | The name of the component. | none |
| {string} | path | The path to create the component | none |
| {string} | styleext | The file extension to be used for style files | 'css' |
| {boolean} | noSpec | Specifies if a spec file is generated | false |
| {boolean} | subfolder | Flag to indicate if a dir is created | false |
| {boolean} | propTypes | Specifies if a propTypes used | false |
| {boolean} | stateful | Specifies if a state used | false |
| {boolean} | ts | Specifies whether to use TypeScript | false |

### Functional component
Creates a React component.

Example:
```bash
schematics schematics-react:functional-component /src/components/myComponent
```

with alias:
```bash
schematics schematics-react:fc /src/components/myComponent
```

#### Parameters
| Type | Name | Description | Default |
|------|:----:|------------:|--------:|
| *required* {string} | name | The name of the component. | none |
| {string} | path | The path to create the component | none |
| {string} | styleext | The file extension to be used for style files | 'css' |
| {boolean} | noSpec | Specifies if a spec file is generated | false |
| {boolean} | subfolder | Flag to indicate if a dir is created | false |
| {boolean} | propTypes | Specifies if a propTypes used | false |
| {boolean} | ts | Specifies whether to use TypeScript | false |

### React page
Creates a React page with predefined store.

Example:
```bash
schematics schematics-react:reactPage /src/components/MyPage
```

with alias:
```bash
schematics schematics-react:rp /src/components/MyPage
```

#### Parameters
| Type | Name | Description | Default |
|------|:----:|------------:|--------:|
| *required* {string} | name | The name of the component. | none |
| {string} | path | The path to create the component | none |
| {string} | styleext | The file extension to be used for style files | 'css' |
| {boolean} | noSpec | Specifies if a spec file is generated | false |
| {boolean} | subfolder | Flag to indicate if a dir is created | false |
| {boolean} | propTypes | Specifies if a propTypes used | false |
| {boolean} | ts | Specifies whether to use TypeScript | false |
