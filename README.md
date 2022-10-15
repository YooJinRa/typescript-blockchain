# 타입스크립트 이해

- 2022.10.15-16

---

### JSDoc

- VS Code에서 순수한 자바스크립트 소스코드에 다음과 같이 `@ts-check` 를 주석으로 추가하면 TypeScript처럼 타입 및 에러 체크 가능
- JSDoc은 자바스크립트 API 문서 생성기
- 자바스크립트 소스코드에 JSDoc 형식의 주석을 추가하면 API를 설명하는 HTML 문서를 생성 가능
- JSDoc 주석은 `/** ... */` 사이에 기술

```
/ @ts-check
/**
 * Initializes the project
 * @param {object} config
 * @param {boolean} config.debug
 * @param {string} config.url
 * @returns boolean
 */
```
