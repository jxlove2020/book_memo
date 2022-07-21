# BookMemo App

### 설치

```bash
mkdir book_memo
cd book_memo
# . 이 만들어진 폴더(book_memo)안에 설치한다는 뜻입니다.
npx create-react-app . --template typescript
```

### 설치할 npm 라이브러리

```bash
npm i react-router-dom
# react-router-dom 사용하는 방법은 App.tsx 파일 참고
```

```bash
npm i react-error-boundary
# react-router-dom 사용하는 방법은 App.tsx 파일 참고
# 런타임 에러 발생시 해당 컴포넌트로 이동
```

```bash
npm i redux react-redux redux-saga redux-actions @redux-devtools/extension
# 리덕스 사용 라이브러리

# 타입이 없기 때문에 Dev 의존성 설치
npm i @types/react-redux @types/redux-actions -D
```
