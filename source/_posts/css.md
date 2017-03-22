---
title: css3
date: 2017-03-15 11:32:14
tags:
---
有关css3的一些demo

### demo
#### 1.map site（地图节点）[在线调试环境](https://jsfiddle.net/lemon_yw/pydoxmyz/)     

```css
    @keyframes map-pulse { 
        0% {
            opacity: .85; 
            filter: alpha(opacity= 85);
            transform: scale(0); 
        } 
        100% {
            opacity: 0;
            filter: alpha(opacity= 0);
            transform: scale(1); 
        }
    }
```
#### 2.鼠标hover（边框向两边展开）[在线调试环境](https://jsfiddle.net/lemon_yw/9sqmh7so/)
```css
    .button .check {
       position: absolute;
       top: 0;
       left: 50%;
       margin-left: -50%;
       width: 50%;
       height: 100%;
       border-top: 1px solid red;
       border-bottom: 1px solid red;
       transform-origin: 0;
       transform: scaleX(2);
       transition: 0.3S ease-in-out
    }
```
#### 3.消息框（下方三角形带背景和边框）[在线调试环境](https://jsfiddle.net/lemon_yw/t1bk9zvg/)
```css
    .triangle {
      position:absolute;
      left:50%;
      margin-left:-10px;
      width:0px;
      height:0px;
      border-width:10px;
      border-style:solid dashed dashed dashed
    }
    .border {
      border-color:#C6CCDC transparent  transparent transparent;
      bottom: -20px;  
    }
    .bg {
      border-color:#fff transparent  transparent transparent;
      bottom: -19px;  
    }
```


