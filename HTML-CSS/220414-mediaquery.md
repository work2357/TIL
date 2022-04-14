# Media Query

## 미디어 쿼리 사용법
- css 내부에 삽입하기
ex.
<style>
@media (max-width: 700px) {
    .container{
    margin: 0px; padding: 0px;
    }
}
</style>
- 링크로 연결할 때
<link red="stylesheet" media="(max-width: 700px)" href="test.css"/>
* text.css 파일 안에는 위 미디어쿼리 구문이 들어가야 함
