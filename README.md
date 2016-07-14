# CodeWebProject

1. 서비스 레이어 추가
        - 서비스 계층은 고객마다 다른 부분을 처리할 수 있는
        완충장치 역할을 한다.
        - 각 회사마다 다른 로직이나 규칙을 DB에 무관하게
        처리할 수 있는 완충영역으로 존재할 필요가 있다.
        - 컨트롤러와 같은 외부 호출이 영속계층에 종속적인
        상황을 막아준다.
        - 만일 컨트롤러가 직접 영속계층의 DB를 이용하게 되면
        트랜젝션의 처리나 예외의 처리 등 모든 로직이 
        컨트롤러로 집중된다. 서비스 계층은 컨트롤러로 하여금
        처리해야 하는 일을 분업하게 만들어준다.
