# rispa-server

## Plugin overview

  This plugin integrate server application for project with all necessary configuration:
  * Add [express](http://expressjs.com/) - powerful webserver

## Plugin public API
  
### `runServer`

Run server with current configuration

### `setRenderMethod`

It is a function for extend renderer  

## Usage examples 

```typescript
this.server.setRenderMethod(expressApp => {
  expressApp.use((req, res) => {
    res.end('pong')
  })
})
```
