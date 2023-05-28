# DDL

Data Definition Language

데이터 정의어 - DB를 정의하는 언어

<aside>
✨ SQL문의 종류 중 하나!

</aside>

- 추가 설명
  **DB에서는** 모든 작업을 **SQL문을 이용해 작업**한다
  SQL문은 다루는 객체나 **용도에 따라 나눌 수 있다**
  DDL, DML, DCL이 있다

DDL

**DB와 테이블을 생성, 변경, 제거**

데이터를 생성하거나 수정, 삭제 등 데이터의 **전체 골격을 결정**하는 역할의 언어

스키마, 도메인, 테이블, 뷰, 인덱스 등이 있다

명령어를 입력하는 순간 작업이 즉시 완료(auto commit)되기 때문에 조심해야 한다

| create   | 대상 객체를 생성                                        |
| -------- | ------------------------------------------------------- |
| alter    | 대상 객체의 구조 변경(수정)                             |
| drop     | 대상 객체와 객체 내부 데이터를                          |
| 삭제한다 |
| truncate | 공간을 포함한 모든 레코드를 삭제한다 (테이블 초기화 등) |
| rename   | 대상 객체 이름을 변경한다                               |

[코드](%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B3%20d552f6edefe94180b0be9afb3018e0b2.md)