```js
const {imgur} = require("imgur-upload-api")

async function upload(url){
  const response = await imgur(url)
  console.log(response)
  
}

upload(url)
```
