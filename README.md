<h1 align=center>🚧 Drifting PaperMod | <a href="https://blog.drifting.boats" rel="nofollow">Demo</a></h1>

<br>

本主题是 [Hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod) 的个性化版本。

## 快速开始

1. 安装 Hugo。参考文档：[Hugo Docs's - Quick Start](https://gohugo.io/getting-started/quick-start/)
   (需要 Hugo 版本 >= v0.125.3)

2. 创建 Hugo Site

```powershell
# 将下面 MySite 替换为你的网站名
hugo new site MySite --format yml
```

更多命令参考：[Hugo Docs's - hugo new site command](https://gohugo.io/commands/hugo_new_site/#synopsis)

3. 启用 Git

```powershell
cd MySite
git init .
```

4. 安装 PaperMod-PE 主题

```powershell
git submodule add --depth=1 https://github.com/DriftingBoats/Drifitng-PaperMod.git themes/Drifitng-PaperMod
```

5. 修改 Hugo 配置文件：

```yaml
theme: Drifitng-PaperMod
```

## 示例Hugo.yaml

