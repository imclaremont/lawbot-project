이 프로젝트는 법률 분야에서의 AI 활용을 시도한 데모 프로젝트로, LangGraph + RAG 구조를 바탕으로 개인정보 보호법을 분석하고 자연어 응답을 생성합니다.

향후 다양한 법령으로 확장 가능한 구조로 설계되어 있습니다.



## LangGraph + Agentic RAG 구조

- 법령 PDF를 전처리하여 Chroma 벡터 DB로 구축 (다른 법 관련 pdf 파일을 추가해 확장 가능)
  
- GPT-4o-mini 기반 LangGraph 에이전트 워크플로우

- [질문 분류 → 법령 검색 → 해석 → 응답] Agentic 구조
  
- Human-in-the-loop(HITL) 흐름 반영
  
- 최종 답변을 PDF 보고서로 자동 저장
