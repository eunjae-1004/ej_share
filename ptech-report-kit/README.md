# P-Tech 최종보고서 도우미 키트

원주폴리텍대학 P-Tech 과정에서 생성형 AI(Claude · ChatGPT · Gemini)로 **「[서식5] 최종보고서」**를 작성할 수 있도록 만든 설정 키트입니다.
입력양식만 채우면 학습모듈 내용(Ⅰ장)과 회사 사례(Ⅱ·Ⅲ장)가 들어간 보고서가 만들어집니다.

**키트 주소:** https://github.com/eunjae-1004/ej_share/tree/main/ptech-report-kit

- 대상 교과목: 융합프로젝트실습(자재관리 프로그램 운영), 종합프로젝트실습(현장 제어기기 운영)
- 결과물: 보고서 PDF (Gemini는 Google 문서로 내보낸 뒤 PDF 저장)

## 1. 내려받기

사용할 AI를 하나 골라 ZIP 파일을 내려받으세요. 압축을 풀면 `안내` 폴더에 단계별 안내서(HTML)가 들어 있습니다.

| 사용할 AI | 내려받기 | 특징 |
|---|---|---|
| **Claude 프로젝트 (권장)** | [ptech_claude_kit.zip](https://github.com/eunjae-1004/ej_share/raw/main/ptech-report-kit/download/ptech_claude_kit.zip) | PDF 자동 생성, 사진 자동 배치 |
| ChatGPT 프로젝트 | [ptech_chatgpt_kit.zip](https://github.com/eunjae-1004/ej_share/raw/main/ptech-report-kit/download/ptech_chatgpt_kit.zip) | PDF 생성(한글 글꼴이 없으면 글꼴 첨부 또는 Word로 대체) |
| Gemini Gem | [ptech_gemini_kit.zip](https://github.com/eunjae-1004/ej_share/raw/main/ptech-report-kit/download/ptech_gemini_kit.zip) | Canvas → Google 문서 → PDF 저장 |
| 전체 | [ptech_all_kit.zip](https://github.com/eunjae-1004/ej_share/raw/main/ptech-report-kit/download/ptech_all_kit.zip) | 세 플랫폼 키트, 안내서, 샘플 보고서 6부, 학습모듈 원본 2종 |

> 링크를 누르면 바로 내려받아집니다. 안 되면 이 페이지 위쪽 초록색 **Code → Download ZIP**으로 전체를 받으세요.

## 2. 사용 순서

1. ZIP 압축을 풀고 `안내` 폴더의 HTML 안내서를 더블클릭해 엽니다.
2. 안내서대로 AI에 프로젝트(또는 Gem)를 만들고 **지침**과 **소스 파일**을 넣습니다. (처음 한 번)
3. 새 채팅에서 **시작**이라고 입력하면 입력양식이 나옵니다.
4. 입력양식을 채워 보내고, 초안을 확인한 뒤 **PDF로 만들어 주세요**(Gemini는 **보고서로 만들어 주세요**)라고 입력합니다.

## 3. 폴더 구성

| 폴더 | 내용 |
|---|---|
| `Claude/` | 지침, 소스1~5, 첨부_PDF생성코드, 학습모듈(참고용) |
| `ChatGPT/` | 지침, 통합 소스 1개, 첨부_PDF생성코드, 학습모듈(참고용) |
| `Gemini/` | 지침, 소스1(Gemini용)~5, 소스6(보고서 양식), 학습모듈(참고용) |
| `guide/` | 플랫폼별 HTML 안내서, 설정안내서, 작성스타일·업종별 예시 |
| `samples/` | 교과목별 샘플 보고서 PDF 3부씩, Gemini 양식 예시 1부 |
| `modules/` | NCS 학습모듈 원본 PDF 2종(자재관리 프로그램 운영, 현장 제어기기 운영) |
| `download/` | 위 내려받기용 ZIP |

## 4. 학습모듈 원본

- [학습모듈_자재관리프로그램운영.pdf](modules/학습모듈_자재관리프로그램운영.pdf)
- [학습모듈_현장제어기기운영.pdf](modules/학습모듈_현장제어기기운영.pdf)

> 각 플랫폼 폴더의 「학습모듈(참고용)」 폴더에는 원본 PDF가 들어 있습니다. 보고서는 소스 파일만으로 작성되며, 원본은 필요할 때만 채팅에 첨부하세요(첨부해도 원문을 그대로 옮기지 않고 가공해 씁니다).

## 5. 주의

- 회사 기밀(도면·고객사명·단가)이나 얼굴이 나온 사진은 올리지 마세요.
- 보고서의 수치는 사용자가 입력한 것만 사용합니다. 제출 전 내용을 꼭 확인하세요.
- 각 AI의 메뉴 이름과 무료 계정 제한은 바뀔 수 있습니다(2026년 11월 기준 확인).
