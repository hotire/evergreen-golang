# 데이터 타입 

Go 프로그래밍 언어는 다음과 같은 기본적인 데이타 타입들을 갖고 있다.

- bool

- string

- int int8 int16 int32 int64

- float32 float64 complex64 complex128

- byte / rune


## 문자열 

문자열 리터럴은 Back Quote(` `) 혹은 이중인용부호(" ")를 사용하여 표현할 수 있다.

- Back Quote (` `)로 둘러 싸인 문자열은 Raw String Literal이라 부르는데, 이 안에 있는 문자열은 별도로 해석되지 않고 Raw String 그대로의 값을 갖는다. 예를 들어, 문자열 안에 \n 이 있을 경우 이는 NewLine으로 해석되지 않는다. 또한, Back Quote은 복수 라인의 문자열을 표현할 때 자주 사용된다.