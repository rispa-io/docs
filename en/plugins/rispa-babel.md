# rispa-babel

## Plugin overview

  This plugin integrate babel configuration to project. With redux and integration him to react infrastructure it will give following:
  * Add [babel](https://babeljs.io/) - transpiling library

## Plugin public API
  
### `addPlugin`
Method to add specific babel plugin to babel configuration without specific environment

```javascript
const babelPlugin = path.resolve(__dirname, '../lib/babel-plugin.js')

class Plugin extends PluginInstance {
  start() {
    this.babel.addPlugin(babelPlugin)
  }
}
```
 
### `addConfig`  

```javascript
  const whenBabelPlugin = { 
  env: {
    production: { 
      plugins: [path.resolve(__dirname, '../lib/babel-plugin.js')]
    }
  }
}

class Plugin extends PluginInstance {
  start() {
    this.babel.addConfig(whenBabelPlugin)
  }
}
```

## Usage examples 
  To access dependencies you should import them from this plugin 
