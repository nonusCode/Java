# Polymorphism



### 오버로딩(Overloading)

> 한 클래스 내에 같은 이름의 메서드를 여러개 정의

* 조건

  > 메서드의 이름이 같아야 함
  >
  > 매개변수의 개수 또는 타입이 달라야함

* 접근 제어자

  > 자유롭게 지정 가능



### 오버라이딩(Overriding)

> 부모 클래스로부터 상속받은 메서드를 자식 클래스에서 재정의

* 조건

  > 메서드의 이름이 같아야 함
  >
  > 매개변수가 같아야 함
  >
  > 반환타입이 같아야 함

* 접근 제어자

  > 부모 클래스의 메서드보다 더 좁게 설정할 수 없음
  >
  > 예외는 부모 클래스의 메서드보다 많이 선언할 수 없음
  >
  > static메서드를 인스턴스메서드로 또는 그 반대로 바꿀 수 없음