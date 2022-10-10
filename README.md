# JDBC 라이브러리 구현하기

## 🚀 1단계 - JDBC 라이브러리 구현하기

 * [x] UserDaoTest의 모든 테스트 케이스가 통과한다.
 * [x] UserDao가 아닌 JdbcTemplate 클래스에서 JDBC와 관련된 처리를 담당하고 있다.

## 🚀 2단계 - 리팩터링 힌트

### 미션 설명
자바가 제공하는 기능을 극한으로 활용해 클린 코드를 작성하는 연습을 한다.

 * [x] 익명 클래스
 * [x] 함수형 인터페이스
 * [x] 제네릭
 * [x] 가변 인자
 * [x] 람다
 * [x] try-with-resources
 * [x] checked vs unchecked exception

## 🚀 3단계 - Transaction 적용하기

 * [x] 트랜잭션 롤백이 적용되어 UserServiceTest 클래스의 testTransactionRollback() 테스트 케이스가 통과한다.
 * [x] 트랜잭션 서비스와 애플리케이션 서비스가 분리되었다.
