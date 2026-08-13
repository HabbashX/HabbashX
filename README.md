# Abd Allah Al Habbash

Java backend developer. Self-taught, project-driven, 4+ years building things from scratch — compilers, HTTP frameworks, payment systems, desktop apps. Currently studying Management Information Systems at the University of Palestine.

I build the hard-to-find infrastructure pieces: a JVM-targeting language, an annotation-driven HTTP client framework, and backend systems built for constrained environments like Gaza.

---

![metrics](github-metrics.svg)

---

## Projects

### Larv
A custom JVM-targeting programming language written in Java. Full compiler pipeline — Lexer → Parser → AST → Compiler — with Java FFI via `include`/`involve` syntax, direct bytecode generation (`INVOKEVIRTUAL` dispatch), and a 13-module standard library. Comes with an IntelliJ IDEA plugin: syntax highlighting, real-time error squiggles, five inspections, and a project wizard with build tool support.

### AxiomHttp
An annotation-driven HTTP client framework for Java, using ByteBuddy proxies to generate Retrofit-style clients at runtime. Started as WebScrapingJava before evolving into a general-purpose framework.

### Property-Parser
A Java library for parsing and resolving property files.

### GazaPay
A payment notification and forwarding system for Palestinian payment providers (Jawwal Pay, Pal Pay, Bank of Palestine). Spring Boot 3.x backend with clean architecture, JWT auth, HMAC-SHA256 signed webhooks, WebSocket device heartbeat, and Telegram/SMS notification routing — paired with an Android companion app for notification capture and forwarding.

### Exams Resolver
A Java Swing desktop application with a custom developer console system (Logback `SwingConsoleAppender`, replay buffer, level-based coloring) and a bytecode encryption pipeline using AES-256-GCM with a custom `ClassLoader`.

---

## Stack

`Java` `Spring Boot` `Kotlin/Android` `PostgreSQL` `WebSocket` `JWT` `HTMX` `Vue 3` `Three.js`

---

<div align="right"><i>Building from Gaza, Palestine.</i></div>
