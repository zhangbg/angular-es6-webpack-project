##使用说明##

+ 网页调试 ： npm run dev
+ Nw调试： npm rum build && cd dist && nw .
+ Nw开发模式调试: npm run dev && nw.(使用以下配置)
```javascript
//package json
  {
      "main": "http://localhost:8080",
      "webkit":{
    	"plugin": true
      },
      "window": {
    	"frame": false,
    	"toolbar": false,
    	"height": 500,
    	"width": 1000,
    	"resizable": true,
    	"position": "center"
      }
  }
```
