# GitHub Pages 部署说明

## 1. 新建 GitHub 仓库
仓库名可随意，例如：template-editor-preview

## 2. 上传文件
把本目录里的 `index.html` 上传到仓库根目录。

## 3. 开启 GitHub Pages
进入仓库：
Settings → Pages

然后设置：
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

保存后等待几十秒到几分钟。

## 4. 获取公开链接
GitHub Pages 会生成一个公开地址，通常类似：

`https://你的github用户名.github.io/仓库名/`

## 5. 导入 Figma
把这个公开链接粘贴到 HTML to Figma 插件里。

## 说明
如果样式有轻微偏差，通常是插件对模糊、渐变、字体的解析差异导致的，导入后在 Figma 里微调即可。
