# 标题中的时代：人民日报标题关键词变迁可视化 Demo

这是《数字人文技术与方法》期末展示项目的本地交互 Demo，用模拟趋势数据和示例标题展示一条数字人文研究方法链路：

- 时间滑块切换历史阶段
- 阶段关键词词云
- Top 关键词柱状图
- 多关键词趋势折线图
- 关键词共现网络
- 标题档案卡片
- 方法链路高亮

> 注：本 Demo 使用模拟趋势数据与示例标题，用于课堂展示研究设计；正式研究需替换为人民日报图文数据库导出的真实标题。

## 本地预览

直接打开：

```bash
open demo/index.html
```

或使用任意静态服务器：

```bash
python3 -m http.server 3000
```

然后访问：

```text
http://localhost:3000/demo/
```

## Vercel 部署

本仓库已经包含 `vercel.json`，部署后访问根路径 `/` 会自动展示 `demo/index.html`。

### 方式一：Vercel 网页导入 GitHub 仓库

1. 打开 <https://vercel.com/new>
2. Import 这个 GitHub 仓库
3. Framework Preset 选择 `Other`
4. Build Command 留空
5. Output Directory 留空
6. 点击 Deploy

### 方式二：Vercel CLI

```bash
npm i -g vercel
vercel
```

按提示选择当前目录即可。
