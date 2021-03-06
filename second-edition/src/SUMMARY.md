# The Rust Programming Language

## Getting started

- [Introduction](ch01-00-introduction.md)
    - [Installation](ch01-01-installation.md)
    - [Hello, World!](ch01-02-hello-world.md)

- [추리 게임 튜토리얼](ch02-00-guessing-game-tutorial.md)

- [보편적인 프로그래밍 개념](ch03-00-common-programming-concepts.md)
    - [Variables and Mutability](ch03-01-variables-and-mutability.md)
    - [Data Types](ch03-02-data-types.md)
    - [How Functions Work](ch03-03-how-functions-work.md)
    - [Comments](ch03-04-comments.md)
    - [Control Flow](ch03-05-control-flow.md)

- [소유권 이해하기](ch04-00-understanding-ownership.md)
    - [소유권이 뭔가요?](ch04-01-what-is-ownership.md)
    - [참조자와 빌림](ch04-02-references-and-borrowing.md)
    - [슬라이스](ch04-03-slices.md)

- [연관된 데이터들을 구조체로 다루기](ch05-00-structs.md)
    - [구조체를 정의하고 생성하기](ch05-01-defining-structs.md)
    - [구조체를 이용한 예제 프로그램](ch05-02-example-structs.md)
    - [메소드 문법](ch05-03-method-syntax.md)

- [열거형과 패턴 매칭](ch06-00-enums.md)
    - [열거형 정의하기](ch06-01-defining-an-enum.md)
    - [`match` 흐름 제어 연산자](ch06-02-match.md)
    - [`if let`을 사용한 간결한 흐름 제어](ch06-03-if-let.md)

## Basic Rust Literacy

- [모듈](ch07-00-modules.md)
    - [`mod`와 파일 시스템](ch07-01-mod-and-the-filesystem.md)
    - [`pub`으로 가시성 제어하기](ch07-02-controlling-visibility-with-pub.md)
    - [`use`로 이름 가져오기](ch07-03-importing-names-with-use.md)

- [일반적인 컬렉션](ch08-00-common-collections.md)
    - [벡터](ch08-01-vectors.md)
    - [스트링](ch08-02-strings.md)
    - [해쉬맵](ch08-03-hash-maps.md)

- [에러 처리](ch09-00-error-handling.md)
    - [`panic!`과 함께하는 복구 불가능한 에러](ch09-01-unrecoverable-errors-with-panic.md)
    - [`Result`와 함께하는 복구 가능한 에러](ch09-02-recoverable-errors-with-result.md)
    - [`panic!`이냐, `panic!`이 아니냐, 그것이 문제로다](ch09-03-to-panic-or-not-to-panic.md)

- [제네릭 타입, 트레잇, 그리고 라이프타임](ch10-00-generics.md)
    - [제네릭 데이터 타입](ch10-01-syntax.md)
    - [트레잇: 공유 동작을 정의하기](ch10-02-traits.md)
    - [라이프타임을 이용한 참조자 유효화](ch10-03-lifetime-syntax.md)

- [테스팅](ch11-00-testing.md)
    - [테스트 작성하기](ch11-01-writing-tests.md)
    - [테스트 실행하기](ch11-02-running-tests.md)
    - [테스트 조직화](ch11-03-test-organization.md)

- [An I/O Project](ch12-00-an-io-project.md)
    - [Accepting Command Line Arguments](ch12-01-accepting-command-line-arguments.md)
    - [Reading a File](ch12-02-reading-a-file.md)
    - [Improving Error Handling and Modularity](ch12-03-improving-error-handling-and-modularity.md)
    - [Testing the Library's Functionality](ch12-04-testing-the-librarys-functionality.md)
    - [Working with Environment Variables](ch12-05-working-with-environment-variables.md)
    - [Writing to `stderr` instead of `stdout`](ch12-06-writing-to-stderr-instead-of-stdout.md)

## Thinking in Rust

- [Functional Language Features in Rust](ch13-00-functional-features.md)
    - [Closures](ch13-01-closures.md)
    - [Iterators](ch13-02-iterators.md)
    - [Improving our I/O Project](ch13-03-improving-our-io-project.md)
    - [Performance](ch13-04-performance.md)

- [More about Cargo and Crates.io](ch14-00-more-about-cargo.md)
    - [Release Profiles](ch14-01-release-profiles.md)
    - [Publishing a Crate to Crates.io](ch14-02-publishing-to-crates-io.md)
    - [Cargo Workspaces](ch14-03-cargo-workspaces.md)
    - [Installing Binaries from Crates.io with `cargo install`](ch14-04-installing-binaries.md)
    - [Extending Cargo with Custom Commands](ch14-05-extending-cargo.md)

- [스마트 포인터](ch15-00-smart-pointers.md)
    - [`Box<T>`는 힙에 있는 데이터를 가리키고 알려진 크기를 갖습니다](ch15-01-box.md)
    - [`Deref` 트레잇은 참조자를 통하여 데이터로의 접근을 허용합니다](ch15-02-deref.md)
    - [`Drop` 트레잇은 메모리 정리 코드를 실행시킵니다](ch15-03-drop.md)
    - [`Rc<T>`, 참조 카운팅 스마트 포인터](ch15-04-rc.md)
    - [`RefCell<T>`와 내부 가변성 패턴](ch15-05-interior-mutability.md)
    - [Creating Reference Cycles and Leaking Memory is Safe](ch15-06-reference-cycles.md)

- [Fearless Concurrency](ch16-00-concurrency.md)
    - [Threads](ch16-01-threads.md)
    - [Message Passing](ch16-02-message-passing.md)
    - [Shared State](ch16-03-shared-state.md)
    - [Extensible Concurrency: `Sync` and `Send`](ch16-04-extensible-concurrency-sync-and-send.md)

- [Is Rust an Object-Oriented Programming Language?](ch17-00-oop.md)
    - [What Does Object-Oriented Mean?](ch17-01-what-is-oo.md)
    - [Trait Objects for Using Values of Different Types](ch17-02-trait-objects.md)
    - [Object-Oriented Design Pattern Implementations](ch17-03-oo-design-patterns.md)

## Advanced Topics

- [Patterns Match the Structure of Values](ch18-00-patterns.md)
    - [All the Places Patterns May be Used](ch18-01-all-the-places-for-patterns.md)
    - [Refutability: Whether a Pattern Might Fail to Match](ch18-02-refutability.md)
    - [All the Pattern Syntax](ch18-03-pattern-syntax.md)

- [Advanced Features](ch19-00-advanced-features.md)
    - [Unsafe Rust](ch19-01-unsafe-rust.md)
    - [Advanced Lifetimes](ch19-02-advanced-lifetimes.md)
    - [Advanced Traits](ch19-03-advanced-traits.md)
    - [Advanced Types](ch19-04-advanced-types.md)
    - [Advanced Functions & Closures](ch19-05-advanced-functions-and-closures.md)

- [Final Project: Building a Multithreaded Web Server](ch20-00-final-project-a-web-server.md)
    - [A Single Threaded Web Server](ch20-01-single-threaded.md)
    - [How Slow Requests Affect Throughput](ch20-02-slow-requests.md)
    - [Designing the Thread Pool Interface](ch20-03-designing-the-interface.md)
    - [Creating the Thread Pool and Storing Threads](ch20-04-storing-threads.md)
    - [Sending Requests to Threads Via Channels](ch20-05-sending-requests-via-channels.md)
    - [Graceful Shutdown and Cleanup](ch20-06-graceful-shutdown-and-cleanup.md)

- [Appendix](appendix-00.md)
    - [A - Keywords](appendix-01-keywords.md)
    - [B - Operators](appendix-02-operators.md)
    - [C - Derivable Traits]()
    - [D - Nightly Rust]()
    - [E - Macros]()
    - [F - Translations]()
    - [G - Newest Features](appendix-07-newest-features.md)
