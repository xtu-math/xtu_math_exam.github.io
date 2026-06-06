powershell执行命令 模板：

$time = Get-Date -Format "yyyy-MM-dd HH:mm"
$note = "这里写简短修改说明"
if (!(Test-Path CHANGELOG.md)) { Set-Content -Encoding UTF8 CHANGELOG.md "# 修改日志`n" }
Add-Content -Encoding UTF8 CHANGELOG.md "`n## $time`n- $note"



## 2026-06-07 00:02
- 修复 GitHub Pages 项目页配置，并隐藏侧边栏作者链接
