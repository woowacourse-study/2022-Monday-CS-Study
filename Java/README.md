## Java, JVM, Spring

1. [JVM의 구조와 Java의 실행방식을 설명해주세요.](1.md)
2. [GC가 무엇인지, 필요한 이유는 무엇인지, 동작방식에 대해 설명해주세요.](2.md)
3. 컬렉션 프레임워크에 대해서 설명해주세요.
4. 제네릭에 대해서 설명해주세요.
5. 애노테이션에 대해서 설명해주세요.
6. [오버라이딩과 오버로딩이 무엇이며 어떤 차이가 있을까요?](6.md)
7. 인터페이스와 추상클래스의 차이점에 대해 설명해주세요.
8. 클래스는 무엇이고 객체는 무엇인가요?
9. 정적(static)이란 무엇인가요?
10. 자바의 원시타입들은 무엇이 있으며 각각 몇 바이트를 차지하나요?
11. 접근 제어자의 종류와 이에 대해 설명해주세요.
12. 객체지향에 대해서 설명해주세요.
13. [SOLID(객체지향 5대원칙)에 대해서 설명해주세요.](13.md)
14. [동일성(identity)와 동등성(equality)에 대해 설명해주세요. (equals(), ==)](14.md)
15. 원시타입과 참조타입의 차이에 대해 설명해주세요.
16. [String, StringBuilder, StringBuffer 각각의 차이에 대해 설명해주세요.](16.md)
17. [Checked Exception과 Unchecked Exception에 대해 설명해주세요. 스프링 트랜잭션 추상화에서 rollback 대상은 무엇일까요?](17.md)
18. Java8에서 추가된 기능에 대해서 설명해주세요.
19. try-with-resource에 대해서 설명해주세요.
20. 강한 결합과 느슨한 결합이 무엇인지 설명해주세요.
21. 직렬화와 역직렬화에 대해서 설명해주세요.
22. 자바의 동시성 이슈(공유자원 접근)에 대해 설명해주세요.
23. Mutable 객체와 Immutable 객체의 차이점에 대해 설명해주세요.
24. 자바에서 null을 안전하게 다루는 방법에 대해 설명해주세요.
25. JVM 에서의 autoboxing 이란 어떤 현상을 말하는 걸까요?
26. interface default implementation 이란? abstract class 를 상속받는 것과 기본 구현을 들고 있는 interface 를 implements 하는것은 어떤 차이가 있나요?
27. Java stream method 중 map 과 flatMap 의 차이에 대해 설명해주세요.
28. 메소드에서 리스트 타입의 파라미터를 받을 때, ArrayList - List - Collection - Iterable 처럼 구체 타입 뿐 아니라 상위 타입도 받을 수 있습니다. 컬렉션을 받는 어떤 API 를 구현하실 때 구체 타입의 API 디자인을 선호하는지, 추상 타입의 API 디자인을 선호하는지를 설명해 주세요. 왜 그런 선택을 하시나요?
29. [Java 의 equals 와 == 의 차이에 대해 설명해주세요. Kotlin 의 == 와 === 는 어떤 차이가 있나요?](14.md)
30. 스프링의 @Autowired 를 가급적 쓰지 말라는 이야기가 종종 들리는데 원인이 뭘까요?
31. final 키워드를 변수, 메소드, 클래스에 선언하는 것은 어떤 의미가 있습니까?
32. synchronized 를 메소드에 선언하는 것과, 특정 객체에 선언하는 것은 어떤 차이가 있습니까?
33. Reflection 을 유용하게 사용하는 사례를 말씀해 주세요.
34. JDK/JVM 은 대표적으로 OpenJDK 와 Oracle JDK 로 나뉘는데요, 업무에 어떤 JDK 를 사용하시겠습니까? 선택의 이유를 말씀해 주세요.
35. hashCode / equals 메소드의 역할에 대해 아시는 내용을 최대한 설명해주세요.
36. [Java 의 Collections.unmodifiableList 같은 API 를 이용해 List 같은 collection 을 변경 불가능하게 만들 수 있습니다. 그렇다면 이 API 를 사용하면 immutability 를 달성할 수 있을까요?](36.md)
37. 다음 싱글턴 코드의 어떤 점을 개선하실 수 있습니까? (개선이 필요 없을 수도 있음 / 왜?)
    ```java
    class MySingleton {
        private static MySingleton instance;

        public static synchronized MySingleton getInstance() {
            if (instance == null) {
                instance = new MySingleton();
            }
            return instance;
        }
    }
    ```
38. java 9 이상에 도입된 추가 기능들 중 마음에 드는거 아무거나 하나만 설명해주세요.
39. 민감한 정보를 String 으로 저장하는 것과, char[] 또는 StringBuilder/StringBuffer 같은 클래스로 저장하는 것은 어떤 차이가 있나요?
40. 크기를 지정하지 않고 ArrayList 를 new 로 생성하면 크기 10의 ArrayList 가 생성됩니다. Array 는 크기를 넘길 수 없는데 반해 ArrayList 는 꽉 찬 List 에 element 를 추가로 더할 수 있습니다. 그렇다면 10개의 element 를 채워넣은 ArrayList 의 11번째 element 을 add 하기위해 어떤 일이 일어나는지 설명해주세요.
41. java.lang.String 의 hashCode 구현에 대해 고찰해 봅시다. 왜 그런 구현일지, 문제점은 없을지 이야기해주세요.
42. lambda 와 메소드 1개만 있는 익명 클래스 직접 선언은 문법적 차이 외에 어떤 내부적인 차이가 있을까요?
43. [Java generics 에는 primitive type 을 쓸 수 없는 문제가 있습니다. 왜 그럴까요? 어떻게 해결할 수 있을까요?](43.md)
44. I/O 를 Java nio 로 코딩할 때 주의점은 어떤게 있을까요?
45. Java 는 Pure OOP 언어가 아니라고 하는데, 왜 그런 걸까요?
46. java.lang.String 의 length 메소드는 정확한 결과를 반환하지 않는 경우가 종종 있습니다. 정확한 의 의미란 무엇이고, 왜 그럴까요?
47. Maven 이나 Gradle 이, 의존성 선언한 artifact 들을 찾는 과정에 대해 설명해주세요.
48. java.util.Property extends Hashtable, java.util.Stack extends Vector 같은 클래스는 상속으로 망한 대표 사례입니다. 이유를 설명해 주세요.
49. Spring boot 가 stereotype annotation 을 붙인 클래스들을 어떻게 찾고 bean 으로 등록하는지 그 과정을 최대한 상세하게 설명해주세요.
50. [Spring 은 @Transactional 어노테이션 붙인 메소드를 어떻게 찾고 트랜잭션을 처리하나요? 그 내부 구현을 상세하게 설명해 주세요.](50.md)
51. 메소드에 @Transactional 을 붙이는 것과, TransactionTemplate 을 사용해 트랜잭션을 직접 제어하는 것에는 어떤 차이가 있나요? 어떤 방식을 더 선호하시는지 그 이유도 함께 설명해 주시기 바랍니다.
52. Spring DI/IoC는 어떻게 동작하나요? 
53. Spring Bean이란 무엇인가요? 
54. 스프링 Bean의 생성 과정을 설명해주세요. 
55. 스프링 Bean의 Scope에 대해서 설명해주세요. 
56. IoC 컨테이너의 역할은 무엇이 있을까요? 
57. DI 종류는 어떤것이 있고, 이들의 차이는 무엇인가요? 
58. Autowiring 과정에 대해서 설명해주세요. 
59. [Spring Web MVC의 Dispatcher Servlet의 동작 원리에 대해서 간단히 설명해주세요.](59.md)
60. 프론트 컨트롤러 패턴이란 무엇인가요? 
61. Servlet Filter와 Spring Interceptor의 차이는 무엇인가요? 
62. Spring에서 CORS 에러를 해결하기 위한 방법을 설명해주세요. 
63. Bean/Component 어노테이션에 대해서 설명해주시고, 둘의 차이점에 대해 설명해주세요. 
64. POJO란 무엇인가요? Spring Framework에서 POJO는 무엇이 될 수 있을까요? 
65. [Spring Web MVC에서 요청 마다 Thread가 생성되어 Controller를 통해 요청을 수행할텐데, 어떻게 1개의 Controller만 생성될 수 있을까요?](65.md) 
66. Filter는 Servlet의 스펙이고, Interceptor는 Spring MVC의 스펙입니다. Spring Application에서 Filter와 Interceptor를 통해 예외를 처리할 경우 어떻게 해야 할까요? 
67. Spring Application을 구동할 때 메서드를 실행시키는 방법에 대해 설명해주세요. 
68. 의존성과 설정값을 생성자 인자로 주입해야 하는 이유에 대해 설명해주세요.
69. [톰캣의 NIO Connector의 동작 방식에 대해 설명해주세요.](69.md)
