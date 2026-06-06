powershell执行命令 模板：

$time = Get-Date -Format "yyyy-MM-dd HH:mm"
$note = "修复 GitHub Pages 配置"
Add-Content -Encoding UTF8 CHANGELOG.md "`n## $time`n- $note"

git status
git add CHANGELOG.md
git commit -m "Update changelog"


# 修改日志

## 2026-06-07 00:02
- 修复 GitHub Pages 项目页配置，并隐藏侧边栏作者链接

## 2026-06-07 01:27
- 修复 GitHub Pages 配置
