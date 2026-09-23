# SEO 日志分析器

把 Web 服务器日志转换为清晰的 SEO 抓取数据，辅助分析百度蜘蛛访问页面、状态码和响应速度。

## 核心功能
- 识别常见搜索引擎 User-Agent
- 按 URL 和状态码聚合访问记录
- 发现 404、5xx 和慢页面
- 支持离线分析与 JSON 导出

## 使用
```powershell
python tool.py --demo
python tool.py --input sample.csv --json
```
User-Agent 只能作为日志分类依据，不能单独证明请求来源。请结合 IP、时间和服务器记录综合判断。

官网：https://jta.mobi  
QQ群：1039545483

## 许可证
MIT License
