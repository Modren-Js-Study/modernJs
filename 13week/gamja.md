## 두 번째 호출을 첫 번째 호출이 완료된 후에 수행되도록 해주세욥!

힌트: 프로미스 체이닝과 마이크로태스크 큐

```jsx
function fetchData(url) {
  return new Promise(function (resolve) {
    setTimeout(function () {
      resolve(`Data from ${url}`);
    }, 1000);
  });
}

// 에드 유어 매직 히어!
```
========================================

## 제너레이터란?
()에서 도입된 제너레이터는 코드 블록의 실행을 일시 중지했다가 필요한 시점에 재개할 수 있는 특수한 함수

- 제너레이터는 함수 실행을 여러 단계로 나눌 수 있어, ()코드를 작성하는데 유용하게 활용

- 제너레이터 함수 정의 시 '()' 구문을 사용
- '()'키워드를 사용하여 일시 중지 및 값을 반환

## 제너레이터 객체는 ()메서드를 갖죠.
이 메서드를 호출하면 제너레이터 함수의 코드 블록을 실행

단, ()표현식까지만 실행
()키워드는 제너레이터 함수의 실행을 일시 중지시키거나 ()키워드 뒤에 오는 표현식의 평가 결과를 제너레이터 함수 호출자에게 반환

==========================================