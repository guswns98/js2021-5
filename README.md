# [강현준 201840203]
## [03월30일]
### 1. 배열
<p>기본 형태</p>
```javascript
        let array=[52,1,'안녕','잘가',true,false]
        undefined
        array
        [52,1,'안녕','잘가',true,false]
```
---

### 2.while 반복문
<p>기본 메커니즘</p>

![image description](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMDExMDRfMjMw%2FMDAxNjA0NDk3ODMxMTI0.5QjxSGuUaI0HH5gnTMiyTZHe-YKFYwOjPpacVWlQxqcg.IoclaF8kQrSZqpkw3LqTrUU_Vh9TvWtQUf0OxezHOxMg.PNG.hwang890%2Fimage.png&type=sc960_832)

<p>기본형태</p>

```jsx
    while(조건){
    실행내용(반복 내용)
}
```
---

### 3.For 반복문
<p>기본형태</p>
```jsx
for(초기화식; 조건식; 증감식){
    실행 문장;
}

//변수 선언
let output =0 ; 
//반복 수행
for(let i=0; i<=100; i++;){
    output *= i;
}
//출력
console.log(output);
실행 결과 -->5050출력
```
---

### 4.For in 반복문
 for in 반복문은  **객체(오브젝트)에서 사용하는 반복문**
<p>기본형태</p>
```jsx
    for(let 인덱스 in 배열){
        문장

    }
```

### 5.For of 반복문
 for of 반복문은 **배열에서 사용하는 반복문**
<p>기본형태</p>
```jsx
    for(let 요소 of 배열){
         객체의 프로퍼티의 개수만큼 반복적으로 실행하고자 하는 실행문

    }
```


# 강현준[201840203]
## [03월23일]
>오늘 배운 내용 요약 <br>
><ul>
<p><strong>변수 선언  (var, let, const)</strong></p>
<li>>var -->  같은 이름의 변수 선언이 돼 있더라도 다시 선언해서 데이터를 할당</li>
<li>let--> 변수의 중복 선언 x  변수의 할당된 데이터 변경 o </li>
<li>const--> 변수의 중복 선언 x  변수의 할당된 데이터 변경 x<br></li>
</ul><br>
<p><strong>typeof</strong> --> 값의 유형 , 자료형을 확인 할 때 사용</p><br>
<strong>NAN</strong>--> 숫자를 문자로 나누는등 말도안되는 수식을 작성할떄 사용 -->let IsNaN =10/"칠";

<br><p><strong>조건문 if</strong>-->조건에 부합 했을때 결과값 </p>
<p><strong>else</strong>-->조건에 부합하지 않았을 떄 결과값 </p>
```jsx
function testIf(data){
    if(data%3==0){
        console.log('나머지 0')
    }else if(data%3==1){
        console.log('나머지 1')
    }else{
        console.log('x')
    }
}
```
-->if (조건) {트루일 떄 결과} 
    else if (조건2){조건2가 트루일 때 결과}
    else {모두 false일 때 결과}

<p><strong>and 조건</strong>--> 모든 조건이 true 여야 true   &&사용  </p>
<p><strong>or 조건</strong>--> 조건 중 하나라도 충족하면 true  ||사용  </p>








# 강현준[201840203]
## [03월16일]
>오늘 배운 내용 요약<br />
>여러줄 요약<br />
>하하하하<br />

배운내용
자바 



