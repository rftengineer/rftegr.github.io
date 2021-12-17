# Categories
    - Suppliers
    : 인자(arguments)를 하나도 가지지 않는 Function
    - Consumer
    : 인자를 가지고, return이 없는 함수
    - Predicates
    : 값을 받아서, boolean return을 갖는 함수
    - Operators
    : 특정값을 받았을 때, 같은 타입의 값을 돌려주는 함수

    이게 왜 중요? CompletableFuture 나 기타 함수 파라미터 값으로 받는 함수들의 특징에 의해서, 어떤 메소드를 써야 하는지가 갈리기 때문에, 숙지해둬야합니다.

    - lazy evaluation : Optional -- orElseGet 확인

    - CompletableFuture
    