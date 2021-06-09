# DB란(data bass) 

몇 개의 자료 파일을 조직적으로 통합하여 자료 항목의 중복을 없애고 자료를 구조화하여 기억시켜 놓은 자료의 집합체



# data bass 용어

![DataBase ](https://t1.daumcdn.net/cfile/tistory/993845445A67253915)

### 식별자(**identifier**) 

**식별자의 뜻 :** 여러개의 집합체를 담고있는 관계형 데이터베이스에서 각각의 구분할 수 있는 논리적인 개념

**식별자의 특성**

유일성 : 하나의 릴레이션에서 모든 행은 서로 다른 키 값을 가져야 합니다.

최소성 : 꼭 필요한 최소한의 속성들로만 키를 구성해야 합니다.



### 튜플(Tuple)

**튜플:** 데이터 베이스의 행을 의미하고 튜플의 수는 카디날리티(Cardinality)라고한다.



### 어트리뷰트(Attribute)

**어트리뷰트: **테이블에서 열을 의미하고 어트리뷰트(Attribute)의 수를 의미하는 단어는 디그리(Degree)라고 라고한다.



# DBMS 

: 사용자-데이터베이스 간 인터페이스 역할(중간역할)

-필수 기능: DB내용에 대한 정의기능, 조작기능, 제어기능 

-장단점: 데이터의 중복성 & 종속성 최소화; 일괄성 & 무결성 유지;

사용자 간 데이터 공유 가능 



# SQL 

- 데이터베이스에서 데이터를 정의,조작,제어하기 위해 사용하는 언어

  ### DDL(Data Definision Language,

  ### 데이터 정의 언어) 

  DDL:  데이터베이스의 구조를 정의,수정,삭제 등 위해 사용되는 언어 (CREATE, ALTER, DROP)

  

  ### DML(Data Manipulation Language, 데이터 조작 언어)

  DML: 데이터베이스 내의 자료 검색, 삽입, 갱신,삭제 위해 사용되는 언어 (SELECT,DELETE,INSERT,UPDATE)

  

  ### DCL(Data Control Language, 데이터 제어 언어)

  DCL: 데이터베이스 데이터의 대해 무결성 유지, 병행 수행 제어, 보호관리(COMMIT,ROLLBACK,GRANT,REVOKE)