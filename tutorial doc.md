# Webpack 4, and video tutorial used is **Learn Webpack from Freecodecamp**
## cideo Url https://www.youtube.com/watch?v=MpGLUVbqoYQ 

## set mode
`mode:'development '` or `mode: `production``

## `Eval` may be evil some time.

By default webpack use `eval(....)` everhwere in their produced bundle file,
Image before setting `devtool:"none"`

which you can turn off by setting 

```
devtool: "none"
```

## Bare minimum file structure of a webpack config `weback.config.js`
```
const path=require("path");
module.export={
mode:"development",
entry:"./src/app.js",
output:{
filename:"main.js",
path:path.resolve(__dirname,'dist')
}

}```

This is the bare minimum you should be having by the way


