# AutoOps-MultiAgent

基于 Multi-Agent 协同与长链路推理的运营自动化系统。

## Features

- 多 Agent 协同
- 长链路推理
- 自动运营分析
- 异常检测
- 自动报告生成
- 风险控制
- FastAPI API 服务

## Quick Start

```bash
pip install -r backend/requirements.txt

cd backend

uvicorn main:app --reload
```

## API

POST /run

```json
{
  "query": "分析骑手拒单率高的问题"
}
```