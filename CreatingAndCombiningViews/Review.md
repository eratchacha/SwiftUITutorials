<kbd><img width="695" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/b17473e3-1c52-4edc-a935-8564899add23"></kbd>

### protocol

- struct,enum + protocol vs class
  -  Swift는 다중 상속이 불가능하고, 오직 class만이 상속이 가능하기 때문에 protocol를 활용한다!
  -  ? : super class 와  protocol의 차이점은 무엇이 있을까 --> protocol은 여러 개 가능 & enum, struct에도 사용 가능. (이정도 뿐인건가?) --> 사실 완전히 다르지 protocol은 애초에 오버라이딩 개념이 아니지. class는 오버라이딩. 프로토콜은 어떻게 보면 클래스와 인스터스 관계처럼 프로퍼티와 클래스 관계라고 할 수 있을까 완전히 같지 않더라도?
  -  ? : 내가 이해한 바로는 상속은 수직 관계, protocol은 평행관계인데 이것이 맞나?
  -  사실 프로토콜은 근데 구현한게 아닌데 재사용성이 보장되는 것이 맞나?
  -  정확한 프로토콜의 사용 이유는 무엇일까
 
- 상속
  - https://docs.swift.org/swift-book/documentation/the-swift-programming-language/inheritance/

### App protocol

https://developer.apple.com/documentation/swiftui/app

### property

- 필드와 메소드

- stored property

- computed property

  - get - set

### 명령형 vs 선언형

### some 키워드

### Scene

### @main

### WindowGroup

- - -
<kbd>
  <img alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/ce475c37-6f65-4d14-a2f0-c36b3123dd18">
</kbd>

### modifier

- "Each modifier returns a new view, so it’s common to chain multiple modifiers, stacked vertically."

- - -
<kbd>
<img width="781" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/661314c7-a6b1-472e-a186-03e7257400fe">
</kbd>

### modifier의 작동 방식? 위의 사진에서 글씨의 색깔이 빨강이 아닌 파랑인 이유?

- - -
<kbd>
<img width="1255" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/5135c8d3-ee55-4778-8a3c-4198375cfd5b">
</kbd>

### padding 값을 설정 안해줬을 경우 디폴트값은 몇인지?

- - -
<kbd>
<img width="1275" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/2d59232f-90af-4ed5-8401-b6e8014ba6e4">
</kbd>

### clipShape()

- - -
<kbd>
<img width="946" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/7e1257b6-6dd8-4975-858d-8762da3ad970">
</kbd>

### .overlay{}

- shadow가 overlay vs Image 에 적용되는지

### .stroke()

- - - 
<kbd>
<img width="1269" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/64a56954-5694-4c26-9dc2-c6d22d5ec254">
</kbd>

<kbd>
<img width="859" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/a427b63b-c35b-413e-b86d-837312b6a67a">
</kbd>

### padding의 존재 유뮤에 따라 달라진 차이점

- - -
<kbd>
<img width="1282" alt="image" src="https://github.com/eratchacha/SwiftUITutorials/assets/58865827/d0fdb845-6771-497f-9093-c23178b62268">
</kbd>

### Divider()

- - -
