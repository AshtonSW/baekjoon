# 자바 풀이를 도와주세요!

## 설명

 저는 C++을 위주로 코딩테스트를 준비하고 있습니다. JAVA 정답 코드에 올라갈 코드는 정말 최적의 코드가 필요한 것은 아닙니다만, 제가 풀이를 작성하기에는 JAVA에 대해 미흡한 부분이 있어 도움을 요청드립니다.

단원의 Directory에 들어가보면 cpp과 java directory가 있습니다. 해당 directory에 문제에 맞는 java 파일이 존재하고, 해당 파일에 코드를 작성하여 pull request를 main 으로 보내주세요!

## 규칙

### 일반 

- 반드시 본인의 코드를 PR합니다.
- 구현한 사람 정보는 본인의 이름, 백준 닉네임만 허용합니다. 또한 제출 정보도 보내주셔야합니다.
- Allow edits by maintainers 옵션을 허용해주셔야 합니다.
- 한 번의 PR은 반드시 한 코드만 PR 해야합니다. 각 문제에 대해 branch를 반드시 따로 두어 여러 개의 PR을 보내주세요.
- Problem1078.java는 반드시 해당 단원의 풀이 방식이 적용되어야 합니다. -> BFS 수업이었다면, BFS 풀이로
- 이미 다른 사람이 코드를 작성한 경우 기존의 풀이와 다른 알고리즘이나 자료구조를 사용한 경우(풀이의 방향이 다른)에만 PR 해주시면 감사하겠습니다. 이의 경우 Problem1078_2.java와 같은 방식으로 지정해주세요.

### 코딩 컨벤션


- 입력은 BufferedReader, 출력은 BufferWriter 또는 StringBuilder를 사용하는 것을 원칙으로 합니다.
- Scanner 및 System.out.println은 성능 이슈로 사용을 금지합니다.
- 클래스명은 Main으로 합니다.
- 패키지는 사용하지 않습니다.
- 모든 import는 자동 정리하고, 불필요한 import는 포함하지 않습니다.
- class, method, variable 이름은 JAVA 표준에 따라 camelCase로 작성해주세요.
-> 클래스명은 PascalCase
-> 메서드, 변수명은 camelCase
- 반드시 필요한 경우가 아니면 float, double 대신 int, long 등 정수형을 사용해주세요.
- 동적 배열 등은 JAVA의 ArrayList, HashMap, Queue 등 표준 라이브러리 (java.util.*) 를 적극 활용해주세요.
- 중괄호 {}는 항상 사용하는 것을 기본으로 합니다.(K&R 스타일 권장)
- 한 파일 안에 여러 클래스는 금지합니다.
- 자주 쓰는 로직은 메서드로 분리하여 가독성과 재사용성을 높이세요.