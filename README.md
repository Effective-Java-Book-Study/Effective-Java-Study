# Effective-Java-Study

## 스터디 규칙
- 스터디는 매주 목요일 오후 9시에 진행됩니다.
- Wiki에 명시된 컨벤션 타입을 확인하고 준수해야 합니다.
- 원본 저장소를 Fork하여 로컬 환경에서 작업합니다.
- 작업 완료 후 원격 저장소에 PR(Pull Request)을 요청합니다.
- 각 학습 아이템마다 개별 이슈를 생성합니다.
- 생성된 이슈는 추후 PR과 연동합니다.
- 스터디 당일에 자신이 작성한 예제 코드를 기반으로 설명을 진행합니다.
- Discussion을 통해 각 아이템별로 질의응답 시간을 가집니다.

## 참고 링크
- [책 정보](https://m.yes24.com/Goods/Detail/65551284)
- [이펙티브 자바 영문판 Github](https://github.com/jbloch/effective-java-3e-source-code)
- [이펙티브 자바 한글판 Github](https://github.com/WegraLee/effective-java-3e-source-code)

## 2장. 객체 생성과 파괴
| 아이템 | 담당자 | 링크 |
|:---:|:---:|:---:|
|아이템 1. 생성자 대신 정적 팩터리 메서드를 고려하라|[정다은](https://github.com/takemetoneverland)| |
|아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라|[정다은](https://github.com/takemetoneverland)| |
|아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라|[정다은](https://github.com/takemetoneverland)| |
|아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라|[정다은](https://github.com/takemetoneverland)| |
|아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라|[장우진](https://github.com/dnwls16071)||
|아이템 6. 불필요한 객체 생성을 피하라|[장우진](https://github.com/dnwls16071)||
|아이템 7. 다 쓴 객체 참조를 해제하라|[장우진](https://github.com/dnwls16071)||
|아이템 8. finalizer와 cleaner 사용을 피하라|[장우진](https://github.com/dnwls16071)||
|아이템 9. try-finally보다는 try-with-resources를 사용하라|[장우진](https://github.com/dnwls16071)||

## 3장. 모든 객체의 공통 메서드
| 아이템 | 담당자 | 링크 |
|:---:|:---:|:---:|
|아이템 10. equals는 일반 규약을 지켜 재정의하라|[정다은](https://github.com/takemetoneverland)||
|아이템 11. equals를 재정의하려거든 hashCode도 재정의하라|[정다은](https://github.com/takemetoneverland)||
|아이템 12. toString을 항상 재정의하라|[정다은](https://github.com/takemetoneverland)||
|아이템 13. clone 재정의는 주의해서 진행하라|[정다은](https://github.com/takemetoneverland)||
|아이템 14. Comparable을 구현할지 고려하라|[정다은](https://github.com/takemetoneverland)||

## 4장. 클래스와 인터페이스
| 아이템 | 담당자 | 링크 |
|:---:|:---:|:---:|
|아이템 15. 클래스와 멤버의 접근 권한을 최소화하라|[장우진](https://github.com/dnwls16071)||
|아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라|[장우진](https://github.com/dnwls16071)||
|아이템 17. 변경 가능성을 최소화하라|[장우진](https://github.com/dnwls16071)||
|아이템 18. 상속보다는 컴포지션을 사용하라|[장우진](https://github.com/dnwls16071)||
|아이템 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라|[장우진](https://github.com/dnwls16071)||
|아이템 20. 추상 클래스보다는 인터페이스를 우선하라|||
|아이템 21. 인터페이스는 구현하는 쪽을 생각해 설계하라|||
|아이템 22. 인터페이스는 타입을 정의하는 용도로만 사용하라|||
|아이템 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라|||
|아이템 24. 멤버 클래스는 되도록 static으로 만들라|||
|아이템 25. 톱레벨 클래스는 한 파일에 하나만 담으라|||
