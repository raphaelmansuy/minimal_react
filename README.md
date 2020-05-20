# A minimal react boilerplate

## To install
```bash
npm install
```

## To start
```
npm start
```

## Structure of the application

### src/index.js
```javascript
import React from 'react'
import ReactDOM from 'react-dom'


const App = () => {
    return( 
        <h1>Hello</h1>
   )
}

ReactDOM.render(<App/>,document.getElementById('root'))

```

### public/index.html
````html
<html>
  <body>
      <div id="root"/>
  </body>
</html>

```
