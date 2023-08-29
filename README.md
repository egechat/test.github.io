# vue3-vite-screen

可视化大屏

基于Vue3.2 + ECharts 5 开发大屏可视化项目

这个项目是跟着 程序员Sunday 老师的视频，一步一步敲出来的，效果很不错。

在此感谢 程序员Sunday 老师的无私奉献。

[2023最新：ECharts 数据可视化大屏项目](https://www.bilibili.com/video/BV1yu411E7cm?p=1&vd_source=4c524e8e506ca061863d2041deba2db8)


### 1.安装vite

```
npm creat vite@latest 
```

问 projetc name： 写名字
然后选框架vue，语言js
cd 到项目里面

## 2.Project setup 

```
npm i
```

### 3.Compiles and hot-reloads for development


```
npm run dev
```

然后就得到一个最初的页面 项目
### 4.taildwind install 打开tailwindcss官网

<!-- 点frameword guides，找到vite，using vue -->

```
cnpm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
<!-- 生成tailwind.config.js 点进去按照下一步改了-->

```
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### 5. 改src下的style css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
然后run
```
npm run dev
```

### .Compiles and minifies for production

```
npm run build
```

## 大屏展示

演示地址：[https://huzgl.github.io/vue3-vite-screen/](https://huzgl.github.io/vue3-vite-screen/)

![大屏展示.png](show.png)
