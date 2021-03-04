# Modifier



### 제어자(Modifier)

> 클래스, 변수 또는 메서드의 선언부에 함께 사용되어 부가적인 의미를 부여



### 접근 제어자(Access Modifier)

> 클래스, 메서드, 멤버변수, 생성자에 사용되어,  외부에서 접근하지 못하도록 제한

* public

  > 접근 제한이 전혀 없음

* protected

  > 같은 패키지 내에서,  다른 패키지의 자식 클래스에서 접근이 가능

* default

  > 같은 패키지 내에서만 접근이 가능
  >
  > 접근 제어자가 지정되어 있지 않다면 default를 의미

* private

  > 같은 클래스 내에서만 접근이 가능

|   대상   |        사용 가능한 접근 제어자        |
| :------: | :-----------------------------------: |
|  클래스  |           public, (default)           |
|  메서드  | public, protected, (default), private |
| 멤버변수 | public, protected, (default), private |
| 지역변수 |                 없음                  |

