# 여러 데이터 접근 기술로 학습용 게시판 만들기

SQLMapper  
-JdbcTemplate  
-MyBatis  

ORM 관련 기술  
-JPA, Hibernate  
-스프링 데이터 JPA  
-Querydsl  

Project  
-Development Tools: IntelliJ IDEA ULTIMATE  
-Project: Gradle Project  
-Language: Java  
-Spring Boot: 2.7  
-Packaging: Jar  
-Java: 11  

SQL Mapper 주요 기능  
SQL만 작성하면 해당 SQL 결과를 객체로 매핑해준다. JCBC를 직접 사용할 때 발생하는 여러 중복을 제거해준다.

ORM 주요 기능  
JPA를 사용하면 기본적인 SQL은 JPA가 대신 작성하고 처리해준다. 개발자는 저장하고 싶은 객체를 마치 자바 컬렉션에 저장하고 조회하듯 사용하면 ORM 기술이 DB에 해당 객체를 저장하고 조회해준다.  
스프링 데이터 JPA, Querydsl은 JPA를 더 편리하게 사용할 수 있게 도와준다.  

