# Type Conversion (형 변환)

## 일치 연산자 (===)
```javascript
const a = 1
const b = '1'

console.log(a === b)

// false```

## 동등 연산자 (==)
: 형 변환이 일어나게 됨
```javascript
const a = 1
const b = '1'

console.log(a == b)

// true

- Truthy (참 같은 값) : true, {}, [], 1, 2, 'false', -12, '3.14',...
- Falsy (거짓 같은 값) : false, '', null, undefined, 0, -0, NaN

```javascript
if(false) {
	console.log(123)
}

// truthy가 아니기 때문에 아무것도 뜨지 않음

if('false') {
	console.log(123)
}

// 123
