# RESTful이란 무엇이며, 이것에 대해서 아는대로 설명해보세요.

`토르`

REST+ful은 Representational State Transfer에서 나온 말로 컴퓨터 시스템간의 상호운영성을 제공하는 방법 중 하나입니다. 

REST의 조건을 지키기 위해서는
- client-server
- stateless
- cache
- uniform interface
- layered system
- code-on-demand

가 필요한데 http를 사용하면서 `uniform interface`를 제외한 대부분의 제약조건을 지키고 있습니다. 

`uniform interface`의 세부 제약 조건은 

- identification of resources
- manipulation of resources through representations
- self-descriptve messages
- hypermedia as the engine of application state (HATEOAS)

처음 두 개는 잘 지켜집니다. URI를 만들 때 리소스가 URI에서 식별되고, http 메서드를 통해서 행위를 나타내기 떄문입니다. 

`self-descriptive message`: 메시지는 스스로 설명할 수 있어야 합니다. 메시지 내용만으로 온전히 해석할 수 있어야 합니다. 
`HATEOAS`: 애플리케이션의 상태는 Hyperlink를 이용해 전이되어야 합니다. 




## 참고 자료
- https://velog.io/@injoon2019/CS-REST-API
