# TIL

> Today I learned
> 오늘 배운 내용을 복습하고 정리해봅시다.

- Git
- Linux
- Markdown

-9/27
저장 조건 반복 : 프로그래밍 언어의 목적 
코드 입력 후 터미널에서 실행하는 법: python 파일명
파일명 첫 알파벳+tab = 자동완성
터미널에서 위아래 방향키이용하면 과거의 코드 확인 가능 
파이썬앞에 #을 붙이면 이 부분은 코드가 아니라는 주석임
띄어쓰기에 따라 다른 명령어로 인식됨
!대소문자에 따라 다른 언어로 인식됨!
프로그램에서 =는 '할당(대입)했다'의 의미
ctrl+/ = 주석처리로 변환
이름이 똑같으면 대입할 수 있는 데이터는 한개
대입할 수 있는 데이터: 1.숫자(int), 2.글자(string), 3.참-거짓(boolean) True/False
리스트에 있는 숫자는 0번째부터 시작
EX]dust_list = [10, 20, 0, 50, 100]
50은 3번째 ,print(dust_list[3]) 실행시 결과는 50나옴 
'서울': 100 = 서울:키 100:밸류
리스트는 []
dict는 {
}

조건 여러개 붙일때
if
elif
elif
.
.
else

-dust 150보다 크다면 => 매우 나쁨
-80~150 => 나쁨
-30~79 => 보통
-0~29 => 좋음 
이라는 조건 생성시 코드 작성
->
dust=100
if 150 <= dust:
    print('매우 나쁨')
elif 80 <= dust < 150:
    print('나쁨')
elif 30 <= dust and dust < 80:
    print('보통')
else:
    print('좋음')
elif는 무조건 조건을 작성, else는 조건이 없어도 됨

코드에서의 등호는 무조건 오른쪽부터 실행 
n=n+1 
while문은 조건이 false가 될때까지 반복 

for item in list
menus = ['돈까스', '라면', '삼겹살', '피자']
for menu in menus:
    print(menu)     -> 메뉴를 조각냄 

.은 집합(상자)안에서 도구를 꺼낸다의 의미 ex) random.randint()
공구상자(집합)을 불러오는 함수 import

https://~~ =>주소 / ~~ =>목적
?이후로는 데이터 
&이후로는 데이터 

List, dict와 같은  데이터 세부사항 접근할때 []
함수 이용시에 ()
set() & set() => &는 교집합을 구해줌


참고사이트: pep8 파이썬 작성 가이드

10/04
## 변수 
1. Number 
int: 정수, float: 소수, complex: 복합 (1-4j), c.imag: 소수만 추출, c.real: 정수만 추출
2. Boolean
True, False로 이루어진 타입 
3. None
데이터 없음을 의미
4. String
문자열을 의미, `,`과`"` 모두 사용 가능, 둘 중 하나 통일하는 걸 추천 
string interpolation
1. %-formatting
print('홍길동은 %s살입니다.'% age) => 홍길동은 10살입니다.
2. str.format()
print('홍길동은 {}살입니다.'.format(age)) => 홍길동은 10살입니다.
3. f-string -> 가장 최신
print(f'홍길동은 {age}살입니다.') => 홍길동은 10살입니다.

