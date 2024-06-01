<div align="center">
<img src="./public/favicon.svg" alt="预览"/>

<h1 align="center">简约风格的网址导航页</h1>

[演示 Demo](https://www.luode.vip) / [QQ群 542544997]()

![Snipaste_2023-05-08_09-15-08](public/png/QQ截图20231019212432.png)

</div>

## 原作者

[https://github.com/jic999/moon-web-start](https://github.com/jic999/moon-web-start)

## 已经完成的功能

- 自由增删改网站

- 拖动排序

- 导入 / 导出数据

- 搜索

- 主题切换

- 夜间模式



## TODO

- ~~搜索词联想~~

- ~~移动端适配~~

- 设置项完善

- 后端服务

  - 获取 favicon

  - 同步数据

- 更多...


进入目录
```bash
cd moon-web-start
```

安装依赖
```bash
npm install -g pnpm
pnpm install
```

启动项目
```bash
npm run dev
```

# docker容器

# 1.0 版本

- 旧版本

```shell
docker pull luode0320/web-start:1.0
```

启动:

```shell
docker run -d -p 2000:2000 luode0320/web-start:1.0
```

# latest 版本

- 最新版本

```shell
docker pull luode0320/web-start:latest
```

启动:

```shell
docker run -d -p 2000:2000 luode0320/web-start:latest
```


