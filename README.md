# 眼界 · 舞台灯光设计工作室

React + Vite 单页作品集，使用工作区提供的实际照片和 30 秒混剪视频。源码与压缩素材全部独立放在本目录，原素材未修改。

## 运行

需要 Node.js 20.19+ 或 22.12+。

```sh
pnpm install
pnpm dev
```

也可使用 `npm install`、`npm run dev`。生产构建：`pnpm build`，输出到 `dist/`。

## 编辑入口

- `src/main.jsx`：页面结构、工作室简介、联系方式与弹窗。
- `src/style.css`：整体样式与响应式布局，版心最大 1700px。
- `src/projects.js`：六个项目的说明、年份、地点和公开报道链接。
- `public/media/`：压缩后的图片、视频和封面图。

## 内容说明

工作室简介.docx 和 ADIZERO 上海全球发布会/项目阐述.txt 均为空文件，因此工作室简介和四个缺少理念的项目文案为本版创作草稿。CLIMACOOL 和 EVO SL 文案改编自用户提供的阐述。所有工作室职责仅表述为灯光设计，不将整场活动或舞美统筹归为工作室作品。

邮箱 hello@yanjie.example、微信 YANJIE_STUDIO 为明确占位，不是真实联系方式。项目数据是本页六个项目、五个展示分类，不代表工作室历年全部业绩。正式上线前请替换联系方式并确认补写的理念。

## 项目资料来源

- CLIMACOOL：[adidas 官方发布](https://news.adidas.com/innovations/adidas-showcases-the-future-of-climacool-in-shanghai-innovation-event/s/ac007e9b-91a5-4c06-99e5-1d54f6a1e2df)，2026 年 4 月，上海浦东美术馆。
- EVO SL：[活动报道](https://www.sohu.com/a/996834026_121124663)，2026 年 3 月 11 日，上海。
- CFS：[官方赛事报道](https://www.crossfirestars.com/cn/news/view?groupNo=1765560483)，2025 年 12 月，成都金融城演艺中心。
- ADIZERO：[ConCall 报道](https://cn.concall.com/article/detail/article_id/3020)，2025 年 3 月 17 日，上海西岸穹顶艺术中心。页面沿用用户文件夹中的项目标题，报道中的活动名称为 ADIZERO 0 系列科技发布会。
- 川超之夜：[国家体育总局报道](https://www.sport.gov.cn/n14471/n14494/n14544/c29421616/content.html)，2026 年 1 月 10 日，攀枝花。
- 四川工 BA：[人民网报道](https://sc.people.com.cn/n2/2026/0912/c345167-41694275.html)，2026 年 9 月 11 日，四川省体育馆。

地点与年份按文件夹标题、照片和公开报道匹配；作品身份以用户提供的素材为依据。图片来源映射保留在 `image-index.json`。Google Fonts 加载失败时自动回退到本机字体。网站当前仅本地预览，尚未公开部署。
