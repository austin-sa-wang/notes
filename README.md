# notes

## Webpack

### Plugins

  - ProvidePlugin: Automatically load modules instead of having to import or require them everywhere.
    - To make over-arching libraries easily accessible, such as `jquery` or `angular`
    
### Loaders

  - expose-loader: The expose loader adds modules to the global object. 
    - To support libraries that depend on libraries in globals.
