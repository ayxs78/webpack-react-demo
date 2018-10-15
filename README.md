# webpack-react-demo
## webpack4.20.2+react16.5.2+babel7.1.2
## 2018-10-15
依照目前比较新的教程，使用最新版本的webpack和react搭建的项目demo  
该项目包含的模块：  
    "@babel/core": "^7.1.2",  
    "@babel/preset-env": "^7.1.0",  
    "@babel/preset-react": "^7.0.0",  
    "babel-loader": "^8.0.4",  
    "css-loader": "^1.0.0",  
    "html-loader": "^0.5.5",  
    "html-webpack-plugin": "^3.2.0",  
    "mini-css-extract-plugin": "^0.4.4",  
    "prop-types": "^15.6.2",  
    "react": "^16.5.2",  
    "react-dom": "^16.5.2",  
    "react-hot-loader": "^4.3.11",  
    "webpack": "^4.20.2",  
    "webpack-cli": "^3.1.2",  
    "webpack-dev-server": "^3.1.9"  
参考的网址：  
1.[Tutorial: How to set up React, webpack 4, and Babel 7 (2018)](https://www.valentinog.com/blog/react-webpack-babel/)  
2.[Webpack 4 Tutorial: from 0 Conf to Production Mode](https://www.valentinog.com/blog/webpack-tutorial/)  
3.[React + Webpack 4 + Babel 7 Setup Tutorial](https://www.robinwieruch.de/minimal-react-webpack-babel-setup/)  

//顺便记录一下这次使用git的坑  
git add . 报错Filename too long  
原因：git有可以创建4096长度的文件名，然而在windows最多是260，因为git用了旧版本的windows api  
解决方案：git config --global core.longpaths true  
