# 📚 AI Generation Library

**AI로 쓴 책을, 함께 읽고 고치는 오픈소스 서재.**

AI Generation Library is an open-source library of AI-generated books, improved through community contributions.

관심 있는 주제를 AI로 한 권의 책으로 만들고, 원고와 관련 자료를 공개합니다. 누구나 책을 읽고, 오류를 고치고, 새로운 책을 제안할 수 있습니다. 책 콘텐츠와 독자용 웹 서비스를 별도 저장소로 관리합니다.

**[온라인 서재에서 읽기 →](https://ai-generation-library.github.io/library/)** · [책 원고](https://github.com/AI-Generation-Library/books) · [책 생성기](https://github.com/AI-Generation-Library/book-generator)

책 목록과 목차는 [온라인 서재](https://ai-generation-library.github.io/library/)에서 확인하세요. 서재가 책 메타데이터로 목록을 생성하므로 새로운 책을 추가할 때 이 소개 문서를 수정할 필요가 없습니다.

## 저장소 구성

| 저장소 | 역할 |
| --- | --- |
| [books](https://github.com/AI-Generation-Library/books) | 책 원고·목차·메타데이터·실습 코드, 책 추가·수정 PR과 콘텐츠 검사 |
| [library](https://github.com/AI-Generation-Library/library) | 독자를 위한 검색·웹 뷰어·학습 진도·디자인·배포 |
| [book-generator](https://github.com/AI-Generation-Library/book-generator) | 사용자 API 키로 실행하는 로컬 웹 화면과 CLI, AI 기획·목차·장별 집필·원고 ZIP |
| [.github](https://github.com/AI-Generation-Library/.github) | Organization 소개. 공통 기여 안내·Issue 템플릿·커뮤니티 정책을 확장할 저장소 |

`book-generator`로 초안을 작성하고 내용을 검토한 뒤 `books`에 PR로 제안합니다. `library`가 반영된 원고를 가져와 독자용 사이트를 만듭니다.

## 자신의 AI로 책 만들기

[book-generator 사용 안내](https://github.com/AI-Generation-Library/book-generator#시작하기)에 따라 컴퓨터에서 로컬 웹 화면 또는 CLI를 실행하세요. **OpenAI·Claude·Gemini** 중 제공자와 모델을 선택하고 자신의 API 키를 입력합니다. 비용은 그 키의 제공자 계정에 청구되며 키를 설정·원고·체크포인트에 저장하지 않습니다.

주제·독자·장 수와 원하는 목차를 입력하면 장별 Markdown, 목차·메타데이터, 생성 기록과 ZIP을 만듭니다. 출력 예산, 중단과 재개, 키 없는 데모를 지원합니다. 결과는 미검수 초안이므로 사실·출처·예제를 확인한 뒤 공개하세요.

[저장소 역할과 연동 설계](https://github.com/AI-Generation-Library/books/blob/main/ARCHITECTURE.md) · [책 콘텐츠 형식](https://github.com/AI-Generation-Library/books/blob/main/CONTENT-FORMAT.md)

## 함께 만드는 방법

- **책 읽기**: [온라인 서재](https://ai-generation-library.github.io/library/)에서 목차를 따라 읽고 실습해 보세요.
- **책 제안·수정**: [books Issues](https://github.com/AI-Generation-Library/books/issues)에 주제를 제안하거나, 설명·예제·오탈자 수정 PR을 제출해 주세요. [콘텐츠 기여 안내](https://github.com/AI-Generation-Library/books/blob/main/CONTRIBUTING.md)를 참고할 수 있습니다.
- **웹 서비스 개선**: 검색·읽기 화면·접근성·디자인은 [library Issues](https://github.com/AI-Generation-Library/library/issues)와 PR로 함께 개선합니다. [서비스 기여 안내](https://github.com/AI-Generation-Library/library/blob/main/CONTRIBUTING.md)에 개발 방법이 있습니다.
- **생성기 개선**: 제공자 연동·집필 흐름·웹 화면·CLI는 [book-generator Issues](https://github.com/AI-Generation-Library/book-generator/issues)와 PR로 개선합니다. [생성기 기여 안내](https://github.com/AI-Generation-Library/book-generator/blob/main/CONTRIBUTING.md)를 참고하세요.

## 책을 공개하는 원칙

- **출처를 기록합니다.** AI 작성 여부, 생성 도구·모델·날짜·참고 자료를 기록합니다. 확인할 수 없는 정보는 추측하지 않습니다.
- **검증한 범위를 구분합니다.** 실행한 실습과 확인한 환경을 남기고, 미검증 내용도 표시합니다. AI가 작성한 설명과 코드는 리뷰와 수정으로 정확도를 높입니다.
- **원고와 개선 과정을 공개합니다.** Markdown 원고와 변경 이력을 관리하고, PR로 내용과 서비스를 함께 발전시킵니다.

## 라이선스

책 자료와 서비스 코드의 라이선스는 각 저장소에서 확인할 수 있습니다. 개별 의존성과 포함된 자료의 라이선스도 함께 확인해 주세요.

[books LICENSE](https://github.com/AI-Generation-Library/books/blob/main/LICENSE) · [library LICENSE](https://github.com/AI-Generation-Library/library/blob/main/LICENSE) · [book-generator LICENSE](https://github.com/AI-Generation-Library/book-generator/blob/main/LICENSE) · [Quartz 라이선스](https://github.com/AI-Generation-Library/library/blob/main/LICENSE.txt)
