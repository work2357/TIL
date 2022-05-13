# callback (콜백)
1. 함수의 인수로 사용되는 함수
	ex. setTimeout(함수, 시간): 타이머함수 안에서 사용되는 함수!
2. 특정한 실행 위치를 보장해주는 용도로 많이 사용됨

```javascript
function timeout() {
    setTimeout(() => {
        console.log('Heropy!')
    }, 3000)
}
timeout();
console.log('Done!')

// Done! Heropy!
```

```javascript
function timeout(cb) {
    setTimeout(() => {
        console.log('Heropy!')
				cb()
    }, 3000)
}
timeout(() {
	console.log('Done!')
});

// Heropy! Done
```
