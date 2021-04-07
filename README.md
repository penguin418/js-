# cookie-util.js

쿠키 사용을 도와줍니다

```jsx
/**
 * 쿠키 설정
 * @param name {string} 쿠키 이름
 * @param value {string,boolean,number} 쿠키 값
 * @param timeout 종료시간을 정합니다
 * @param timeout.hour 시간
 * @param timeout.day  일
 * @param timeout.week 주
 */
setCookie(name, value, timeout = undefined)
```

```jsx
/**
 * 쿠키 조회
 * @param name {string} 쿠키 이름
 * @returns {string|undefined}
 */
getCookie(name)
```

```jsx
/**
 * 쿠키 삭제
 * @param name {string} 쿠키 이름
 */
deleteCookie(name)
```