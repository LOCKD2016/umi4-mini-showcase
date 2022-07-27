使用的 Antd Pro pro-cli 脚手架创建的项目

打开二级管理页查看控制台打印的日志,一级路由"管理页"和二级路由"二级管理页"中 component 属性值都为 undefined,无法区分哪个路由是有组件的,默认的面包屑配置中所有的面包屑都是可点击的,但是像一级路由"管理页"这种父级菜单没有 component,点击之后就会跳转到空白页,所以需要自定义 itemRender,根据 route 中 component 属性是否有值来判断是否可点击

![加载失败](https://github.com/LOCKD2016/umi4-mini-showcase/raw/master/public/screenshot-20220727-135349.png)

# Ant Design Pro

This project is initialized with [Ant Design Pro](https://pro.ant.design). Follow is the quick guide for how to use.

## Environment Prepare

Install `node_modules`:

```bash
npm install
```

or

```bash
yarn
```

## Provided Scripts

Ant Design Pro provides some useful script to help you quick start and build with web project, code style check and test.

Scripts provided in `package.json`. It's safe to modify or add additional script:

### Start project

```bash
npm start
```
