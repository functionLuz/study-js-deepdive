[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fgather-around-and-code%2Fstudy-js-deepdive&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

# study-deepdive-js

Javascript Deep Dive와 MDN문서를 토대로 자바스크립트 개념을 공부하는 스터디 기록입니다.

<br>

## 📋 Study Approach

1. 참여 인원은 각자 해당 챕터를 정리한 내용을 마크다운 파일로 작성하여 GitHub에 업로드합니다.
2. 발표는 각자가 작성한 내용을 기반으로 진행합니다.
3. 주차별 발표자는 랜덤으로 정합니다.
4. 각자 챕터와 관련된 질문 갯수를 2개씩 정한 후, 그 내용을 meeting 당일 13:00까지 q&a.md 파일에 추가합니다.
5. 폴더 및 구조

```bash
.
├── [Number] Chapter Title
├── 04_변수
│   ├── userName.md # userName으로 파일을 명명합니다.
│   └── q&a.md # 챕터와 관련된 질문 목록
├── 05_표현식과 문
├── 06_데이터 타입
├── 07_연산자
├── 08_제어문
├── 09_타입변환과 단축평가
├── 10_객체 리터럴
├── 11_원시값과 객체의 비교
├── 12_함수
├── 13_스코프
├── 14_전역변수의 문제점
├── 15_let,cosnt 키워드와 블록레벨 스코프
├── ...
├── Projects # 토이 프로젝트
│   └── [Number]_Assignment
│   └── 01_Assignment # 차시별 같이 고민해본 과제
│       ├── b
│       │   └── ex_assignment_finished.html # 완성 시 `_finished`
│       └── ex_assignment.html # 과제 예시 코드
└── public # 이미지
```

<br>

## 🤔 Pull Request와 Commit Convention

한글 커밋 메시지를 사용하고 커밋의 의도를 나타내기 위해 적절한 접두사를 사용하여 Commit Convention을 준수합니다.

```bash
# 개인의 이름을 사용하여 새로운 브랜치를 생성합니다
git branch user-b

# 새로 생성된 브랜치로 이동합니다
git checkout user-b

# 적절한 커밋 메시지로 변경 사항을 커밋합니다
git commit -m "create: #1 4장 변수"

# 브랜치를 원격 저장소로 푸시합니다
git push origin user-b

# 메인 브랜치로 전환합니다
git checkout master

# user-b 브랜치를 master 브랜치로 병합합니다
git merge user-b

```

**Commit Convention**:

- 커밋 메시지는 한글로 작성합니다.
- 커밋 메시지는 챕터명을 기준으로 작성합니다 (예: "4장 변수").
- 다음과 같은 접두사를 사용하여 커밋의 의도를 표시합니다:
  - `create`: 새로운 내용을 추가하는 경우
  - `update`: 기존 내용을 수정하는 경우
  - `delete`: 기존 내용을 삭제하는 경우
  - `docs`: README.md 파일을 수정하는 경우
  - `chore`: 기타 작업 및 변경 사항
  - `fix`: 버그 수정
  - `chore`: 일반적인 유지보수 또는 도구 변경
  - `test`: 테스트 추가 또는 수정
  - `refactor`: 동작을 변경하지 않고 코드 재구성
  - `style`: 코드 스타일 변경 (공백, 형식 등)

```
feat: 사용자 인증 기능 추가
fix: 데이터 처리 중 발생한 널 포인터 예외 수정
docs: 설치 안내서에 README 업데이트
```

<br>

## ✨ Meeting

- ~월요일과 목요일: 23:00~24:30 (1시간 30분)~

<br>

## 🔖 Content

|     | 날짜           | 챕터                   | 발표자            | 불참자 | Q&A                                                                          |
| --- | -------------- | ---------------------- | ----------------- | ------ | ---------------------------------------------------------------------------- |
| 1   | 2023-05-25(목) | 4장,5장                | b(4), jamie(5)    |        | [#34](https://github.com/gather-around-and-code/study-js-deepdive/issues/34) |
| 2   | 2023-05-29(월) | 6장,7장                | choi(6), jamie(7) |        |                                                                              |
| 3   | 2023-06-01(목) | 8장,9장                | b(8), jamie(9)    |        |                                                                              |
| 4   | 2023-06-05(월) | 10장,11장              | b(10), jamie(11)  |        |                                                                              |
| 5   | 2023-06-08(목) | 12장                   | choi              | b      |                                                                              |
| 6   | 2023-06-12(월) | 13장,23장              | b(13), jamie(23)  |        |                                                                              |
| 7   | 2023-06-15(목) | 14장,15장              | choi(14), b(15)   | jamie  |                                                                              |
| 8   | 2023-06-19(월) | 16장,17장              | b, jamie          | choi   |                                                                              |
| 9   | 2023-06-22(목) | 18장                   | choi              |        |                                                                              |
| 10  | 2023-06-26(월) | 19장                   | b, jamie, choi    |        |                                                                              |
| 11  | 2023-06-29(목) | 20장,21장,22장         | b, jamie, choi    |        |                                                                              |
| 12  | 2023-07-03(월) | 24장                   |                   |        |                                                                              |
| 13  | 2023-07-06(목) | 25장                   |                   |        |                                                                              |
| 14  | 2023-07-10(월) | 26장                   |                   |        |                                                                              |
| 15  | 2023-07-13(목) | 27장                   |                   |        |                                                                              |
| 16  | 2023-07-17(월) | 28장, 29장, 30장, 31장 |                   |        |                                                                              |
| 17  | 2023-07-20(목) | 32장,33장              |                   |        |                                                                              |
| 18  | 2023-07-25(월) | 38장                   |                   |        |                                                                              |
| 19  | 2023-07-27(목) | 39장                   |                   |        |                                                                              |
| 20  | 2023-07-31(월) | 34장, 35장, 36장       |                   |        |                                                                              |
| 21  | 2023-08-03(목) | 37장, 42장             |                   |        |                                                                              |
| 22  | 2023-08-07(월) | 40장                   |                   |        |                                                                              |
| 23  | 2023-08-10(목) | 41장, 43장             |                   |        |                                                                              |
| 24  | 2023-08-14(월) | 45장                   |                   |        |                                                                              |
| 25  | 2023-08-17(목) | 46장                   |                   |        |                                                                              |
| 26  | 2023-08-21(월) | 47장, 48장             |                   |        |                                                                              |

<br>

## Toy Project 목록

|     |                                            Toy Project                                             | 경로 |
| :-: | :------------------------------------------------------------------------------------------------: | :--: |
|  1  | [Fetching data: 상품 리스트](https://github.com/gather-around-and-code/study-js-deepdive/issues/3) |      |
|  2  |           [차트](https://github.com/gather-around-and-code/study-js-deepdive/issues/13)            |      |
|  3  |          [계산기](https://github.com/gather-around-and-code/study-js-deepdive/issues/30)           |      |
|  4  |        [To do List](https://github.com/gather-around-and-code/study-js-deepdive/issues/31)         |      |
|  5  |         [SoundBook](https://github.com/gather-around-and-code/study-js-deepdive/issues/47)         |      |
|  6  |                                                                                                    |      |

```bash

└── Projects
    ├── 01_fetcing_data
    │   ├── b
    │   ├── jy
    │   └── README.md
    ├── 02_chart
    ├── 03_calculator
    ├── 04_todo_list
    └── ...
```

<br>

## 📚 Reference

- [Javascript Deep Dive](https://book.naver.com/bookdb/book_detail.nhn?bid=16710547)
- [MDN](https://developer.mozilla.org/ko/docs/Web/JavaScript)
- [JavaScript Info](https://ko.javascript.info/)
- [JavaScript Tutorial](https://www.w3schools.com/js/default.asp)

<br>

## 📝 더 나아가서

자바스크립트 스터디 로드맵

- [Dev, Master JavaScript](https://dev.to/dev_abdulhaseeb/master-javascript-1p7a?ref=dailydev)

```bash
├── Basics
│   ├── Variables and Data Types
│   ├── Operators
│   ├── Control Flow (if, else, switch)
│   ├── Loops (for, while, do-while)
│   ├── Functions
│   └── Arrays and Objects
│
├── Advanced Functions
│   ├── Closures
│   ├── Callbacks
│   ├── Promises
│   ├── Async/Await
│   └── Higher-Order Functions
│
├── ES6+ Features
│   ├── Arrow Functions
│   ├── Template Literals
│   ├── Destructuring
│   ├── Rest and Spread Operators
│   ├── Let and Const
│   ├── Classes and Inheritance
│   └── Modules (import/export)
│
├── Object-Oriented Programming (OOP)
│   ├── Objects
│   │   ├── Properties
│   │   └── Methods
│   ├── Constructors
│   │   ├── Constructor Functions
│   │   └── new Keyword
│   ├── Prototypes
│   │   ├── Prototype Chain
│   │   └── Object.create()
│   ├── ES6 Classes
│   │   ├── Class Syntax
│   │   ├── Constructors in Classes
│   │   ├── Methods in Classes
│   │   └── Inheritance with extends
│   ├── Encapsulation
│   │   ├── Closures
│   │   └── Private Variables and Methods
│   ├── Abstraction
│   ├── Polymorphism
│   │   ├── Method Overriding
│   │   └── Method Overloading (JavaScript doesn't support true method overloading)
│   └── Inheritance
│       ├── Single Inheritance
│       └── Multiple Inheritance (JavaScript uses prototype chain for inheritance)
│
├─ Scope and Closures
│
├── This Keyword
│
├── Prototype Chain
│
├── Asynchronous JavaScript
│   ├── Callbacks
│   ├── Promises
│   ├── Async/Await
│   └── Event Loop
│
├── Browser Environment
│    ├── DOM Manipulation
│    ├── Events
│    ├── AJAX and Fetch
│    └── Local Storage
│
├── Error Handling
│   ├── try/catch
│   ├── Error Object
│   └── Custom Errors
│
├── Regular Expressions
│
├── Debugging and Dev Tools
│
├── JavaScript Engines
│
├── Memory Management
│   ├── Garbage Collection
│   └── Memory Leaks
│
├── APIs and HTTP
│   ├── RESTful APIs
│   ├── JSON
│   └── AJAX and Fetch
│
├── Testing
│   ├── Unit Testing
│   ├── Integration Testing
│   └── Test Frameworks (e.g., Jest)
│
├── Build Tools and Module Bundlers
│   ├── Webpack
│   ├── Babel
│   └── npm/yarn
│
├── Frontend Frameworks
│   ├── React
│   ├── Angular
│   └── Vue
│
├── Backend Development with Node.js
│   ├── Express.js
│   ├── npm
│   ├── RESTful APIs
│   └── Authentication and Authorization
│
├── Security
│   ├── HTTPS
│   ├── Cross-Site Scripting (XSS)
│   └── Cross-Site Request Forgery (CSRF)
│
├── Design Patterns
│
├── Functional Programming
│   ├── Pure Functions
│   ├── Immutability
│   ├── First-Class Functions
│   ├── Higher-Order Functions
│   └── Recursion
│
├── Data Structures
│   ├── Arrays
│   ├── Linked Lists
│   ├── Stacks
│   ├── Queues
│   ├── Trees
│   ├── Graphs
│   └── Hash Tables
│
├── Algorithms
│  ├── Sorting
│  ├── Searching
│  ├── Recursion
│  └── Dynamic Programming
│
├── WebSockets
│
├── Progressive Web Apps (PWAs)
│
├── Mobile App Development (React Native)
│
├── WebAssembly (Wasm)
│
├── Machine Learning and JavaScript (TensorFlow.js)
│
└── Miscellaneous
    ├── Code Style and Best Practices
    ├── Code Version Control (e.g., Git)
    ├── Code Review
    └── Continuous Integration/Continuous Deployment (CI/CD)
```

## 💪 Participants

<a href="https://github.com/gather-around-and-code/study-js-deepdive/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=gather-around-and-code/study-js-deepdive" />
</a>
