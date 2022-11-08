# react-hooks-study
노마드코더 실전형 리액트 Hooks 강의

## Learn How to use React Hooks in 10 min (by Nico)
[리액트 Hook 10분만에 사용법 배우기](https://www.youtube.com/watch?v=yS-BU6eYUDE)

### 강의요약
- 리액트 훅 : `functional component`에서 `state`를 가질 수 있게 해줌.   
- class component, did mount, render 등 이런 것들을 안 해도 됨.   
- 모든 것들을은 하나의 function이 됨.
- 훅의 역시는 *recompose*ㅜ로부터 시작되었다. (실제로 이 recompose 라이브러리를 만든 사람은 react 팀으로 들어갔다.)
- 과연 클래스를 떠나서 함수에 머물 수 있는 방법은? setState, this를 사용하지 않아도 되는 방법은 무엇일까?
- useState는 2개를 준다. 하나는 value, 하나는 이를 변경하는 방법.
- 우리는 array로 작업을 하는데, useState가 주는 것이 array떄문
array의 첫 번째 요요소 cpount, 두 번째는 set count가 될 것이다.
- useSates는 array를 리턴하는데, 그 array의 첫번째 요소는 value이며 이는 0에서부터 시작된다. 
- class 컴포넌트를 건드려 state를 조작해야 하는 class 컴포넌트와 달리, hook을 사용하는 function형 컴포넌트는 매우 간단한 편이다.

## React Hooks for daily use! (by Nico)
[리액트 Hooks 실제 사용 예시를 알아보자!](https://www.youtube.com/watch?v=sZDvByH2mNU)

### 강의요약
- 실제 Nico가 만든 Hook인 useInput, useFetch에 관한 간략한 소개.

***

## 1.0 Introduction to useState
- Hook : react의 state machine에 연결시켜주는 기능.
- 더이상 class를 사용하지 않고, 모든 걸 function 을 통해 가능하게 해준다.
### `useState`
- 2개의 value를 return
- 첫 번째 value : item
- 두 번쨰 value : modifier(값을 변하게 하는)
- 초기에 initialstate를 세팅할 수 있는 기능을 제공해준다.
- class component를 쓸 때처럼 this와 render, setState를 사용하지 않는 것만으로도 코드가 엄청나게 짧아진다.

### CodeSandbox link : https://codesandbox.io/s/nooks-bt33o4?file=/src/App.js

## 1.1 useInput
- 기본기능 : input update
- 

### CodeSandbox link : https://codesandbox.io/s/prod-tdd-2gi788?file=/src/App.js