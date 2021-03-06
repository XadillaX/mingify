[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/cht8687/help)

<big><h1 align="center">明哥体生成器</h1></big>

<p align="center">
  <a href="https://www.npmjs.com/package/mingify">
    <img src="https://img.shields.io/npm/v/mingify.svg?style=flat-square"
         alt="NPM Version">
  </a>

 <a href="https://coveralls.io/github/cht8687/mingify?branch=master">
    <img src="https://coveralls.io/repos/cht8687/mingify/badge.svg?branch=master&service=github" alt="Coverage Status" />
 </a>

  <a href="https://travis-ci.org/cht8687/mingify">
    <img src="https://img.shields.io/travis/cht8687/mingify.svg?style=flat-square"
         alt="Build Status">
  </a>

  <a href="https://npmjs.org/package/mingify">
    <img src="http://img.shields.io/npm/dm/mingify.svg?style=flat-square"
         alt="Downloads">
  </a>

  <a href="https://david-dm.org/cht8687/mingify.svg">
    <img src="https://david-dm.org/cht8687/mingify.svg?style=flat-square"
         alt="Dependency Status">
  </a>

  <a href="https://github.com/cht8687/mingify/blob/master/LICENSE">
    <img src="https://img.shields.io/npm/l/mingify.svg?style=flat-square"
         alt="License">
  </a>
</p>

<p align="center"><big>

</big></p>


![mingify](src/example/logo.jpg)

一切起源：

>[老实说我从来没用过JQUERY，正因为我反感JQUERY。 为什么我反感，因为我完全有开发JQUERY的能力，JQUERY的底层我都了如指掌。](https://github.com/drduan/minggeJS)  
>--- mingge

引擎(底层)贡献者：

>[“我完全有开发明哥体生成器的能力，明哥体生成器的底层我都了如指掌”](https://github.com/drduan/minggeJS/issues/148)  
> --- jamesliu96

## 在线实例

[http://cht8687.github.io/mingify/example/](http://cht8687.github.io/mingify/example/)

## 使用范例

如 `mingify("Angular")`返回

```js
老实说我从来没用过Angular，正因为我反感Angular。 为什么我反感，因为我完全有开发Angular的能力，Angular的底层我都了如指掌。

虽说我反感Angular，但是Angular却在测试界占有大量的用户份额，之后我有个想法，不如重新开发一个属于自己思想，自己架构的Angular。

我给了他一个霸气的名字：MingGeAngular，

它的名字叫MingGeAngular，MingGe就是我的大名， 一看到Angular名字，就知道作者是我，知道它是国产的，让别人知道国产Angular一样做得很出色，出众

我是mingge 请支持国产minggeAngular，因为我们都是中国人.
```

CLI

```
$ mingify Angular
```

## 安装

### npm

```
$ npm install --save mingify
```

Or install CLI globally

```
$ npm install --global mingify
```

![mingify](cli.gif)

###引用：

####ES5

```js
var mingify = require('mingify');

var result = mingify("Angular");
```

####ES6

```js
import mingify from 'mingify'

const result = mingify("Angular");
```

## 如何克隆并开发

```
$ git clone git@github.com:cht8687/mingify.git
$ cd mingify
$ npm install
$ webpack-dev-server
```

然后

```
打开 http://localhost:8080/webpack-dev-server/
```
![mingify](dev.gif)

## Demo项目使用技术

1. React
2. Webpack
3. Webpack-hot-reload
4. ES6

然而，在明哥面前，这些都没什么卵用。因为所有底层他都了如指掌。

## 贡献者

*主引擎，底层：[jamesliu96](https://github.com/jamesliu96)

*Logo: [tianyuf](https://github.com/tianyuf)

## License

MIT
