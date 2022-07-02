# lib_generateUUID
Author: [@javascriptjp](https://github.com/javascriptjp)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/K3K1AQ3A3)

## How to use?
```javascript
const UuId=seed=>{
    const d=[],r=(a,u)=>(Math.floor(Math.random()*a)+u).toString(16)
    for(const i of seed.split(""))d.push(i=="x"?r(16,0):i=="y"?r(4,8):i)
    return d.join``
}

console.log(UuId("xyxxxxxxxxxx8xxxxxxxxyxxxxxxxxxx"))
console.log(UuId("xyxxxxxxxxxx-8xxxxxxxxy-xxxxxxxxxx"))
```
