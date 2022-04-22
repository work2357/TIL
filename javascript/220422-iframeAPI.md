# Youtube iframe API

## 화면 비율 조절하기

```html
<div class="container">
    <div class="item"></div>
</div>
```

### 2:1 비율
```css
.container {
width: 300px;
background-color: royalblue;
}
.container .item {
width: 100%;
height: 0;
padding-top: 50%;
}
```

### 16:9 비율
```css
.container {
    width: 300px;
    background-color: royalblue;
}
.container .item {
    width: 100%;
    height: 0;
    padding-top: 56.25%;
}
```

---

Full HD - 1920px * 1080px

유튜브에서 소스 코드 복사로 가져오면 가져와서 보는 기능밖에 못하지만,
URL 맨 뒤 아이디 값을 가져오면 제어 가능
