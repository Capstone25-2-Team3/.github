## [2025-2] 중앙대학교 소프트웨어학부 캡스톤 디자인(1) 프로젝트


## 👀 팀원

| 이름    | 박석진                                        | 이승화                            | 이정재                          |
| ------- | --------------------------------------------- | --------------------------------- | ------------------------------- |
| **git** | [seokjin1023](https://github.com/seokjin1023) | [lshwa](https://github.com/lshwa) | [lee1026td](https://github.com/lee1026td) |

## 📑 프로젝트 주제
Word Changer: 실시간 혐오 표현 순화 크롬 익스텐션
온라인 환경의 공격적 언어와 혐오 표현을 무조건적인 차단이 아닌, 문맥을 유지한 채 순화된 표현으로 자동 변환하여 건강한 디지털 소통 문화를 조성하는 시스템입니다. 

## 🎯 핵심 가치
'무엇을 말하지 말아야 하는가'가 아닌, **'어떻게 더 나은 방식으로 말할 수 있는가'**에 집중하는 능동적 순화(Active Purification) 

## 🛠️ 주요 기술 스택 및 아키텍처
Hybrid Model Structure
효율성과 정확도를 동시에 잡기 위해 이중 구조의 AI 모델을 채택했습니다. 

### Phase 1: KoBERT (Hate Speech Classification) 
입력 문장의 혐오 표현 포함 여부 및 유형(인종, 성별, 연령 등 10개 카테고리) 분류 

정확도 약 85% 달성 및 1차 필터링을 통한 시스템 부하 감소 

### Phase 2: LLM (Context-Aware Purification) 

GPT API를 활용하여 원문의 의도는 유지하되 공격성만 완화된 문장으로 변환 

### Implementation Details

Frontend: Chrome Extension (JavaScript) 
Backend: FastAPI, Amazon EC2 

## ✨ 기대 효과
심리적 보호: 혐오 표현 노출에 따른 청소년의 스트레스 및 위축감 감소 

교육적 기능: 순화된 표현을 제시함으로써 올바른 언어 습관 형성 유도 

소통 유지: 내용 삭제 없이 표현만 순화하여 건강한 비판과 의견 교류 가능
