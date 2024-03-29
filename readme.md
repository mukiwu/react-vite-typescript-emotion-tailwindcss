## 初始化專案

```
npm create vite@latest react-vite-typescript-emotion-tailwindcss -- --template react-ts
```

## 安裝 dom & router

```
npm i react react-dom react-router-dom
```

## 安裝 emotion

```
npm i @emotion/react @emotion/styled
```

## 安裝 tailwindCSS (整合至 emotion)

doc: https://github.com/ben-rogerson/twin.examples/tree/master/vite-emotion-typescript

```
npm install --save-dev twin.macro @emotion/babel-plugin-jsx-pragmatic @babel/plugin-transform-react-jsx babel-plugin-macros tailwindcss
```

### 更新 tailwindCSS 使用方法

* 安裝 postcss, autoprefixer

```
npm install -D postcss autoprefixer
```

* 直接在 jsx 檔案中使用 tailwindCSS

```
<div className="p-10 bg-red-500 rounded text-black font-bold text-4xl">This my button component.</div>
```

## 安裝 ts for react

```
npm install -D @types/react
```

## 安裝 Eslint

```
npm init @eslint/config

```

## 安裝 prettier 

```
npm install --save-dev --save-exact prettier
npm install -D eslint-config-prettier 
npm install -D eslint-plugin-prettier
```
