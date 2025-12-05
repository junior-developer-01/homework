# homework
## 총 15문항(6문항 풀음)
1번. “안녕” 출력하는 함수

설명

이름: SayHello

매개변수: 없음

기능: 호출할 때마다 안녕! 이라는 문장을 콘솔에 출력한다.

요구사항

// 사용 예시 (Main에서)
SayHello();   // 콘솔에: 안녕!

2번. 이름을 받아 인사하는 함수

설명

이름: Greet

매개변수: string name

기능: 안녕, OOO! 형태로 출력

요구사항

Greet("철수");   // 안녕, 철수!
Greet("영희");   // 안녕, 영희!

3번. 두 수를 더해서 출력하는 함수

설명

이름: PrintSum

매개변수: int a, int b

기능: 두 수의 합을 계산해서 출력

요구사항

PrintSum(3, 5);    // 결과: 8
PrintSum(10, 20);  // 결과: 30

4번. 두 수의 합을 리턴하는 함수

설명

이름: Add

매개변수: int a, int b

반환형: int

기능: 두 수의 합을 리턴(return)

요구사항

int result1 = Add(3, 5);    // result1 == 8
int result2 = Add(10, 20);  // result2 == 30

5번. 나이를 받아 성인인지 출력하는 함수

설명

이름: CheckAdult

매개변수: int age

기능:

나이가 20살 이상이면 성인입니다.

아니면 미성년자입니다. 출력

요구사항

CheckAdult(25);  // 성인입니다.
CheckAdult(17);  // 미성년자입니다.

6번. 짝수인지 홀수인지 알려주는 함수

설명

이름: IsEven

매개변수: int number

반환형: bool

기능:

짝수이면 true

홀수이면 false 리턴

요구사항

bool a = IsEven(4);  // true
bool b = IsEven(7);  // false

7번. 세 수 중 가장 큰 수를 리턴하는 함수

설명

이름: MaxOfThree

매개변수: int a, int b, int c

반환형: int

기능: a, b, c 중 가장 큰 값을 찾아 리턴

요구사항

int m1 = MaxOfThree(3, 7, 5);   // 7
int m2 = MaxOfThree(10, 2, 8);  // 10

8번. “n번 반복해서 문장 출력” 함수

설명

이름: RepeatMessage

매개변수: string message, int count

기능: for문을 사용해서 message를 count번 출력

요구사항

RepeatMessage("Hello", 3);
// Hello
// Hello
// Hello

9번. 1부터 n까지 합을 구해 리턴하는 함수

설명

이름: SumToN

매개변수: int n

반환형: int

기능: 1 + 2 + 3 + ... + n 의 합을 구해 리턴 (반복문 사용)

요구사항

int s1 = SumToN(5);   // 1+2+3+4+5 = 15
int s2 = SumToN(10);  // 1~10 합 = 55

10번. 문자열 길이를 리턴하는 함수

설명

이름: GetLength

매개변수: string text

반환형: int

기능: 문자열의 길이(text.Length)를 리턴

요구사항

int len1 = GetLength("Hello");  // 5
int len2 = GetLength("안녕하세요"); // 글자 수 5

11번. 점수에 따라 등급을 출력하는 함수

설명

이름: PrintGrade

매개변수: int score

기능:

90 이상: A

80 이상 90 미만: B

70 이상 80 미만: C

그 외: F
를 콘솔에 출력

요구사항

PrintGrade(95);  // A
PrintGrade(82);  // B
PrintGrade(71);  // C
PrintGrade(60);  // F

12번. 가격과 개수를 받아 총 가격을 리턴하는 함수

설명

이름: GetTotalPrice

매개변수: int price, int count

반환형: int

기능: price * count 를 계산해 리턴

요구사항

int t1 = GetTotalPrice(1000, 3);  // 3000
int t2 = GetTotalPrice(2500, 2);  // 5000

13번. 섭씨 온도를 화씨 온도로 변환하는 함수

화씨(F) = 섭씨(C) × 9 / 5 + 32

설명

이름: CelsiusToFahrenheit

매개변수: float celsius (또는 double)

반환형: float (또는 double)

기능: 위 공식을 이용해서 화씨 값 리턴

요구사항

float f1 = CelsiusToFahrenheit(0);    // 32
float f2 = CelsiusToFahrenheit(100);  // 212

14번. 숫자가 0이면 “Zero”, 양수면 “Positive”, 음수면 “Negative” 리턴

설명

이름: CheckNumber

매개변수: int number

반환형: string

기능:

0: "Zero"

0보다 큼: "Positive"

0보다 작음: "Negative" 리턴

요구사항

string r1 = CheckNumber(0);    // "Zero"
string r2 = CheckNumber(10);   // "Positive"
string r3 = CheckNumber(-5);   // "Negative"

15번. 간단한 메뉴 출력 함수

설명

이름: PrintMenu

매개변수: 없음

기능: 아래처럼 3줄을 그대로 출력하는 함수 작성

출력 예시

1. 게임 시작
2. 옵션
3. 종료


요구사항

// Main에서
PrintMenu();
// 위와 같은 메뉴가 콘솔에 표시되도록
