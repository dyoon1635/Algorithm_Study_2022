# Algorithm_Study_2022

- 코딩테스트를 대비하기 위해 1주에 알고리즘 하나씩 타파하는 스터디입니다.
- 언어 : Python
- 참고 사이트 : [백준](https://www.acmicpc.net/) / [프로그래머스](https://programmers.co.kr/) / [Leetcode](https://leetcode.com/explore/) / [SW Expert Academy](https://swexpertacademy.com/)

## 스터디 방식
#### 1) 매 주 돌아가며 3문제 제출 및 발표를 한다. 
- 문제는 순서인 사람이 해당 주 월요일 오전 8시 전까지 제출 
  + 예시 : 다음주 그리디 담당인 A님은 다른분의 발표 이후 <br>
  + **`2/24 목요일`** ~ **`2/28일 월요일 오전 8시 전까지`** 문제 3개 먼저 제출. <br>
  + **`3/3 목요일`** 해당 주에 공부해온 알고리즘 md 파일 미리 업로드 및 모임시 발표

#### 2) 3문제는 난이도를 쉬움, 보통, 어려움 순으로 준비한다. 
  - **`쉬움`** : 백준 = 브론즈 ~ 실버 5 / 프로그래머스 = 레벨1
  - **`보통`** : 백준 = 실버 4 ~ 실버 2 /  프로그래머스 = 레벨2
  - **`어려움`** : 백준 = 실버 1 이상 / 프로그래머스 = 레벨3

#### 3) 발표는 마크다운 파일로 만들어 알고리즘 유형 폴더 안에 올린다. 
 - 아래의 **파일 및 폴더 구조** 내용 참고. 본인 폴더 아님
  
#### 4) 주 2회 모여서 코드리뷰와 알고리즘 설명을 한다.
- [1회차] 화요일 오후 9시전 (모임 X): 
  + `쉬움`단계 1문제 풀어오고, 다른 사람 코드 리뷰 적기. 
  + 궁금한 점, 개선점, 칭찬 등을 구체적으로 댓글로 남겨주세요 (말투는 서로 부드럽게 부탁드려요~)
    + 궁금 : '{}번째 줄 A가 아니라 B를 사용하신 이유는 뭔가요?'
    + 개선 : 'A님은 이렇게 하셨는데 이부분 이렇게 하는건 어떻게 생각하세요?'
    + 칭찬 : '여기 이걸 쓰시다니 너무 효율적이네요'

- [2회차] 목요일 오후 9시 (모임 O) : 
  + 모임 전까지 `보통`단계 1문제 풀어오고 다른 사람 코드 리뷰, 9시부터는 공부해온 알고리즘 발표 및 질문/답변 시간

- [3회차(유동)] 금요일 오후 9시 (모임 O) : 
  + `어려움` 단계 문제를 시도해 본 사람들끼리 모여 코드리뷰. (못 풀었지만 시도한 코드를 올려도 괜찮습니다)

<br>

## 파일 및 폴더 구조
- 파일 이름 규칙 : 문제출처-문제번호-문제이름.py    *(문제 번호 없으면 기재 X. 문제 이름 내에 공백이 있다면 _ 로 구분)*
  + 예시 : `BOJ-1931-회의실_배정.py`
- 문제 풀이 코드가 있는 .py 파일은 **본인 폴더**에 넣기 (문제유형폴더 / 자기폴더 / 파이썬파일)
  + 예시 : 문제 푼 python 파일 -> `greedy` / `ohjiae` / `BOJ-1931-회의실_배정.py`
- 발표용 .md 파일은 **알고리즘 유형 폴더**에 넣기 (문제유형폴더 / 마크다운파일)
  + 예시 : 발표용 마크다운 파일 ->  `greedy` / `Greedy-오지애.md`

<br>

## Commit Message Convention
#### 알고리즘 유형:[이슈번호] 작성자 - 문제이름
  + 예시 : `Greedy:[#23] ohjiae - 회의실 배정`

<br>

## Issue Convention
#### [문제출처] 문제번호 - 문제이름 (발표자)  *(문제 번호 없으면 기재 X)*
  + 예시 : `[백준] 1931 - 회의실 배정 (오지애)`
  + `[백준] 1003 - 피보나치 함수`
  + `[프로그래머스] 체육복`

#### 태그 **3개** 달아주세요
- 태그는 대부분 생성되어 있으나, 없을 시 생성해서 추가해주세요 (영문 기본, 첫 글자 대문자)
  + 문제출처 : 백준 = `BOJ`, 프로그래머스 = `Programmers`, 릿코드 = `LeetCode`, 삼성 SWEA = `SWEA`
  + 알고리즘 유형 : `Greedy`, `DP`
  + 난이도 : `쉬움`, `보통`, `어려움` 


## 도움이 될만한 링크
#### 마크다운 작성법 
- [드림코딩 엘리님 유튜브 / 7분](https://youtu.be/kMEb_BzyUqk)
#### 깃허브 설정 및 기본 사용법 (터미널 사용)
- [드림코딩 엘리님 유튜브 / 47분](https://youtu.be/Z9dvM7qgN9s)
- [우유식빵님 티스토리 블로그](https://waytocse.tistory.com/59)
