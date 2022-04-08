# babel 核心库

## @babel/core

核心库，负责源码编译，source map 以及 ast 的生成。

## @babel/cli

命令行工具，负责收集命令行配置以及配置文件的参数转换

## @babel/preset-env

预设工具集，由于 babel 自身庞大的工具集，导致用户很难记住所需要的插件，所以提供一些预设来帮开发者更加方便的使用。

## @babel/polyfill

运行时的 polyfill 注入插件，帮助注入各种兼容性 api，如 Promise 等。

