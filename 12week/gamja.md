1. dog 함수와 jeong 함수 중 먼저 실행될 함수는 무엇일까?

```jsx
function dog() {
    console.log('멍');
}

function jeong() {
    console.log('냥');
}

setTimeout(dog, 0);
jeong();
```

2. 자바스크립트는 (  ) 방식으로 동작한다.
    1. 싱글스레드
    2. 멀티스레드

3. 브라우저는 (  ) 방식으로 동작한다. 
    1. 싱글스레드
    2. 멀티스레드