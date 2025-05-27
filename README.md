# AI-agent-RAG_code_MS
AI agent RAG_code_MS

## 📊 RAG 데모 노트북 비교 요약

| 파일명 | 프레임워크 | 검색 백엔드 | 구조 | 특징 |
|--------|------------|--------------|-------|--------|
| `05-autogen-azuresearch.ipynb` | Autogen | Azure Cognitive Search | 에이전트 + 클라우드 검색 | 클라우드 인덱스 검색 + 생성 조합, 실제 서비스 수준 RAG |
| `05-autogen-chromadb.ipynb` | Autogen | Chroma (로컬 벡터DB) | 에이전트 + 로컬 검색 | 로컬 데이터 기반 실험, 경량화된 RAG 구조 |
| `05-semantic-kernel-azure-ai-agent.ipynb` | Semantic Kernel | 없음 (질의만) | Planner 기반 Agent | 계획-실행 구조, LLM에 명령 실행 중심 |
| `05-semantic-kernel-azuresearch.ipynb` | Semantic Kernel | Azure Cognitive Search | Planner + 검색 플러그인 | 검색 기능을 SK 플러그인으로 사용하여 조정 가능 |
| `05-semantic-kernel-chromadb.ipynb` | Semantic Kernel | Chroma DB | Planner + 로컬 검색 | 로컬 DB에서 검색 → 명령 기반 실행 구조 |
