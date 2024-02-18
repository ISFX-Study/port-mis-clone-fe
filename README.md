# port-mis-clone
포트미스 데이터 수집(OpenAPI) 및 제공, 시각화 
<br>
<br>


### 작업 일정
- 관리, 설계, 구성, 개발  
https://app.smartsheet.com/sheets/G2MF9PfF2c2MRC9rxrVRhWwvRWcHvM7pHRq9Crw1
<br>
<br>

---
## React Overview
> 리액트 주요 내용  
 공식: https://ko.legacy.reactjs.org/docs/getting-started.html
<br>

### 특징, 장점
 - 컴포넌트 재사용 (유지보수, 생산성)
 - Virtual DOM 을 통한 화면 렌더링 성능 향상
 - 단방향 데이터 바인딩 (Up to Bottom)
 - JSX 문법 활용
 - 전자정부 표준 프레임워크 개발 도구
<br>
 
### 필요 사전 지식
 - Javascript (es6)
 - HTML
 - XML
<br>

### 관련 라이브러리
 - 리액트는 화면 렌더링만 해주므로 특정 기능 구현을 위해 라이브러리 import 필요  
   ex) grid library(그리드), Axios(통신), react-router-dom(페이지 전환/경로), Zustand(상태관리) ...
<br>
	  
### 구성 요소
 - 컴포넌트:  
   https://www.bulcode.com/blog/react-overview-definition-spa-components-hooks
 - Vritual DOM:  
   브라우저 DOM을 직접 이용하지 않고, 빈번한 작업을 가상 DOM에 접근하여 처리  
   https://callmedevmomo.medium.com/virtual-dom-react-%ED%95%B5%EC%8B%AC%EC%A0%95%EB%A6%AC-bfbfcecc4fbb
 - Hook:  
   컴포넌트의 상태(state), 생명주기 관련 활용을 위한 기능  
   useState(), useEffect(), useRef(), useContext() ...  
 - state/props:
   ![img](https://res.cloudinary.com/infinijith/image/upload/v1675404854/Infinijith%20Blog%20Images/React%20JS/Props%20vs%20State/state-structu-pic_da0ots.png)
<br>

### 기초 문법, 규칙
 - return 시 태그는 하나까지만(<> 또는 React.Fragment 이용)
 - javascript 변수 활용시 {}
 - 함수형 컴포넌트명은 대문자로 시작
 - 태그 내에서 스타일 이용시 인라인으로 작성 <div style={{속성명='속성값'}}></div>
<br>
<br>

