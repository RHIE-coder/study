# OOP의 역할

1. 실력 없는 프로그래머가 코드를 망가뜨리지 못하게 함(캡슐화-인터페이스 제공)
2. 코드에 대한 책임을 명확히 함

 - 함수는 매개변수의 순서에 대해서 사람마다 생각이 다르고 같은 자료형에 대하여 다른 성격의 값이 들어가면 디버깅하기 힘든 실수가 나올 수 있음.
 - 함수 시그니쳐를 고침에 따라 에러 발생
 - 필요한 문맥(context)마다 맞는 클래스를 여러 객체로 만들어서 사용(쓸데 없이 생성하는 것 같고 귀찮아지지만, 코드 사용자에 대한 실수가 현저히 떨어질 수 있음 - 개발 의도 반영)
 - `int`하나까지 클래스로... 제품의 성능까지 줄여야 하나? 강하게 코드를 망가뜨리지 않게하는 장치. 
 - 두 마리 토끼를 잡아라 java보단 C#?? -> C#에는 구조체 존재 --> not heap allocation -> stack allocation(객체를 스택에??)
 - 함수 시그니처를 잘 설계하자
