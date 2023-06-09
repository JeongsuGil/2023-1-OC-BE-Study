1. 의존과 의존성
    - 간단하게 말하면 코드에서 두 모듈간의 연결
    - 대표적으로 A 클래스의 메소드에서 매개변수를 다른 B 클래스의 타입으로 받아 B 객체의 메서드를 사용할때, A 클래스는 B 클래스와 의존한다고 보면 된다.
    
2. @Autowired 의존성 주입
    - Spring은 @Autowired 어노테이션을 이용한 다양한 의존성 주입(DI; Dependency Injection) 방법을 제공한다.
    - 의존성 주입은 필요한 객체를 직접 생성하는 것이 아닌 외부로부터 객체를 받아 사용하는 것으로, 이를 통해 객체간의 결합도를 줄이고 코드의 재활용성을 높일 수 있다.
    - @Autowired 는 Spring에게 의존성을 주입하는 지시자 역할로 쓰입니다.
3. DIP
    - 간단하게 말하면 의존 관계를 맺을 때 변화하기 쉬운 것 또는 자주 변화하는 것에 의존하기 보다는, 변화하기 어려운것, 거의 변화가 없는 것에 의존하라는 원칙
    
4. 스프링 빈과 스프링 컨테이너란?
    - 스프링 컨테이너 : 스프링에서 자바 객체들을 관리하는 공간, 자바 객체를 스프링에선 빈(Bean)이라고 하는데 스프링 컨테이너에서는 이 빈의 생성부터 소멸까지를 개발자 대신 관리해주는 곳이라고 할 수 있다.
    - 스프링 빈 : 스프링은 보통의 경우 스프링 컨테이너에 빈 인스턴스를 단 한개만 저장하는 싱글톤 방식을 채택하고 있다. 빈 이름은 항상 다르게 지정이 되어야 한다. 예상치 못한 여러 오류가 발생하는데, 이를 개발 중 발견하기 매우 어렵기 때문
    
5. JDBC와 JPA
    - JDBC : DB에 접근(Connectivity)할 수 있도록 Java에서 제공하는 API, 모든 Java Data Access 기술의 근간으로 모든 Persistence Framework는 내부적으로 JDBC API를 사용한다.
    - JPA : 자바 ORM 기술에 대한 API 표준 명세로, Java에서 제공하는 API
