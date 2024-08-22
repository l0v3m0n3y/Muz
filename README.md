# Muz
JavaScript library for l.muz.kr link shorter
# main
```js
async function main(){
    const {muz} = require('./muz');
    const url= new muz();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
