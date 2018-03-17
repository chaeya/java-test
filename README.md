## Description

이 프로젝트는 java 소스코드에 test case 가 포함된 간단한 예제입니다.
자동화 빌드를 교육하는 도구에 사용할 수 있습니다.

## example code

In the code that's included in this project, you'll see an example of a collaborator test (for `FeedsWalrus`), and two regression tests (for `OpensCan`
and `Walrus`). They serve as examples of using JUnit, Hamcrest, and Mockito.

```
.
├── README.md
├── pom.xml
├── src
│   ├── main
│   │   └── java
│   │       └── example
│   │           ├── FeedsWalrus.java
│   │           ├── OpensCan.java
│   │           └── values
│   │               ├── CannedWalrusFood.java
│   │               ├── Walrus.java
│   │               └── WalrusFood.java
│   └── test
│       └── java
│           └── example
│               ├── FeedsWalrusTest.java
│               ├── OpensCanTest.java
│               └── values
│                   └── WalrusTest.java
```
