여름 계절학기(공학커뮤니케이션)
======================

Markdown 개요
-----------------
1. 텍스트 기반 마크업 언어
2. 2004년 존 그루버에 의해 만들어 졌음
3. 쉽게 쓰고 읽을 수 있음
4. HTML로 변환 가능
5. 확장자가 .md로 된 파일

## 1. blockqute
> first blockqute
>	> second
>	>	> third

## 2. List
1. 순서 있는 목록 첫번째
2. 두번째
3. 세번째

* 순서 없는 목록1
 * 2
  * 3

## 3. Code
	4개의 공백 또는 하나의 탭으로 들여쓰기

		들여쓰지 않은 행을 만날 때 까지 반환이 계속된다

	한 줄을 띄어쓰지 않으면 줄바꿈 인식 제대로 안됨

``` Python
e_tot = 0
o_tot = 0
for x in range(1, 101):
    if x % 2 == 0: e_tot += x
    else: o_tot += x

print("1~100까지 짝수 합 : {0}, 홀수 합 : {1}" .format(e_tot, o_tot))
```
## 4. Draw Line
* * *
***
*****
- - -
-----------------

## 5. Link
*참조 링크

// examle

Link: [google][googlelink]

[googlelink]: https://google.co.uk "Let's Go Google"

*외부 링크

[Title](link)

// examle

[Google](https://google.co.uk)

*자동 링크
문서 내 일반 URL이나 꺽쇠 괄호(‘< >’) 안의 URL은 자동으로 연결
일반적인 URL 혹은 이메일 주소인 경우

// examle

Google Homepage: https://google.co.uk

Naver Homepage: <https://naver.com>

## 6. Emphasis(강조)

// examle
이텔릭체 *별표(asterisks)* 혹은 _언더바(underscore)_ 를 사용

두껍게는 **별표(asterisks)* 혹은 __언더바(underscore)__ 를 사용

**_이텔릭체_와 두껍게** 를 같이 사용할 수 있음

취소선은 ~~물결표시(tilde)~~ 를 사용
