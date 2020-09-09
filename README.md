# Josa
한국어 받침에 따른 조사를 구분합니다.
[![TypeScript](https://img.shields.io/badge/Built%20with-Typescript-informational?logo=typescript)](https://www.typescriptlang.org/)
## 조사?
조사란 주로 체언에 붙어 뒤에 오는 다른 단어에 대하여 가지는 문법적 관계를 표시하거나 그 말의 뜻을 도와주는 품사입니다.
(출처: [네이버 지식백과](https://terms.naver.com/entry.nhn?docId=548582&cid=46674&categoryId=46674))
## How it works?
이 라이브러리는 한국어 체언의 받침 유무를 확인하여 그에 맞는 조사를 붙여 반환합니다.<br />
한글이 아닐 경우에는 ```Word is not Hangul.```이라는 예외를 발생시킵니다.
## How to use?
```typescript
console.log(new Josa('사람'/* 체언 */, '와'/*조사 예시*/).execute());
```
위와 같은 식으로 사용할 수 있습니다.
