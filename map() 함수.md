### map() 함수

```javascript
const numbers = [1, 2, 3, 4, 5];
const result = numbers.map((n) => n *2);
console.log(result);
```

여기서 넣어주는  `n` 값은 각각 numbers[0] ... numbers[4]를 뜻하고 각 요소에 *2를 해준다는 뜻

그 결과값을 result 에 저장하고 콘솔에 출력하는 예제이다.

- 여기서 중요한 것은 `n` 은 각 배열의 요소 값