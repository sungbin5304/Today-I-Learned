![banner](https://raw.githubusercontent.com/sungbin5304/Programming-Study/master/images/banner.png)

-----

# Languages
- [x] [JavaScript](https://github.com/sungbin5304/KUtils)
- [x] [Java](https://github.com/sungbin5304/SnsAutoReplyBot)
- [ ] TypeScript
- [ ] Node.js
- [ ] C
- [ ] C#
- [ ] C++
- [x] [Kotlin](https://github.com/sungbin5304/AndroidUtils)
- [ ] Lua
- [ ] Deno
- [ ] Swift
- [ ] Rust
- [ ] Dart (flutter)

# Android 
## 라이브러리
- [ ] OkHttp
- [x] Retrofit
- [ ] Coroutine
- [x] RxJava
- [x] RxKotlin
- [x] RxAndroid
- [ ] Dagger
- [ ] Koin
- [ ] Hilt
- [ ] Paging
- [ ] Realm
- [ ] LiveData
- [x] DataBinding
- [ ] Room

## 아키텍처 패턴
- [x] [MVVM](https://github.com/sungbin5304/SpotiPlayer)
- [x] [MVP](https://github.com/sungbin5304/Android-Study/tree/master/pattern/MVP)
- [ ] MVC

## 생명주기
[Activity Life-Cycle](https://raw.githubusercontent.com/sungbin5304/Today-I-Learned/master/images/Activity%20Life-Cycle.png)<br/>
[Layout Life-Cycle](https://raw.githubusercontent.com/sungbin5304/Today-I-Learned/master/images/Layout%20Life-Cycle.png)

## 4대 컴포너트
1. Activity
2. Service
3. BroadCast Receiver
4. Content Provider

## [Context](https://sungbin.me/m/entry/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-Context%EC%9D%98-%EC%A2%85%EB%A5%98)
> 싱글톤 인스턴스

1. Application Context
2. Activity Context

## Dagger
> Component Method

`Provision Method` : 매개변수 X, 모듈이 제공하는 객체타입을 받음<br/><br/>
`Member-Injection Method` : 의존성 주입을 받을 객체를 메소드의 피라미터로 넘김 (`@Inject`)

-----

# Words
## 블로킹/논블로킹
> 유후상태 매커니즘

`블로킹` : //todo<br/><br/>
`논블로킹` : 블로킹의 반대 상태 -> //todo

## 동기/비동기
> 순서보장 매커니즘

`동기` : 현재 작업의 요청과 응답이 동시에 발생하는것 -> 현재 작업의 응답과 다음 작업의 요청이 동시에 발생<br/><br/>
`비동기` : 동기의 반대 상태 -> 현재 작업의 응답과 다음 작업의 요청의 타이밍이 일치하지 않아도 됨

## I/O
> Input/Output

`CPU`/`메모리`와 정보를 주고받음 (연산을 함)

## 프레임워크
개발에 바탕이 되는 템플릿과 같은 역할을 하는 `class`와 `interface`들의 집합

## 런타임
프로그램이 실행되고 있을때 존재하는 곳 -> 프로그래밍 언어가 구동되는 환경

## 컴파일타임
//todo

## 인터프리터 
//todo

## 프로세스
운영체재 활당 작업단위 -> 자원공유 X

## 스레드
프로세스 내에서 실행되는 흐름 단위 -> 자원 공유 O

## Dependency Injection
> 의존성 주입

`java`와 `android`를 위해 완전히 정적으로 되있는 컴파일타임 의존성 주입 프레임워크

## reflection
프로그램 내부 속성을 조작할 수 있게 해줌

## 싱글톤
`scope`를 지정하고 객체를 재사용함

## 보일러플레이트 코드
> BoilerPlate Code

최소한의 변경으로 여러곳에서 재사용 되며, 반복적으로 비슷한 형태를 띄는 코드
