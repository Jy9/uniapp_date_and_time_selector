# Uni-app 日期时间选择器组件

一个功能丰富的 uni-app 日期时间选择器组件（mx-datepicker），支持日期选择、时间选择、日期时间选择、日期范围选择、日期时间范围选择等多种模式。

## 功能特性

- 5 种选择模式：日期 / 时间 / 日期时间 / 日期范围 / 日期时间范围
- 日历 Swiper 滑动切换月份
- 年份快速切换
- 时间精确到秒
- 自定义主题色
- 自定义开始/结束文案（如"入住"/"离店"）
- 日期小圆点和提示信息

## 技术栈

- uni-app (Vue.js)

## 使用方式

1. 将 `components/mx-datepicker` 目录复制到你的 uni-app 项目中
2. 在页面中引入组件：

```vue
<mx-datepicker @confirm="onConfirm" type="date" />
```

3. 运行项目：`npm run dev:h5`
