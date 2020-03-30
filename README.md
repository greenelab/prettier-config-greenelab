### prettier-config-greenelab

Prettier config


### Installation

`yarn add --dev git+https://git@github.com/greenelab/prettier-config-greenelab.git`



### Usage

See: https://prettier.io/docs/en/configuration.html#sharing-configurations

In a `.prettierrc.yaml` file:

```yaml
prettier-config-greenelab
```
    

  
### Usage in `VSCode`

Install the [`Prettier extension for VSCode`](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode).

Then, in `settings.json`:

```json
"prettier.packageManager": "yarn",
"editor.defaultFormatter": "esbenp.prettier-vscode"
```

Then, in `keybindings.json`:

```json
{
  "key": "ctrl+alt+f",
  "command": "editor.action.formatDocument",
}
```
