<div align="center">

# 📖 Java API Reference

**실전 예제와 함께하는 Java 표준 라이브러리 완전 정복**

<br/>

> *"암기가 아닌 이해, 요약이 아닌 통찰"*

실무 개발부터 코딩 테스트까지,  
**왜 그렇게 동작하는지** 원리부터 파헤치는 Java API 심화 학습 자료

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-dev--book--lab-181717?style=flat-square&logo=github)](https://github.com/dev-book-lab)
[![Java](https://img.shields.io/badge/Java-8%2B-orange?style=flat-square&logo=openjdk)](https://www.java.com)
[![Docs](https://img.shields.io/badge/Docs-69개-blue?style=flat-square&logo=readthedocs&logoColor=white)](./README.md)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square&logo=opensourceinitiative&logoColor=white)](./LICENSE)

</div>

---

## 🎯 이 프로젝트에 대하여

단순한 메서드 나열이 아닌, **실전에서 바로 써먹을 수 있는** Java API 레퍼런스입니다.

### ✨ 특징

| 🎯 **원리 중심** | 💻 **실행 가능** | 🔥 **실전 패턴** | 📊 **성능 비교** |
|:---:|:---:|:---:|:---:|
| 왜 그렇게 동작하는지<br/>원리부터 설명 | 모든 코드는<br/>복사-붙여넣기 즉시 실행 | 실무에서<br/>자주 쓰는 패턴 | 같은 기능의<br/>여러 방법 비교 |

- ✅ **200+ 실행 가능한 예제 코드** - 이론만이 아닌 실습 중심
- ✅ **내부 동작 원리 설명** - 단순 암기가 아닌 깊이 있는 이해
- ✅ **25+ 실전 연습 문제** - 학습 내용 즉시 확인
- ✅ **성능 벤치마크 포함** - 언제 무엇을 써야 하는지 명확히
- ✅ **함정 회피 가이드** - 초보자가 자주 하는 실수 미리 차단

---

## 📚 목차

> 💡 **각 챕터를 클릭하면 상세한 학습 문서로 이동합니다**

### 🔹 1. 기초 다지기 (Basics)
가장 기본이 되는 문자열과 숫자, 그리고 배열을 다룹니다.

#### 🔤 String & 문자열
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. 기본 개념](./string/String-01-기본개념.md)** | Immutable & String Pool | 불변성, intern(), 메모리 구조 |
| **[02. 생성과 비교](./string/String-02-생성과비교.md)** | 생성 방법과 비교 메서드 | equals, compareTo, valueOf |
| **[03. 검색과 인덱싱](./string/String-03-검색과인덱싱.md)** | 문자 접근과 위치 찾기 | charAt, indexOf, substring |
| **[04. 변환과 치환](./string/String-04-변환과치환.md)** | 문자열 변환하기 | toUpperCase, replace, trim |
| **[05. 분리와 결합](./string/String-05-분리와결합.md)** | 나누고 합치기 | split, join, StringJoiner |
| **[06. StringBuilder & StringBuffer](./string/String-06-StringBuilder-StringBuffer.md)** | 가변 문자열 처리 | 성능 최적화, 동기화 |
| **[07. 실전 패턴](./string/String-07-실전패턴.md)** | 알고리즘과 실무 패턴 | 팰린드롬, 검증, 파싱, 최적화 |

#### 🔢 Math & Number
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **01. [Math 클래스](./math/Math-01-Math클래스.md)** | 기본 수학 연산과 난수 | abs, pow, sqrt, random, round |
| **02. [Wrapper 클래스](./math/Math-02-Wrapper.md)** | 기본 타입의 객체화 | Integer, valueOf, parseInt, Boxing |
| **03. [BigInteger & BigDecimal](./math/Math-03-Big.md)** | 대용량 및 정밀 연산 | BigInteger, BigDecimal, 정밀도 |

#### 📦 Arrays (배열)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **01. [배열 기본](./arrays/Arrays-01-배열기본.md)** | 배열과 Arrays 클래스 | 선언, 초기화, 기본 연산 |
| **02. [정렬](./arrays/Arrays-02-정렬.md)** | sort, parallelSort | Comparator, 성능 비교 |
| **03. [검색](./arrays/Arrays-03-검색.md)** | binarySearch | 이진 탐색 활용 |
| **04. [비교와 복사](./arrays/Arrays-04-비교와복사.md)** | equals, copyOf | 깊은 복사, 얕은 복사 |
| **05. [변환](./arrays/Arrays-05-변환.md)** | stream, asList | 배열 ↔ List 변환 |
| **06. [다차원 배열](./arrays/Arrays-06-다차원배열.md)** | 2D, 3D 배열 | deepEquals, deepToString |

<br/>

### 🔹 2. 타입 안전성과 예외 처리 (Type Safety & Error Handling)
자료구조를 배우기 전, 안전한 설계를 위한 필수 도구들을 익힙니다.

#### 🛡️ Generics (제네릭)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Generics Basic](./generics/Generics-01-Basic.md)** | 제네릭 클래스와 메서드 기초 | `<T>`, Bounded Type, Type Erasure |
| **[02. Wildcard & PECS](./generics/Generics-02-Wildcard.md)** | 와일드카드와 유연성 설계 | `<?>`, `extends`, `super`, PECS 공식 |

#### 🚦 Enum (열거형)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Enum Basic](./enum/Enum-01-Basic.md)** | 열거형 기초와 특징 | enum, values(), valueOf() |
| **[02. Enum Advanced](./enum/Enum-02-Advanced.md)** | 상수별 동작 구현과 싱글톤 | abstract method, Singleton Pattern |
| **[03. Enum Patterns](./enum/Enum-03-Patterns.md)** | 실전 활용 패턴과 최적화 | Strategy Pattern, EnumMap, EnumSet |

#### ⚠️ Exception (예외 처리)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Exception Basic](./exception/Exception-01-Basic.md)** | 예외 계층 구조와 처리 | try-catch, Checked vs Unchecked |
| **[02. Custom Exception](./exception/Exception-02-Custom.md)** | 사용자 정의 예외 설계 | Domain Exception, Exception Chain |
| **[03. Best Practices](./exception/Exception-03-Best.md)** | 실무 예외 처리 패턴 | Logging, Fail-Fast, Anti-Patterns |

<br/>

### 🔹 3. 자료구조 (Collections Framework)
List, Set, Map, Queue의 모든 것을 다룹니다.

#### 📋 List Interface (순서가 있는 저장 공간)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **01. [Collections 개요](./collections/Collections-01-Overview.md)** | 프레임워크 전체 구조 | Collection, Iterable, 계층 구조 |
| **02. [ArrayList](./collections/Collections-02-ArrayList.md)** | 동적 배열 구현 | add, get, resize, 성능 |
| **03. [LinkedList](./collections/Collections-03-LinkedList.md)** | 이중 연결 리스트 | addFirst, removeLast, Node |
| **04. [List 비교와 선택](./collections/Collections-04-ListComparison.md)** | 상황별 List 선택 가이드 | 조회 vs 삽입/삭제, 성능 비교 |

#### 🎯 Set Interface (중복 없는 집합)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **05. [HashSet](./collections/Collections-05-HashSet.md)** | 중복 없는 데이터 집합 | hashCode, equals, 유일성 |
| **06. [LinkedHashSet](./collections/Collections-06-LinkedHashSet.md)** | 순서가 있는 Set | 입력 순서 보장, LRU 캐시 |
| **07. [TreeSet](./collections/Collections-07-TreeSet.md)** | 정렬된 Set | 이진 탐색 트리, 범위 검색 |
| **08. [Set 비교와 선택](./collections/Collections-08-SetComparison.md)** | 상황별 Set 선택 가이드 | 정렬 필요성, 입력 순서 |

#### 🗺️ Map Interface (키-값 쌍 저장)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **09. [HashMap](./collections/Collections-09-HashMap.md)** | 키-값 쌍 데이터 저장 | put, get, 해시 충돌, 버킷 |
| **10. [LinkedHashMap](./collections/Collections-10-LinkedHashMap.md)** | 순서가 있는 Map | 삽입 순서, 접근 순서 |
| **11. [TreeMap](./collections/Collections-11-TreeMap.md)** | 정렬된 Map | 키 기준 정렬, NavigableMap |
| **12. [Map 비교와 선택](./collections/Collections-12-MapComparison.md)** | 상황별 Map 선택 가이드 | 키 정렬, 순서 보장 여부 |

#### 📤 Queue & Utils (대기열 및 보조 도구)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **13. [Queue & Deque](./collections/Collections-13-QueueDeque.md)** | 대기열 처리 자료구조 | offer, poll, peek, FIFO |
| **14. [PriorityQueue](./collections/Collections-14-PriorityQueue.md)** | 우선순위 큐 | 힙(Heap), 우선순위 정렬 |
| **15. [Stack](./collections/Collections-15-Stack.md)** | LIFO 자료구조 | push, pop, Vector 상속 문제 |
| **16. [Collections 유틸](./collections/Collections-16-CollectionsUtil.md)** | 컬렉션 보조 도구 | sort, binarySearch, synchronized |

<br/>

### 🔹 4. 모던 자바와 데이터 처리 (Modern Java)
Java 8부터 최신 버전(Java 21)까지의 문법과 데이터 처리 기법입니다.

#### 🚀 Lambda & Functional Interface (람다)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Functional Interface](./lambda/Lambda-01-FunctionalInterface.md)** | 람다식과 표준 인터페이스 | Consumer, Supplier, Function, Predicate |
| **[02. Method Reference](./lambda/Lambda-02-MethodReference.md)** | 메서드 참조와 생성자 참조 | `Class::method`, `new::` |
| **[03. Custom Lambda](./lambda/Lambda-03-Custom.md)** | 커스텀 인터페이스와 변수 포획 | @FunctionalInterface, Variable Capture |

#### ✨ Modern Java Features (Java 9~21)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Record](./modern-java/ModernJava-01-Record.md)** | 불변 데이터 클래스 | record, Compact Constructor, DTO |
| **[02. Switch Expression](./modern-java/ModernJava-02-Switch.md)** | 향상된 분기 처리 | arrow syntax, yield, Pattern Matching |
| **[03. Sealed Class](./modern-java/ModernJava-03-Sealed.md)** | 상속 제한 및 계층 제어 | sealed, permits, non-sealed |

#### 🛠️ Modern Data Utilities (Stream & Optional)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Comparator & Comparable](./utils/Util-01-Comparator.md)** | 정렬과 비교 기준 | compare, compareTo, thenComparing |
| **[02. Stream API](./utils/Util-02-Stream.md)** | 데이터 처리 파이프라인 | filter, map, collect, reduce |
| **[03. Optional](./utils/Util-03-Optional.md)** | Null 안전 처리 | ofNullable, orElse, isPresent |
| **[04. 정규표현식](./utils/Util-04-Regex.md)** | 텍스트 패턴 매칭 | Pattern, Matcher, regex |

<br/>

### 🔹 5. 실무 필수 API (Practical APIs)
비즈니스 로직과 시스템 제어에 필수적인 API입니다.

#### 📅 Date & Time (날짜와 시간)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **01. [Time API 개요](./datetime/DateTime-01-개요.md)** | Java 8 Time API | LocalDate, ZonedDateTime |
| **02. [Local 클래스](./datetime/DateTime-02-Local.md)** | LocalDate, LocalTime, LocalDateTime | 날짜/시간 기본 |
| **03. [Zoned & Instant](./datetime/DateTime-03-Zoned.md)** | ZonedDateTime, Instant | 타임존, UTC |
| **04. [Period & Duration](./datetime/DateTime-04-Period.md)** | 기간 계산 | 날짜 차이, 시간 차이 |
| **05. [포맷팅](./datetime/DateTime-05-Formatter.md)** | DateTimeFormatter | 날짜 포맷 변환 |
| **06. [레거시 vs 신규](./datetime/DateTime-06-Legacy.md)** | Date, Calendar 비교 | 마이그레이션 가이드 |

#### 💾 IO & 입출력
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **01. [File 기본](./io/IO-01-File.md)** | 파일 시스템 다루기 | File, Path, Files |
| **02. [텍스트 파일 입출력](./io/IO-02-Text.md)** | 문자 스트림 (Reader/Writer) | BufferedReader, 인코딩 |
| **03. [바이트 스트림](./io/IO-03-Binary.md)** | 바이너리 & 객체 직렬화 | BufferedStream, Serializable |

<br/>

### 🔹 6. 심화 학습 (Advanced)
가장 난이도가 높고 주의가 필요한 메타 프로그래밍과 동시성입니다.

#### 🪞 Reflection (리플렉션)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Reflection Basic](./reflection/Reflection-01-Basic.md)** | 런타임 클래스 정보 조작 | Class, Method, Field, Constructor |
| **[02. Annotation](./reflection/Reflection-02-Annotation.md)** | 메타데이터 활용 | @Target, @Retention, @Repeatable |
| **[03. Advanced](./reflection/Reflection-03-Advanced.md)** | 프록시 및 고급 기법 | Dynamic Proxy, MethodHandle, Performance |

#### 🔄 Concurrency & Multithreading (동시성)
| Chapter | 주제 | 핵심 키워드 |
|:-------:|------|------------|
| **[01. Thread & Runnable](./concurrency/Concurrency-01-Thread.md)** | 스레드 생성과 생명주기 | Thread, Runnable, sleep, join |
| **[02. Synchronization](./concurrency/Concurrency-02-Sync.md)** | 동기화와 락(Lock) 제어 | synchronized, volatile, ReentrantLock |
| **[03. ExecutorService](./concurrency/Concurrency-03-Executor.md)** | 스레드 풀 관리 프레임워크 | ThreadPoolExecutor, submit, shutdown |
| **[04. Concurrent Collections](./concurrency/Concurrency-04-Concurrent.md)** | 스레드 안전 컬렉션 | ConcurrentHashMap, CopyOnWriteArrayList |
| **[05. Atomic Variables](./concurrency/Concurrency-05-Atomic.md)** | 락 없는(Lock-free) 동기화 | AtomicInteger, CAS, ABA Problem |
| **[06. CompletableFuture](./concurrency/Concurrency-06-Future.md)** | 비동기 프로그래밍 패턴 | supplyAsync, thenApply, allOf |
| **[07. Virtual Threads](./concurrency/Concurrency-07-Virtual.md)** | Java 21 가상 스레드 | Virtual Thread, Structured Concurrency |

<br/>

---

## 🗺️ 학습 로드맵

### 🎯 목적별 학습 경로

<details>
<summary><b>📘 입문자 (Java 처음 배우는 분)</b></summary>

<br/>

**1주차: 기초 다지기**
```
✅ Day 1-2: String 01-04 (기본 개념, 생성, 검색, 변환)
✅ Day 3-4: Arrays 01-02 (배열 기본, 정렬)
✅ Day 5-7: Math 01-02 + Exception 01
```

**2주차: 자료구조 입문**
```
✅ Day 1-2: Collections 01 (개요) + 02 (ArrayList)
✅ Day 3-4: Collections 03-04 (LinkedList, List 비교)
✅ Day 5-7: Collections 05-06 (HashSet, LinkedHashSet)
```

**3주차: 타입 안전성**
```
✅ Day 1-3: Exception 02-03 (커스텀 예외, Best Practices)
✅ Day 4-5: Generics 01-02
✅ Day 6-7: Enum 01-02
```

**4주차: Modern Java 시작**
```
✅ Day 1-3: Lambda 01-03
✅ Day 4-5: Util 02 (Stream API)
✅ Day 6-7: Util 03 (Optional)
```

</details>

<details>
<summary><b>💼 실무자 (업무에 바로 적용)</b></summary>

<br/>

**Week 1: 핵심 자료구조 마스터**
```
✅ Collections 전체 집중
✅ ArrayList vs LinkedList 성능 비교
✅ HashMap 내부 구조 이해
✅ ConcurrentHashMap 실전 활용
```

**Week 2: 날짜/시간 & 파일 처리**
```
✅ DateTime 01-06 (전체)
✅ IO 01-03 (파일 입출력)
✅ Exception Best Practices
```

**Week 3: 함수형 프로그래밍**
```
✅ Lambda 01-03
✅ Stream API 완전 정복
✅ Optional로 null 안전 처리
✅ Comparator 고급 활용
```

**Week 4: 동시성 & 성능 최적화**
```
✅ Concurrency 01-04
✅ Thread Pool 설계
✅ 동기화 문제 해결
✅ Concurrent Collections
```

</details>

<details>
<summary><b>🏆 코딩테스트 준비</b></summary>

<br/>

**우선순위 1 (필수):**
```
✅ String 전체 (7개) - 문자열 조작 완벽
✅ Arrays 전체 (6개) - 정렬, 검색, 이진탐색
✅ Collections 04, 08, 12 - List/Set/Map 비교
✅ Math 01 - 수학 함수
```

**우선순위 2 (중요):**
```
✅ Collections 02, 05, 09 - ArrayList, HashSet, HashMap
✅ Collections 13-14 - Queue, PriorityQueue, Stack
✅ Util 01 - Comparator & Comparable
✅ Util 02 - Stream API 기본
```

**우선순위 3 (심화):**
```
✅ String 07 - 실전 패턴 (팰린드롬, 파싱)
✅ Arrays 06 - 다차원 배열
✅ Collections 07, 11 - TreeSet, TreeMap
✅ Util 04 - 정규표현식
```

**추천 학습 순서:**
```
String → Arrays → Collections (List, Set, Map) 
→ Queue/Stack → Comparator → Stream 기본
```

</details>

<details>
<summary><b>🚀 Modern Java 마스터 (Java 17-21)</b></summary>

<br/>

**Phase 1: 기본기 확인**
```
✅ Lambda 01-03 (람다 & 함수형 인터페이스)
✅ Stream API (데이터 처리 파이프라인)
✅ Optional (null 안전 처리)
```

**Phase 2: Modern Features**
```
✅ Record - 불변 데이터 클래스 (Java 16+)
✅ Switch Expression - 향상된 분기 (Java 14+)
✅ Sealed Class - 상속 제어 (Java 17+)
```

**Phase 3: 최신 동시성**
```
✅ Virtual Threads (Java 21+)
✅ Structured Concurrency
✅ CompletableFuture 고급 패턴
```

**Phase 4: 고급 활용**
```
✅ Pattern Matching (Type Patterns)
✅ Text Blocks
✅ var (Local Variable Type Inference)
```

</details>

<details>
<summary><b>⚡ 빠른 복습 (경력 개발자)</b></summary>

<br/>

**Day 1: 핵심만 빠르게**
```
✅ String 07 (실전 패턴)
✅ Collections 04, 08, 12 (비교 문서)
✅ Util 02 (Stream API)
```

**Day 2: Modern Java**
```
✅ Lambda 전체
✅ Modern Java 01-03 (Record, Switch, Sealed)
✅ Concurrency 06 (CompletableFuture)
```

**Day 3: 심화**
```
✅ Concurrency 07 (Virtual Threads)
✅ Reflection 전체
✅ Exception 03 (Best Practices)
```

</details>

---

## 🎓 학습 방법

```
📖 Read → 💻 Practice → 🤔 Think → 📝 Review → 🔁 Repeat
```

### 1️⃣ 기초부터 차근차근
```
String 01~03 → Collections (ArrayList, HashMap) → Arrays 기본
```

### 2️⃣ 핵심 자료구조 마스터
```
String 전체 → Collections 전체 → Math & Arrays
```

### 3️⃣ 심화 및 최적화
```
전체 심화 → 성능 최적화 → 실전 패턴
```

---

## 💻 시작하기

### 📋 필요 사항
- **Java 8** 이상 (일부 Java 11+ 기능 포함)
- **IntelliJ IDEA** 또는 Eclipse, VS Code

### 1️⃣ Repository 클론
```bash
git clone https://github.com/dev-book-lab/java-api-reference.git
cd java-api-reference
```

### 2️⃣ 학습 방법
1. 관심 있는 챕터의 문서 읽기
2. 예제 코드를 직접 실행하며 이해
3. 연습 문제로 실력 확인
4. 실전 패턴을 프로젝트에 적용

---

## 📖 문서 구성

각 문서는 다음과 같은 구조로 구성됩니다:

| 섹션 | 설명 |
|------|------|
| 📌 **기본 개념** | 이론과 원리 설명 |
| 💻 **메서드 레퍼런스** | 사용법과 예제 코드 |
| 🔥 **실전 활용** | 실무 패턴과 활용법 |
| 🎯 **연습 문제** | 학습 내용 확인 |
| ⚡ **성능 비교** | 여러 방법의 성능 측정 |
| 📌 **핵심 정리** | 빠른 복습용 요약 |

---

## 🤝 기여하기

더 좋은 예제나 설명이 있다면 언제든 환영합니다!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingExample`)
3. Commit your changes (`git commit -m 'Add amazing example'`)
4. Push to the branch (`git push origin feature/AmazingExample`)
5. Open a Pull Request

---

## 🙏 Reference

- [Oracle Java Documentation](https://docs.oracle.com/en/java/)
- [OpenJDK Source Code](https://github.com/openjdk/jdk)

---

## ✨ Dev Book Lab

<div align="center">

**AI와 함께 개발 서적을 분석하고 정리하는 연구소**

[📂 More Projects](https://github.com/dev-book-lab)

</div>

---

<div align="center">

**⭐️ 도움이 되셨다면 Star를 눌러주세요!**

Made with ❤️ by Dev Book Lab

<br/>

**"암기가 아닌 이해, 요약이 아닌 통찰"**

</div>
