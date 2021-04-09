# [강현준 201840203]
## [04월06일]
### 1. 중첩 반복문
형태 
```javascript
let output = ""; // 변수
   for (let i = 0; i < 10; i++) { //i는 0부터 9까지 i를 하나씩 증가시킨다.
      for(let j = 0; j< i+1;j++){ //j는 0부터 i까지 j를 하나씩 증가시킨다.
        output += "*"; //output에 있는 데이터에 *을 하나씩 추가
    }
    output +="\n"; //줄바꿈
}
console.log(output);
```
-실행결과 
![결과](결과.png)
### 2. break 키워드<br>
무한 반복을 빠져 나갈떄 쓰는 키워드
``` javascript
// 짝수를 찾으면 break키워드로 반복문을 벗어납니다.
let i =0;
let array = [1,31,273,57,8,11,32];
let output;

while (true) {
 if (array[i] % 2 == 0){
    output = array[i];
    break;
}
    i=i+1; 
}
console.log(`처음 발견한 짝수는 ${output}입니다.`);
```
### 3. continue 키워드
반복문 내부에서 현재 반복을 멈추고 다음 반복을 진행하게함
```javascript

for (let i = 1; i<10; i++){
    if (i % 2 == 0) {
        continue; //짝수라면 다음 반복으로 넘어감  -> 이 다음 코드는 실행x
    }
    console.log(i);
}

```
### 4. 함수

+ push+pop => stack 사용가능
+ push+shift => queue 사용가능
+ stack = 먼저 넣은것은 나중에 꺼내진다 LIFO(last in first out)
+ queue = 먼저 들어간것은 먼저 꺼내진다 FIFO(first in first out) 
---
+ stack 구조
![stack](stack.png)
+ queue구조
![queue](queue.png)

+ splice 함수
  -배열에서 특정 항목을 제거 할 때 사용
  -제거하는 과정에서 해당 원소가 몇번째인지 알려줘야함
  -기존 배열 자체를 변경

+ slice 함수
  -배열을 잘라낼 때 사용
  -기존의 배열은 달라지지 않음 
  -시작 인덱스와 종료 인덱스를 같은 값을 넣으면 빈 배열이 반환됨
  

 

# [강현준 201840203]
## [03월30일]
### 1. 배열
기본 형태
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



#  강현준[201840203]
##  [03월23일]
오늘 배운 내용 요약 <br>
<ul>
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



