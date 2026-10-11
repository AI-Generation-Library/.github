# 📚 AI Generation Library

**AI로 쓴 책을, 함께 읽고 고치는 오픈소스 서재.**

AI Generation Library is an open-source library of AI-generated books, improved through community contributions.

관심 있는 주제를 AI로 한 권의 책으로 만들고, 원고와 관련 자료를 공개합니다. 누구나 책을 읽고, 오류를 고치고, 새로운 책을 제안할 수 있습니다. 책 콘텐츠와 독자용 웹 서비스를 별도 저장소로 관리합니다.

**[온라인 서재에서 읽기 →](https://ai-generation-library.github.io/library/)** · [책 원고](https://github.com/AI-Generation-Library/books) · [웹 서비스](https://github.com/AI-Generation-Library/library)

## 첫 번째 책

### [FastAPI 완전 정복](https://ai-generation-library.github.io/library/fastapi/)

Python 비동기 프로그래밍부터 REST API 설계, 데이터베이스와 인증, 성능 측정, 운영, RAG와 Agent 서비스까지 다루는 **7부·30장**의 기술서입니다. 장별 예제와 Knowledge Hub 통합 실습을 함께 제공합니다.

[책 읽기](https://ai-generation-library.github.io/library/fastapi/) · [Markdown 원고](https://github.com/AI-Generation-Library/books/tree/main/content/fastapi) · [실습 검증 범위](https://ai-generation-library.github.io/library/fastapi/appendices/verification)

## 저장소 구성

| 저장소 | 역할 | 현재 상태 |
| --- | --- | --- |
| [books](https://github.com/AI-Generation-Library/books) | 책 원고·목차·메타데이터·실습 코드 보관, 책 추가·수정 PR과 콘텐츠 검사 | FastAPI 원고 공개 |
| [library](https://github.com/AI-Generation-Library/library) | 독자를 위한 검색·웹 뷰어·학습 진도·디자인·배포, 주제별 탐색 확장 | 웹 서재 배포 |
| `book-generator` | AI 에이전트의 책 기획·목차 생성·장별 집필 파이프라인 | 설계 단계 · 저장소와 구현 준비 예정 |
| [.github](https://github.com/AI-Generation-Library/.github) | Organization 소개와 공통 기여 안내·Issue 템플릿·커뮤니티 정책 관리 | 소개 게시 · 공통 정책과 템플릿 확장 예정 |

현재 `books`의 원고를 `library`가 가져와 독자용 사이트를 만듭니다. 앞으로 `book-generator`는 콘텐츠 형식에 맞는 원고를 생성하고 `books`에 PR로 제안하는 역할을 맡습니다.

[저장소 역할과 연동 설계](https://github.com/AI-Generation-Library/books/blob/main/ARCHITECTURE.md) · [책 콘텐츠 형식](https://github.com/AI-Generation-Library/books/blob/main/CONTENT-FORMAT.md)

## 함께 만드는 방법

- **책 읽기**: [온라인 서재](https://ai-generation-library.github.io/library/)에서 목차를 따라 읽고 실습해 보세요.
- **책 제안·수정**: [books Issues](https://github.com/AI-Generation-Library/books/issues)에 주제를 제안하거나, 설명·예제·오탈자 수정 PR을 제출해 주세요. [콘텐츠 기여 안내](https://github.com/AI-Generation-Library/books/blob/main/CONTRIBUTING.md)를 참고할 수 있습니다.
- **웹 서비스 개선**: 검색·읽기 화면·접근성·디자인은 [library Issues](https://github.com/AI-Generation-Library/library/issues)와 PR로 함께 개선합니다. [서비스 기여 안내](https://github.com/AI-Generation-Library/library/blob/main/CONTRIBUTING.md)에 개발 방법이 있습니다.
- **생성기 아이디어**: 책 기획·집필 자동화 아이디어는 [books Issues](https://github.com/AI-Generation-Library/books/issues)에 제안해 주세요. 생성기 저장소가 준비되면 그곳에서 구현을 이어갑니다.

## 책을 공개하는 원칙

- **출처를 기록합니다.** AI 작성 여부, 생성 도구·모델·날짜·참고 자료를 기록합니다. 확인할 수 없는 정보는 추측하지 않습니다.
- **검증한 범위를 구분합니다.** 실행한 실습과 확인한 환경을 남기고, 미검증 내용도 표시합니다. AI가 작성한 설명과 코드는 리뷰와 수정으로 정확도를 높입니다.
- **원고와 개선 과정을 공개합니다.** Markdown 원고와 변경 이력을 관리하고, PR로 내용과 서비스를 함께 발전시킵니다.

## 라이선스

책 자료와 서비스 코드의 라이선스는 각 저장소에서 확인할 수 있습니다. 개별 의존성과 포함된 자료의 라이선스도 함께 확인해 주세요.

[books LICENSE](https://github.com/AI-Generation-Library/books/blob/main/LICENSE) · [library LICENSE](https://github.com/AI-Generation-Library/library/blob/main/LICENSE) · [Quartz 라이선스](https://github.com/AI-Generation-Library/library/blob/main/LICENSE.txt)
