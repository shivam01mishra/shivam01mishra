# Shivam Mishra

Software engineer working on **AI inference and model optimization**, with a systems, backend, and performance-engineering foundation underneath it. I care about how things work at the level below the framework — memory layout, concurrency, and where the cycles actually go.

Day to day right now: inference/optimization work (current focus), plus Java/Spring Boot backend work on the side to stay sharp on distributed systems fundamentals.

### Core technical areas

`C++ (11/14/17/20)` · `Data Structures & Algorithms` · `Multithreading & Concurrency` · `Linux & Systems Programming` · `Memory Management` · `Networking` · `Performance Optimization` · `Java` · `Spring Boot` · `Kafka` · `Redis` · `PostgreSQL` · `Python` · `Distributed Systems`

### Selected projects

- **[OS-COMPONENTS-CPP](https://github.com/shivam01mishra/OS-COMPONENTS-CPP)** — a collaborative group project building core OS components in C++: a memory allocator (wrapped in an `Allocator` class), a CPU process scheduler (FCFS/SJF/Round Robin/priority with aging), a cooperative user-space thread library (context switching, join/exit, its own round-robin scheduler), and IPC (pipes, message queues) so far, with virtual memory, a file system, and a shell still to come. Forked from [PoojaGoel-IIT/OS-COMPONENTS-CPP](https://github.com/PoojaGoel-IIT/OS-COMPONENTS-CPP).
- **[url-shortener](https://github.com/shivam01mishra/url-shortener)** — a URL-shortening service on Spring Boot 3.3 / Java 21 with PostgreSQL, a proper layered package structure, and a JUnit/MockMvc/H2 test suite.
- **[differential-Privacy-using-coreset](https://github.com/shivam01mishra/differential-Privacy-using-coreset)** — coreset-based sampling for privacy-preserving, compute-efficient clustering; measures approximation error vs. random sampling.
- **[Core-Machine-leaning](https://github.com/shivam01mishra/Core-Machine-leaning)** — active learning / submodularity for informative subset selection, benchmarked across KNN, Logistic Regression, SVM, and Random Forest.
- **[Brain-tumor-detection-](https://github.com/shivam01mishra/Brain-tumor-detection-)** — CNN-based brain tumor classification from MRI scans (Keras/TensorFlow).

### Systems & C++

**[System_design](https://github.com/shivam01mishra/System_design)** is where most of my C++ systems practice lives:
- Multithreading primitives built from scratch: a working thread pool, ring buffers (including a multi-producer/multi-consumer variant), producer-consumer, atomic flags.
- Hand-rolled STL pieces (`unique_ptr`, `shared_ptr`, a dynamic array) to understand what the standard library is doing under the hood.
- Two full low-level-design exercises: a **Parking Lot** system and an **Elevator System**, each split into single-responsibility classes.
- C++17 features (`optional`, `variant`, `any`) and classic design patterns (Singleton, Observer, Factory, Abstract Factory).

### Backend & distributed systems

- **[url-shortener](https://github.com/shivam01mishra/url-shortener)** — Spring Boot + PostgreSQL, tested end to end.
- **[java](https://github.com/shivam01mishra/java)** — an Order/Inventory Management backend built iteratively (Spring Boot, JPA/Hibernate, JWT auth, Redis caching, optimistic locking with `@Version`), plus a modular Parking Lot LLD exercise.
- Comfortable with Kafka and Redis for the messaging/caching side of distributed systems, applied here at practice scale.

### Competitive programming

**[Competitive-Programming](https://github.com/shivam01mishra/Competitive-Programming)** — solutions across LeetCode, Codeforces, and CodeChef, plus reusable DSA templates (Union-Find, monotonic-stack next-greater, segment tree).

- LeetCode rating: 1850+
- HackerRank: 5-star (C++)
- GATE CS: 99th percentile

### Currently learning

AI inference optimization techniques, and going deeper on distributed systems design (the Kafka/Redis side of things beyond toy examples).

### Get in touch

- LinkedIn: [shivam-mishra-3242361aa](https://linkedin.com/in/shivam-mishra-3242361aa)
- Email: mishrashivam@alumni.iitgn.ac.in
