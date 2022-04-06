속성(property)의 default value 중요!

min-width : 기본값) 0 (최대한 줄어들 수 있는 수치)
max-width : 기본값) none (한계 없이 계속 늘어날 수 있기 때문)

* 특정한 기본 값이 기억나지 않을 때 : 'min-width mdn' 이런식으로 뒤에 mdn 넣어서 구글링하기

* 내가 작성한 코드를 남이 봤을 때 충분히 이해해야 함.
-> 깨끗하고 아름답게.. 작성

## margin collapsing
: 마진 중첩 (좌우로는 X / 상하로 중첩됨)

## box-sizing
- box-siznig의 기본 값 : content-box
- padding-box : padding과border 합쳐서 계산
- content -> padding(개념만 있고 적용은 안됨) -> border

***

- letter spacing : 자간
- word spacing : 단어 사이 간격
* 둘 다 기본 default value : 0

## border
border : 두께 종류 색상;
border : 두께 종류;
색상값의 default value : 글자 상속 받음

두 줄로 나오는 것 한 줄로 표현하고 싶을 때) white-space : no-wrap;

- white space: no-wrap;
- overflow: hidden;
- text-overflow: ellipsis;

CJK도 단어 단위로 적용해달라) word-break: keep all;

overflow-wrap: break-word;
: 이어진 단어에 너비가 제한되면 다음줄로 넘겨라

background-size: cover / contain

background-img에 대체텍스트 적용
: 텍스트 입력 후 css에 text-indent: -9999px;
