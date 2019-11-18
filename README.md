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

### React page
Creates a React page with predefined store.

Example:
```bash
schematics schematics-react:reactPage /src/components/MyPage --name=MyPage
```

with alias:
```bash
schematics schematics-react:rp /src/components/MyPage --name=MyPage
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
