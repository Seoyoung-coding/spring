## @RestController
@RestController = @Controller + @ResponseBody

1) @Controller는 Spring MVC의 기본 컨트롤러 어노테이션으로 주로 웹 애플리케이션에서 HTTP 요청을 처리하는 역할
              클래스에서 사용되며 해당 클래스를 웹 요청을 처리하는 컨트롤러로 등록
              
2) @RestController는 RESTful 웹 서비스를 쉽게 만들 수 있도록 돕는다
                    클래스가 HTTP 요청을 처리하고 데이터를 JSON이나 XMl 형태로 클라이언트에게 직접 반환함

```

```

## API 설계 규칙 
URL 에는 소문자 사용 / 하이픈(-) 가능 / 언더바(_) 불가능 / 파일 확장자를 표현 하지 않는다

