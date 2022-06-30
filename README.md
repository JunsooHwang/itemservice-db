# 여러 데이터 접근 기술로 학습용 게시판 만들기

SQLMapper  
- JdbcTemplate  
- MyBatis  

ORM 관련 기술  
- JPA, Hibernate  
- 스프링 데이터 JPA  
- Querydsl  

Project  
- Development Tools: IntelliJ IDEA ULTIMATE  
- Project: Gradle Project  
- Language: Java  
- Packaging: Jar  


SQL Mapper 주요 기능  
SQL만 작성하면 해당 SQL 결과를 객체로 매핑해준다. JCBC를 직접 사용할 때 발생하는 여러 중복을 제거해준다.

ORM 주요 기능  
JPA를 사용하면 기본적인 SQL은 JPA가 대신 작성하고 처리해준다. 개발자는 저장하고 싶은 객체를 마치 자바 컬렉션에 저장하고 조회하듯 사용하면 ORM 기술이 DB에 해당 객체를 저장하고 조회해준다.  
스프링 데이터 JPA, Querydsl은 JPA를 더 편리하게 사용할 수 있게 도와준다.  

여기서 사용하는 데이터 저장 기술들의 내용이 몹시 방대하여 인프런 김영한 선생님의 강좌인 [스프링 MVC 1편 - 백엔드 웹 개발 핵심 기술], [스프링 DB 2편 - 데이터 접근 활용 기술]을 통해 각 기술들의 핵심 기능 위주로 학습하였습니다.


프로젝트 학습 목표
- 데이터 접근 기술에 대한 기본 이해와 전체적인 큰 그림  
- 각 기술들의 핵심 기능
