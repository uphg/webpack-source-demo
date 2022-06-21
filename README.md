# Webpack 源码阅读

## 版本

- webpack v5.10.1
- webpack-cli v4.2.0

## 运行

webapck cli

```sh
cd webpack-cli/package/webpack-cli
npm link

cd -

cd demo
npm link webpack-cli
```

webapck

```sh
cd webpack
npm link

cd -

cd demo
npm link webpack
```

## 调试

```sh
node --inspect-brk xxx/xxx
```