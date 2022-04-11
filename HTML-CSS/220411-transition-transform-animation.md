# transition & transform & animation

## transition
- transition 중복으로 적용하면 오류 생기니깐 중복 적용하지 말기
- easing-function -> GreenSock 사이트 참고

## transform
- perspective 함수는 맨 앞에 써야함!
- transform-origin(변환의 기준점): 50% 50%(기준값);
- perspective-origin: 50% 50%(기본값);
- 3D 효과 안에 3D 효과 있으면 3D 효과의 자식요소 3D 효과 날려버림 (이 것을 유지하기 위하여 transform-style: preverse-3d;)(기본값: flat)


## animation
- 애니메이션을 제어하는 속성! (실제 애니메이션 동작은 @keyframes)

- animation-name: none;
- animation-duration: 0s;
- animation-timing-function: ease;
- animation-delay: 0s;
- animation-iteration-count: 1;
- animation-direction: normal;
- animation-fill-mode: none;
- animation-play-state: running;
- animation: ;

- keyframes 애니메이션이름 {
	0% {}
	100% {}
}

- hover에 animation-play-state: paused;
	: 마우스 올렸을 때 일시정지하라.

## animation-direction
- normal : 기본값
- reverse : 반대로
- alternate : 왕복운동
- alternate-reverse : 반대로 왕복운동

## animation-fill-mode
- none : 기존 위치로 시작 -> 애니메이션 시작 위치로 이동 -> 동작 -> 기존 위치에서 끝 (기본값)
- forwards : 기존 위치에서 시작 -> 애니메이션 시작 위치로 이동 -> 동작 -> 애니메이션 끝 위치에서 끝
- backwards : 애니메이션 시작 위치에서 시작 -> 동작 -> 기존 위치에서 끝
- both : 애니메이션 시작 위치에서 시작 -> 동작 -> 애니메이션 위치에서 끝
