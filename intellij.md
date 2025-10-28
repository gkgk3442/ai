```sh
요청사항:
- 항상 한국어로 커밋 메시지를 작성하세요.
- Conventional Commits 규칙을 따르되(type는 feat, fix, chore, docs, refactor, test, perf, style 등), 설명은 자연스러운 한국어로 작성합니다.
- 제목(요약)은 1줄로, 72자 이내의 명령형 문장으로 작성하고 마침표를 사용하지 않습니다.
- 본문은 3~5줄의 목록(불릿)으로 핵심만 간결하게 요약합니다.
- 불필요하게 긴 설명, 세부 구현 코드, 장황한 표현은 제외합니다.
- 고유명/기술명(API, Controller, Repository 등)은 영문 그대로 유지합니다.
- 브레이킹 체인지가 있으면 마지막 줄에 `BREAKING CHANGE: <내용>`을 추가합니다.
- 관련 이슈/티켓이 있으면 마지막 줄에 `Refs: <번호|URL>`을 추가합니다.

출력 형식:
- 1줄: `<type>: <짧고 명확한 한글 요약>`
- 1줄 공백
- 3~5줄 불릿 목록(각 줄은 간결한 한글 문장)
- (선택) 마지막 줄에 Refs, BREAKING CHANGE 표기

예시:
feat: 안테나 로그 API에 createdFrom, createdTo 필터 추가

- API 계층 및 Repository 쿼리에 날짜 필터 로직 추가
- Service/Controller에 createdFrom, createdTo 파라미터 반영
- OpenAPI 스펙에 신규 쿼리 파라미터 문서화
- JPA 쿼리 predicate로 날짜 조건 처리 보완

주의:
- Diff가 너무 작거나 의미가 불분명하면, 간결한 한국어로 이유를 설명하고 더 적절한 커밋 단위를 제안하세요.
- 결과에는 커밋 메시지 텍스트만 출력하세요(설명/서문/코드블록 금지).
```
