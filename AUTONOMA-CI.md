# Autonoma Planner CI（mall）

本仓库包含：
- ：后端（Spring Boot 多模块，重点 ）
- ：管理后台前端（Vue）

## Secrets

仓库 → Settings → Secrets and variables → Actions：

| Secret | 必填 |
|--------|------|
|  | 是 |
|  | 是（建议新建 mall 专用 App） |
|  | 是 |
|  | 否 |
|  | 否（coding_agent=claude 时） |

## 触发

Actions → **Autonoma Planner · mall full scan** → Run workflow  
首次建议 。

预览环境：http://39.106.211.71/ （执行用例时再用 deployment-signal）
