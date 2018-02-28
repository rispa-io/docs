# rispa-webpack

## Plugin overview

  This plugin integrate webpack build system with webpack-blocks extends:
  * Add [webpack](https://webpack.js.org/) - powerful build system
  * Add [webpack-blocks](https://github.com/andywer/webpack-blocks) - Configure webpack using functional feature blocks

## Plugin public API
  
### `runBuild`

Run webpack build with current configuration

### `devServer`

Run dev server on specified express application  

### `addClientConfig`

Add config block to client configuration

### `addClientEntry`

Add entry to config `(name, ...paths)` 

### `addClientMiddleware`

Add middleware to process webpack configuration 


## Usage examples 

Client configuration override common configuration