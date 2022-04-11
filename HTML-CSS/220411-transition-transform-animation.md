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
