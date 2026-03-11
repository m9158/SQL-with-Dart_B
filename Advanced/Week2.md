# SQL_ADVANCED 2주차 정규 과제 

📌SQL_ADVANCED 정규과제는 매주 정해진 분량의 『*혼자 공부하는 SQL*』 을 읽고 학습하는 것입니다. 이번주는 아래의 **SQL_ADVANCED_2nd_TIL**에 나열된 분량을 읽고 공부하시면 됩니다.

아래의 문제를 풀어보며 학습 내용을 점검하세요. 문제를 해결하는 과정에서 개념을 스스로 정리하고, 필요한 경우 제시된 강의를 참고하여 보완하는 것이 좋습니다.

<!-- 강의 링크는 아래와 같습니다.
https://www.youtube.com/watch?v=_JURyg_KzHE&list=PLVsNizTWUw7GCfy5RH27cQL5MeKYnl8Pm&index=7
https://www.youtube.com/watch?v=6qkPy7RfLqQ&list=PLVsNizTWUw7GCfy5RH27cQL5MeKYnl8Pm&index=8
https://www.youtube.com/watch?v=WWAFAm9op2U&list=PLVsNizTWUw7GCfy5RH27cQL5MeKYnl8Pm&index=9
-->

**교재 실습 예제 파일은 07_SQL_ADVANCED_Template 레포지토리의 src 폴더에 업로드되어 있습니다. market_db 파일도 해당 폴더에 함께 포함되어 있으니 참고하시기 바랍니다.**

**👀(수행 인증샷은 필수입니다.)** 

## SQL_ADVANCED_2nd_TIL

### 3장 SQL 기본 문법
#### 01. 기본 중에 기본 SELECT ~ FROM ~ WHERE
#### 02. 좀 더 깊게 알아보는 SELECT문
#### 03. 데이터 변경을 위한 SQL문


## Study Schedule

| 주차  | 공부 범위     | 완료 여부 |
| ----- | ------------- | --------- |
| 1주차 | p.24~99    | ✅         |
| 2주차 | p.102~155   | ✅         |
| 3주차 | p.158~213  | 🍽️         |
| 4주차 | p.216~271 | 🍽️         |
| 5주차 | p.274~327 | 🍽️         |
| 6주차 | p.330~369 | 🍽️         |
| 7주차 | p.372~407 | 🍽️         |


<br>

<!-- 여기까진 그대로 둬 주세요-->

---

# 1️⃣ 학습 내용 정리

## 1. 기본 중에 기본 SELECT ~ FROM ~ WHERE

<!-- 기본적인 SQL 문법에 관해 배우게 된 점을 적어주세요. -->

1. select, from, wherem, group by, having 절에 대해 배웠습니다.



<!-- 이번 챕터에서 제시된 실습을 흐름에 맞게 진행한 후, 실습 과정이 보일 수 있도록 인증 사진을 3~4장 제출해 주세요. -->

<img width="572" height="141" alt="image" src="https://github.com/user-attachments/assets/cf55b9c3-a0cd-4dd2-b0a7-90551e68adfd" />



~~~
원하는 값을 채워넣는 방법
~~~



<img width="521" height="110" alt="image" src="https://github.com/user-attachments/assets/dae7252f-dc7e-430b-a49e-43fba240e7b5" />



~~~
두 개의 값을 한번에 채워 넣는 방법
~~~



<img width="425" height="110" alt="image" src="https://github.com/user-attachments/assets/6927d025-d35e-4485-8a76-d2ec1aa9af54" />


~~~
원하는 칼럼의 값 단위를 수정하는 방법
~~~




<img width="423" height="102" alt="image" src="https://github.com/user-attachments/assets/27df8f01-edba-406f-9baa-96335e61065b" />



~~~
특정 조건을 만족하는 값들을 지우는 방법
~~~





> **확인문제: 다음 SQL문의 빈칸에 들어갈 WHERE절의 문법으로 틀린 것을 고르세요.**

```sql
SELECT *
FROM table_name
WHERE ________;
```

보기는 아래와 같습니다.
```
1. mem_number == 4
2. mem_number >= 4
3. mem_number <= 4
4. mem_number = 4
```

```
1번입니다. 나머지는 산술연산자이다. 같다고 말하고 싶다면 '='처럼 하나를 사용해줘야한다.
```


## 2. 좀 더 깊게 알아보는 SELECT문

2. create와 insert 구문을 통해 테이블을 생성하고 데이터를 추가하는 법을 배웠습니다.

> **확인문제: 다음 표는 주요 집계함수를 정리한 것입니다. 각 설명에 해당하는 올바른 함수명을 기호에 맞게 작성하세요.**

| 함수명 | 설명 |
|--------|------|
| SUM() | 합계를 구합니다. |
| (ㄱ) | 평균을 구합니다. |
| (ㄴ) | 최소값을 구합니다. |
| MAX() | 최대값을 구합니다. |
| (ㄷ) | 행의 개수를 셉니다. |
| (ㄹ) | 행의 개수를 셉니다 (중복은 1개만 인정). |

```
여기에 답을 적어주세요!
(ㄱ) - AVG() 
(ㄴ) - MIN()
(ㄷ) - COUNT()
(ㄹ) - COUNT(DISTINCT)
```


## 3. 데이터 변경을 위한 SQL문

3. update와 delete 구문을 통해 데이터를 삭제 혹은 수정하는 법을 배웠습니다.

> **확인문제: 다음이 설명하는 SQL이 무엇인지 쓰세요.**

```
* 데이터를 삭제합니다.
* DELETE와 동일한 효과를 내지만 속도가 무척 빠릅니다.
* 삭제 후에 빈 테이블이 남아 있습니다.
```

```
TRUNCATE
```


---

# 2️⃣ 실습과제

## 1. 데이터베이스 구축

아래 코드를 MySQL Workbench에 붙여넣은 후,  
**전체 드래그 → 실행 (Ctrl + shift + Enter)** 하여 데이터베이스를 구축하세요.

```sql
-- 1. 데이터베이스 생성
CREATE DATABASE IF NOT EXISTS week2_db;

-- 2. 사용할 데이터베이스 선택
USE week2_db;

-- 4. 테이블 생성
CREATE TABLE students (
    student_id INT PRIMARY KEY,
    name VARCHAR(20),
    major VARCHAR(30),
    grade INT,
    age INT,
    gpa DECIMAL(3,2),
    admission_year INT
);

-- 5. 데이터 삽입
INSERT INTO students VALUES
(1, '진아', 'Statistics', 1, 19, 3.85, 2024),
(2, '혜인', 'Computer Science', 2, 20, 3.20, 2023),
(3, '규서', 'Business', 3, 22, 2.95, 2022),
(4, '규영', 'Statistics', 4, 23, 3.60, 2021),
(5, '철원', 'Economics', 2, 21, 3.75, 2023),
(6, '예운', 'Computer Science', 1, 19, 3.10, 2024),
(7, '민서', 'Statistics', 3, 22, 3.45, 2022);
```
## 2. 실습 문제

다음 SQL 문을 작성하고 실행 결과를 확인 후 인증 사진을 아래에 업로드하세요.

1. 모든 학생의 정보를 조회하시오.


<img width="653" height="295" alt="image" src="https://github.com/user-attachments/assets/ba28f309-0f9e-456a-95bf-d2be87e385ec" />


2. 전공이 'Statistics'인 학생을 조회하시오.


<img width="569" height="269" alt="image" src="https://github.com/user-attachments/assets/05bb3f22-cc75-4ce7-a5b4-b6b34b392ed6" />


   
3. 현재 students 테이블에 존재하는 서로 다른 전공의 개수를 구하시오.



<img width="580" height="247" alt="image" src="https://github.com/user-attachments/assets/6d8813a1-ebfe-47ed-9cd9-6f322046a88f" />



4. 나이가 20 이상이고 GPA가 3.5 이상인 학생을 조회하시오.





<img width="467" height="209" alt="image" src="https://github.com/user-attachments/assets/75252e0b-ee8d-45e2-9bd9-c205a92d8634" />






5. students 테이블에 본인의 정보를 직접 INSERT 하시오. (INSERT 실행 후, 데이터가 정상적으로 추가되었는지 확인할 수 있도록 조회 결과까지 포함하여 캡처하시오.)



<img width="627" height="312" alt="image" src="https://github.com/user-attachments/assets/0c1bb491-8aa0-43f6-97fa-c0a0f1d502ec" />




<!-- 이 부분을 지우고 인증사진을 제출해주세요.-->

### 🎉 수고하셨습니다.







