**16-Week .NET Full Stack Senior / Technical Lead Interview Program**

_11+ Years Experience • 500+ Interview Questions • Coding • System Design • Azure • AI_

Objective: prepare for Senior .NET Full Stack Developer, Lead Engineer and Technical Lead interviews by combining deep C#/.NET knowledge, hands-on coding, frontend, SQL, Azure/DevOps, distributed systems, system design, Python, GenAI/RAG/Agentic AI, and leadership stories.

# How to use this program

- Study 2–3 hours on weekdays and 3–4 hours on the weekend.
- For every topic: learn the concept → write code → explain a production scenario → answer interview questions aloud.
- Use a 60–90 second answer for normal questions and a 3–5 minute answer for architecture/scenario questions.
- For coding: first solve without AI/search, then review edge cases, complexity, tests, and production concerns.
- Maintain an interview notebook containing your own project examples, metrics, trade-offs, failures and lessons learned.

# 16-week calendar

## Week 1 — C# Core + OOP

- Types, memory model, OOP, interfaces/abstract classes, generics, equality, strings, exceptions
- Coding: implement immutable value object, generic repository, equality correctly, custom exception hierarchy
- Mock: 20 C# rapid-fire questions + 2 coding problems

## Week 2 — Advanced C# + Async/Concurrency

- Delegates/events, LINQ, iterators, Span/Memory, records, pattern matching, GC
- async/await, Task vs ValueTask, cancellation, locks, SemaphoreSlim, concurrent collections
- Coding: async batch processor, bounded concurrency, producer/consumer, cancellation

## Week 3 — ASP.NET Core

- Hosting/Kestrel, middleware pipeline, DI lifetimes, configuration/options, logging, validation
- Controllers/minimal APIs, filters, ProblemDetails, health checks, caching, rate limiting
- Coding: production-style REST API with DI, validation, global errors, logging and health checks

## Week 4 — API Security + EF Core

- HTTP/REST semantics, versioning, pagination, idempotency, JWT/OAuth/OIDC, policies/RBAC
- EF Core tracking, relationships, transactions, concurrency, migrations, query optimization
- Coding: secured CRUD API with policy authorization and optimized EF queries

## Week 5 — Dapper + SQL Server

- Dapper repository patterns, parameterization, transactions, multi-mapping
- JOINs, CTEs, window functions, indexes, execution plans, isolation levels, deadlocks
- Coding: reporting API using Dapper + stored procedure; tune three intentionally slow queries

## Week 6 — Architecture + Design Patterns

- SOLID, Clean Architecture, CQRS, Mediator, Repository trade-offs
- Factory, Strategy, Decorator, Adapter, Observer, Chain of Responsibility
- Coding: extensible payment strategy engine and notification strategy

## Week 7 — Microservices + Messaging

- Service boundaries, API gateway, resilience, retries, circuit breakers, Saga, Outbox
- RabbitMQ exchanges/queues, acknowledgements, DLQ, retry, ordering, idempotency
- Coding: order → payment → notification event workflow

## Week 8 — gRPC + Distributed Systems

- Protocol Buffers, unary/streaming calls, interceptors, REST vs gRPC
- Distributed consistency, CAP, eventual consistency, caching, Redis, observability
- Coding: gRPC inventory service + REST gateway + correlation ID

## Week 9 — Angular + React

- Angular components, DI, RxJS, signals, routing, guards, interceptors, reactive forms
- React hooks, state, context, memoization, API integration, authentication
- Coding: authenticated order dashboard with pagination, filtering and error handling

## Week 10 — Azure

- App Service, Functions, Container Apps/AKS basics, Azure SQL, Blob, Service Bus, Redis
- Entra ID, Key Vault, Managed Identity, Application Insights, Monitor, Log Analytics
- Architecture lab: deploy API + database + queue + monitoring

## Week 11 — Azure DevOps + Docker + CI/CD

- Git strategy, PRs, YAML pipelines, artifacts, environments, approvals
- Dockerfiles, multi-stage builds, Compose, deployment slots, blue/green/canary
- Coding/lab: complete build-test-scan-package-deploy pipeline

## Week 12 — System Design + Performance

- Scalability, availability, partitioning, caching, queues, rate limiting
- SQL/API profiling, GC/allocations, thread pool starvation, N+1, load testing
- Design: payment, travel, notification and file-processing platforms

## Week 13 — Python + FastAPI

- Python data structures, functions, OOP, decorators, generators, typing, asyncio
- FastAPI, Pydantic, SQLAlchemy, pytest, async APIs
- Coding: FastAPI service that consumes a .NET API and persists results

## Week 14 — LLM + Prompt Engineering

- LLM fundamentals, tokens/context, structured output, tool calling, streaming
- OpenAI API concepts, evaluation, guardrails, cost/latency, prompt design
- Coding: .NET/Python AI assistant with tools and structured JSON output

## Week 15 — RAG + Agentic AI

- Chunking, embeddings, vector search, metadata filtering, reranking, citations
- Agents, tools, planning, state, memory, sub-agents, human approval, MCP concepts
- Coding: Azure DevOps failure-analysis agent with RAG + tools

## Week 16 — Leadership + Final Interview Sprint

- STAR stories, architecture decisions, mentoring, conflict, incidents, ownership
- Daily mixed mock interviews; resume/project deep dives; negotiation questions
- Final: 3 full mocks + 5 system designs + 5 coding sessions

# Daily operating rhythm

Day 1: Learn + notes — 90 min concept + 45 min coding + 15 min verbal explanation

Day 2: Deep dive — 60 min internals + 60 min coding + 30 min questions

Day 3: Production scenario — 45 min architecture + 60 min troubleshooting + 30 min questions

Day 4: Coding — 2 timed problems + tests + complexity analysis

Day 5: Interview questions — 25 rapid-fire + 5 senior scenario answers

Day 6: System design — One 45–60 minute design + trade-off review

Day 7: Mock + revision — 60 minute mock + error log + spaced repetition

# 500+ Interview Question Bank

## C# Fundamentals & OOP

1\. What is the difference between value types and reference types?

2\. Explain stack vs heap in practical .NET terms.

3\. What is boxing and unboxing and how can it affect performance?

4\. var vs dynamic vs object?

5\. const vs readonly vs static readonly?

6\. What does immutability mean in C#?

7\. Why are strings immutable?

8\. When would you use StringBuilder?

9\. Equals vs ReferenceEquals vs ==?

10\. Why must GetHashCode agree with Equals?

11\. What is IEquatable&lt;T&gt;?

12\. Interface vs abstract class?

13\. Can an abstract class have a constructor?

14\. Can an interface contain implementation?

15\. Composition vs inheritance?

16\. Explain encapsulation with a production example.

17\. Explain polymorphism with a payment example.

18\. Overloading vs overriding vs hiding?

19\. virtual vs abstract vs sealed?

20\. What does the sealed keyword do?

21\. What are access modifiers?

22\. private protected vs protected internal?

23\. Static class limitations?

24\. What is dependency in C#?

25\. What is dependency inversion?

26\. Explain SOLID in practical terms.

27\. Open/Closed Principle example?

28\. Liskov Substitution Principle example?

29\. Interface Segregation example?

30\. Dependency Inversion Principle example?

31\. Why prefer small interfaces?

32\. What are nullable reference types?

33\. What does the null-forgiving ! operator do?

34\. Nullable value type vs nullable reference type?

35\. Pattern matching examples?

36\. switch expression vs switch statement?

37\. record vs class?

38\. record struct vs struct?

39\. init-only setters?

40\. required members?

41\. readonly struct?

42\. ref readonly?

43\. ref/out/in differences?

44\. params keyword?

45\. named and optional arguments?

46\. Tuple vs custom type?

47\. Anonymous type limitations?

48\. Extension methods and their trade-offs?

49\. Generic constraints?

50\. Why use generics?

51\. Covariance and contravariance?

52\. Delegate vs interface?

53\. Action vs Func vs Predicate?

54\. Events vs delegates?

55\. Can an event be invoked outside its declaring type?

56\. Custom event accessors?

57\. Exception filters?

58\. throw vs throw ex?

59\. Custom exceptions: when are they justified?

60\. Should exceptions be used for normal control flow?

61\. Global exception handling strategy?

62\. IDisposable and using?

63\. IAsyncDisposable and await using?

64\. Finalizer vs Dispose?

65\. Safe resource cleanup pattern?

66\. Why can finalizers hurt performance?

## Advanced C# / LINQ / Memory

1\. What is deferred execution in LINQ?

2\. Deferred vs immediate execution?

3\. ToList vs ToArray vs ToLookup?

4\. IEnumerable vs IQueryable?

5\. How can LINQ cause multiple database queries?

6\. First vs FirstOrDefault vs Single vs SingleOrDefault?

7\. Any vs Count() > 0?

8\. Select vs SelectMany?

9\. GroupBy performance concerns?

10\. Expression tree vs delegate?

11\. Where does an IQueryable expression execute?

12\. What causes client-side evaluation?

13\. How would you optimize a slow LINQ query?

14\. What is yield return?

15\. Iterator state machine concept?

16\. Compiler-generated state machines for async?

17\. What happens when async/await is compiled?

18\. Task vs ValueTask?

19\. When can ValueTask make things worse?

20\. ConfigureAwait and when it matters?

21\. CancellationToken best practices?

22\. Task.Run for I/O-bound work: good or bad?

23\. CPU-bound vs I/O-bound work?

24\. Thread vs Task?

25\. ThreadPool starvation?

26\. SynchronizationContext?

27\. Deadlock with async/await?

28\. Why avoid .Result and .Wait()?

29\. Parallel.ForEach vs Task.WhenAll?

30\. When is parallelism harmful?

31\. SemaphoreSlim use case?

32\. lock vs Monitor?

33\. Interlocked use cases?

34\. ConcurrentDictionary guarantees?

35\. ConcurrentQueue use case?

36\. Producer/consumer pattern?

37\. Channels in .NET?

38\. Span&lt;T&gt;?

39\. Memory&lt;T&gt;?

40\. ref struct?

41\. Why can't ref struct be boxed?

42\. stackalloc?

43\. ArrayPool&lt;T&gt;?

44\. ObjectPool&lt;T&gt;?

45\. GC generations?

46\. Gen 0 vs Gen 1 vs Gen 2?

47\. Large Object Heap?

48\. Server GC vs Workstation GC?

49\. Allocation pressure?

50\. How do you diagnose a memory leak in managed code?

51\. Can managed .NET applications leak memory?

52\. Event handlers and memory leaks?

53\. Closure capture pitfalls?

54\. Local functions vs lambdas?

55\. Source generators?

56\. Reflection performance trade-offs?

57\. Attributes and reflection?

58\. CallerMemberName and related caller attributes?

59\. Unsafe code: when is it justified?

## ASP.NET Core / Web API

1\. What is the ASP.NET Core request pipeline?

2\. What is middleware?

3\. How does middleware ordering affect behavior?

4\. Use vs Run vs Map?

5\. How does endpoint routing work?

6\. Kestrel vs IIS?

7\. In-process vs out-of-process hosting?

8\. Controller vs Minimal API?

9\. Model binding?

10\. Model validation?

11\. ProblemDetails?

12\. Global exception middleware?

13\. Action filters vs middleware?

14\. Resource/action/result filters?

15\. Dependency injection in ASP.NET Core?

16\. Singleton vs Scoped vs Transient?

17\. What is a captive dependency?

18\. Why is DbContext typically scoped?

19\. How do you avoid service locator anti-pattern?

20\. IOptions vs IOptionsSnapshot vs IOptionsMonitor?

21\. Configuration provider precedence?

22\. appsettings.json vs environment variables?

23\. Secrets management best practice?

24\. User Secrets purpose?

25\. Key Vault integration pattern?

26\. Structured logging?

27\. Correlation ID?

28\. Distributed tracing?

29\. Health checks?

30\. Liveness vs readiness?

31\. Rate limiting in ASP.NET Core?

32\. Response caching vs output caching?

33\. Response compression?

34\. CORS?

35\. CSRF?

36\. XSS?

37\. SQL injection prevention?

38\. API versioning strategies?

39\. REST constraints?

40\. PUT vs PATCH?

41\. POST idempotency?

42\. What makes an operation idempotent?

43\. Pagination approaches?

44\. Offset vs cursor pagination?

45\. Filtering/sorting API design?

46\. HTTP 401 vs 403?

47\. 200 vs 201 vs 202 vs 204?

48\. 400 vs 422?

49\. 409 Conflict use case?

50\. 429 handling?

51\. 502 vs 503?

52\. API gateway responsibilities?

53\. Backend-for-Frontend pattern?

54\. OpenAPI/Swagger?

55\. Problem with exposing internal exceptions?

56\. How do you handle validation errors consistently?

57\. How do you implement request timeouts?

58\. How do you propagate cancellation to downstream calls?

59\. HttpClientFactory and why it exists?

60\. Named vs typed HttpClient?

61\. Polly/resilience concepts?

62\. Retry storms?

63\. Exponential backoff with jitter?

64\. Circuit breaker?

65\. Bulkhead isolation?

66\. How would you protect an API from a slow dependency?

## EF Core / Dapper / Data Access

1\. What is DbContext?

2\. Why is DbContext not thread-safe?

3\. Change tracking?

4\. AsNoTracking?

5\. When should you use AsNoTrackingWithIdentityResolution?

6\. Tracking vs no-tracking trade-off?

7\. Eager vs explicit vs lazy loading?

8\. What is the N+1 problem?

9\. How do projections improve performance?

10\. Include vs projection?

11\. Split queries?

12\. Cartesian explosion?

13\. EF Core migrations?

14\. Code-first vs database-first?

15\. Fluent API vs annotations?

16\. Shadow properties?

17\. Owned/entity types?

18\. Value converters?

19\. Concurrency tokens?

20\. Optimistic concurrency?

21\. Transaction handling?

22\. Execution strategy and transient failures?

23\. DbContext lifetime?

24\. Compiled queries?

25\. Raw SQL in EF Core?

26\. How do you prevent SQL injection with raw SQL?

27\. EF Core interceptors?

28\. How do you inspect generated SQL?

29\. How do you optimize an EF query?

30\. When should you use Dapper?

31\. Dapper advantages/disadvantages?

32\. Dapper parameterization?

33\. Dapper multi-mapping?

34\. Dapper transactions?

35\. Repository pattern with Dapper?

36\. Unit of Work with Dapper?

37\. Should you wrap EF Core in a repository?

38\. Connection pooling?

39\. How do you manage DB connections safely?

40\. Stored procedures: when useful?

41\. ORM vs micro-ORM?

42\. How would you migrate from EF to Dapper selectively?

43\. How do you handle large result sets?

44\. Streaming query results?

45\. Bulk insert strategies?

46\. How do you avoid loading unnecessary columns?

47\. How do you implement optimistic concurrency in an API?

48\. How do you handle unique constraint violations?

49\. How do you map database errors to API responses?

50\. How do you test repositories?

51\. Integration tests with a real database?

52\. Testcontainers concept?

53\. Transaction isolation levels?

54\. Read committed vs snapshot?

55\. Serializable trade-offs?

56\. Deadlocks and retry strategy?

57\. Database connection exhaustion?

## SQL Server

1\. INNER JOIN vs LEFT JOIN?

2\. WHERE vs HAVING?

3\. UNION vs UNION ALL?

4\. EXISTS vs IN?

5\. CTE vs temp table?

6\. Recursive CTE use case?

7\. ROW_NUMBER vs RANK vs DENSE_RANK?

8\. LEAD/LAG use cases?

9\. CROSS APPLY vs OUTER APPLY?

10\. Clustered vs nonclustered index?

11\. Composite index column order?

12\. Covering index?

13\. Included columns?

14\. Filtered index?

15\. Index fragmentation?

16\. Statistics and cardinality estimation?

17\. Index seek vs scan?

18\. Key lookup?

19\. Execution plan reading?

20\. Why can an index be ignored?

21\. SARGability?

22\. Functions on indexed columns?

23\. Parameter sniffing?

24\. Query hints: when not to use them?

25\. Deadlock detection?

26\. Blocking vs deadlock?

27\. Lock escalation?

28\. Isolation levels?

29\. Snapshot isolation?

30\. Row versioning?

31\. ACID?

32\. Normalization?

33\. Denormalization?

34\. Surrogate vs natural key?

35\. Primary key vs unique constraint?

36\. Foreign key benefits?

37\. Check constraints?

38\. Computed columns?

39\. Identity vs sequence?

40\. MERGE concerns?

41\. Upsert strategies?

42\. Stored procedure pros/cons?

43\. Table variables vs temp tables?

44\. Partitioning?

45\. Read replicas?

46\. High availability options?

47\. Backup vs point-in-time recovery?

48\. How do you troubleshoot a 30-second query?

49\. How do you find missing indexes?

50\. How do you validate that an index helped?

51\. How do you reduce logical reads?

52\. How do you process millions of rows safely?

53\. Keyset pagination in SQL?

54\. How do you avoid duplicate rows from joins?

55\. How do you find duplicate records?

56\. Top N per group query?

57\. Second-highest salary query?

58\. Running total query?

59\. Detect gaps and islands?

60\. Delete duplicates safely?

61\. Updatable CTE?

62\. Window function performance?

## Architecture / SOLID / Patterns

1\. Explain SOLID with real examples.

2\. Dependency inversion vs dependency injection?

3\. Clean Architecture layers?

4\. What belongs in the domain layer?

5\. Why keep business rules out of controllers?

6\. Application service vs domain service?

7\. DTO vs domain entity?

8\. Mapping strategies?

9\. Repository pattern trade-offs?

10\. Unit of Work trade-offs?

11\. CQRS: when useful?

12\. When is CQRS overengineering?

13\. Mediator pattern?

14\. Command vs query?

15\. Factory pattern use case?

16\. Abstract Factory use case?

17\. Builder pattern use case?

18\. Strategy pattern use case?

19\. Decorator pattern vs inheritance?

20\. Adapter pattern?

21\. Facade pattern?

22\. Proxy pattern?

23\. Observer pattern?

24\. Chain of Responsibility?

25\. Template Method?

26\. Specification pattern?

27\. State pattern?

28\. Null Object pattern?

29\. Anti-corruption layer?

30\. Dependency boundaries?

31\. How do you prevent a shared-kernel becoming a monolith?

32\. How do you decide service boundaries?

33\. How do you evolve an API contract?

34\. Backward compatibility?

35\. Feature flags?

36\. Strangler Fig pattern?

37\. Modular monolith vs microservices?

38\. When should a monolith remain a monolith?

39\. Distributed transaction alternatives?

40\. Saga orchestration vs choreography?

41\. Outbox pattern?

42\. Idempotency key design?

43\. Event-driven architecture?

44\. Domain events vs integration events?

45\. At-least-once delivery implications?

46\. Exactly-once myth?

47\. Consistency vs availability trade-off?

48\. Architecture decision record?

49\. How do you communicate trade-offs to stakeholders?

50\. How do you handle technical debt?

51\. How do you review a proposed architecture?

52\. How do you identify overengineering?

53\. How do you design for failure?

54\. How do you design a system for 10x growth?

## Microservices / RabbitMQ / gRPC

1\. What makes a good microservice boundary?

2\. Database per service?

3\. Shared database problems?

4\. Synchronous vs asynchronous communication?

5\. REST vs messaging?

6\. RabbitMQ exchange types?

7\. Direct exchange?

8\. Topic exchange?

9\. Fanout exchange?

10\. Routing key?

11\. Queue durability?

12\. Message acknowledgement?

13\. Manual vs automatic ack?

14\. Prefetch?

15\. Dead-letter exchange?

16\. Retry queue?

17\. Poison message?

18\. Message ordering?

19\. Duplicate delivery?

20\. Idempotent consumer?

21\. Consumer scaling?

22\. Backpressure?

23\. Publisher confirms?

24\. Transactional messaging?

25\. Outbox pattern with RabbitMQ?

26\. Event schema evolution?

27\. Contract compatibility?

28\. Correlation ID?

29\. Distributed tracing across messages?

30\. gRPC vs REST?

31\. Why HTTP/2 for gRPC?

32\. Protocol Buffers benefits?

33\. Unary vs streaming gRPC?

34\. Bidirectional streaming?

35\. gRPC interceptors?

36\. gRPC deadlines?

37\. gRPC cancellation?

38\. gRPC authentication?

39\. API gateway and gRPC?

40\. When not to use gRPC?

41\. Saga choreography?

42\. Saga orchestration?

43\. Compensating transaction?

44\. Retry with idempotency?

45\. Circuit breaker around downstream services?

46\. Bulkhead?

47\. Timeout budgets?

48\. Service discovery?

49\. Load balancing?

50\. Distributed configuration?

51\. Centralized secrets?

52\. Observability requirements?

53\. Metrics vs logs vs traces?

54\. How do you debug a distributed failure?

55\. How do you guarantee an event is not lost?

56\. How do you handle a consumer that is slower than producers?

## Angular / React

1\. Angular component lifecycle?

2\. Standalone components?

3\. Angular DI?

4\. Angular change detection?

5\. OnPush strategy?

6\. Signals?

7\. Observable vs Promise?

8\. Subject vs BehaviorSubject?

9\. ReplaySubject?

10\. RxJS switchMap vs mergeMap vs concatMap vs exhaustMap?

11\. Unsubscribe strategies?

12\. Angular HTTP interceptor?

13\. Route guard?

14\. Reactive forms?

15\. Form validation?

16\. Lazy loading?

17\. Angular state management options?

18\. How do you optimize a large Angular app?

19\. TrackBy purpose?

20\. Pure vs impure pipe?

21\. Angular security concerns?

22\. React component model?

23\. Props vs state?

24\. useState?

25\. useEffect pitfalls?

26\. useMemo vs useCallback?

27\. Context API trade-offs?

28\. Redux concepts?

29\. Server state vs client state?

30\. React Query/TanStack Query concept?

31\. Controlled vs uncontrolled forms?

32\. React key prop?

33\. Rendering and reconciliation?

34\. How do you avoid unnecessary re-renders?

35\. Authentication flow in SPA?

36\. Access token storage trade-offs?

37\. Refresh token strategy?

38\. CORS in SPA/API architecture?

39\. Frontend error handling?

40\. Global HTTP error handling?

41\. Pagination UX?

42\. Optimistic UI?

43\. Debouncing search?

44\. Accessibility basics?

45\. Frontend testing strategy?

46\. Component vs integration tests?

47\. Bundle size optimization?

48\. Code splitting?

49\. Web performance metrics?

50\. How should frontend and backend contracts evolve?

51\. How do you handle API version changes?

52\. How do you secure client-side routes?

## Azure / DevOps / Docker

1\. What is Azure App Service?

2\. App Service vs Container Apps?

3\. App Service vs AKS?

4\. When would you use Azure Functions?

5\. Consumption vs premium/serverless concepts?

6\. Azure SQL vs Cosmos DB?

7\. Blob storage tiers?

8\. Managed identity?

9\. Key Vault?

10\. Azure Service Bus vs Event Grid vs Event Hubs?

11\. Redis use cases?

12\. Application Insights?

13\. Log Analytics?

14\. Azure Monitor?

15\. Distributed tracing in Azure?

16\. Deployment slots?

17\. Blue/green deployment?

18\. Canary deployment?

19\. Rollback strategy?

20\. Azure DevOps YAML pipeline structure?

21\. Stages vs jobs vs steps?

22\. Build artifact?

23\. Environment approvals?

24\. Service connections?

25\. Secret variables?

26\. Variable groups?

27\. Pipeline templates?

28\. PR validation?

29\. Branch policies?

30\. Git rebase vs merge?

31\. Trunk-based development?

32\. GitFlow trade-offs?

33\. Docker image vs container?

34\. Multi-stage Docker build?

35\. Why run as non-root?

36\. Docker networking?

37\. Volumes?

38\. Compose?

39\. Image size optimization?

40\. Container health checks?

41\. Kubernetes pod concept?

42\. Deployment vs StatefulSet?

43\. ConfigMap vs Secret?

44\. Readiness vs liveness probes?

45\. Horizontal Pod Autoscaler?

46\. Infrastructure as Code concept?

47\. Bicep vs Terraform?

48\. Immutable infrastructure?

49\. Environment drift?

50\. CI vs CD?

51\. Continuous delivery vs deployment?

52\. Security scanning in CI/CD?

53\. Dependency scanning?

54\. Container scanning?

55\. Supply-chain security?

56\. Zero-downtime deployment?

57\. How do you diagnose a failed deployment?

58\. How do you roll back safely?

59\. How do you optimize cloud cost?

## System Design / Performance

1\. Design a payment processing system.

2\. Design an order management system.

3\. Design a travel itinerary platform.

4\. Design a notification platform.

5\. Design a file processing system.

6\. Design a URL shortener.

7\. Design a rate limiter.

8\. Design an API gateway.

9\. Design a distributed cache.

10\. Design an audit logging system.

11\. Design a job scheduler.

12\. Design a webhook delivery platform.

13\. Design an email ingestion/quotation system.

14\. Design a fraud/risk analysis service.

15\. Design an EFT processing workflow.

16\. Design a real-time dashboard.

17\. Design a document search system.

18\. Design a multi-tenant SaaS platform.

19\. Design a feature flag platform.

20\. Design a CI/CD failure analysis platform.

21\. How do you estimate capacity?

22\. How do you choose SQL vs NoSQL?

23\. How do you partition data?

24\. Horizontal vs vertical scaling?

25\. Stateless service benefits?

26\. Load balancing strategies?

27\. Cache-aside vs write-through?

28\. Cache invalidation strategies?

29\. Cache stampede?

30\. Distributed lock?

31\. Rate limiting algorithms?

32\. Token bucket vs leaky bucket?

33\. Queue-based load leveling?

34\. Backpressure?

35\. Eventual consistency?

36\. CAP theorem?

37\. PACELC concept?

38\. RPO vs RTO?

39\. Availability calculation?

40\. Bulkhead isolation?

41\. Graceful degradation?

42\. Disaster recovery?

43\. Multi-region design?

44\. Active-active vs active-passive?

45\. Hot vs warm vs cold standby?

46\. How do you design observability?

47\. How do you trace one user request across services?

48\. How do you investigate API latency?

49\. How do you investigate CPU saturation?

50\. How do you investigate memory growth?

51\. How do you diagnose thread pool starvation?

52\. How do you diagnose database connection exhaustion?

53\. How do you handle a downstream dependency outage?

54\. How do you prevent cascading failures?

## Python / LLM / RAG / Agentic AI

1\. Python list vs tuple?

2\. Dictionary internals concept?

3\. Set use cases?

4\. Mutable vs immutable?

5\. Shallow vs deep copy?

6\. Python generators?

7\. Decorators?

8\. Context managers?

9\. Iterators vs iterables?

10\. Type hints?

11\. dataclass?

12\. Exception handling?

13\. asyncio event loop?

14\. async vs threading vs multiprocessing?

15\. FastAPI dependency injection?

16\. Pydantic validation?

17\. Async endpoint design?

18\. pytest fixtures?

19\. Mocking external APIs?

20\. LLM vs traditional ML?

21\. Token concept?

22\. Context window?

23\. Temperature?

24\. Top-p?

25\. Structured output?

26\. Function/tool calling?

27\. Streaming responses?

28\. Prompt injection?

29\. Hallucination?

30\. Grounding?

31\. LLM evaluation?

32\. Latency/cost trade-offs?

33\. Embedding concept?

34\. Vector similarity?

35\. Cosine similarity?

36\. Chunking strategies?

37\. Overlap?

38\. Metadata filtering?

39\. Hybrid search?

40\. Reranking?

41\. RAG failure modes?

42\. How do you evaluate retrieval quality?

43\. How do you cite sources in RAG?

44\. Vector DB vs relational DB?

45\. Agent vs chatbot?

46\. Tool calling loop?

47\. Agent state?

48\. Memory types?

49\. Planning?

50\. Sub-agent architecture?

51\. Human-in-the-loop?

52\. Guardrails?

53\. Agent observability?

54\. MCP concept?

55\. How do you secure tools?

56\. How do you prevent an agent from taking unsafe actions?

57\. How do you handle tool failure?

58\. How do you evaluate an agent?

59\. How do you reduce hallucinations?

60\. How do you control LLM cost?

61\. How do you protect sensitive data in AI systems?

## Leadership / Behavioral / Ownership

1\. Tell me about yourself.

2\. Why are you looking for a change?

3\. Why should we hire you?

4\. What is your strongest technical skill?

5\. What is one weakness you are improving?

6\. Describe a difficult production incident.

7\. Describe a performance improvement you led.

8\. Describe a major migration.

9\. Describe a technology you introduced.

10\. Describe a disagreement with an architect.

11\. Describe a disagreement with a teammate.

12\. Tell me about a failed project decision.

13\. Tell me about a time you made a mistake.

14\. Tell me about a customer escalation.

15\. Tell me about mentoring a developer.

16\. How do you conduct code reviews?

17\. How do you enforce quality without slowing delivery?

18\. How do you prioritize technical debt?

19\. How do you estimate work?

20\. How do you handle changing requirements?

21\. How do you work under a tight deadline?

22\. How do you delegate?

23\. How do you lead without authority?

24\. How do you handle an underperforming team member?

25\. How do you onboard engineers?

26\. How do you choose between build and buy?

27\. How do you evaluate a new technology?

28\. How do you convince infrastructure teams?

29\. How do you handle production ownership?

30\. How do you communicate risk to management?

31\. How do you measure engineering success?

32\. What are your top three KPIs?

33\. Describe an end-to-end ownership example.

34\. Describe a customer-impacting bug.

35\. Describe a security issue you addressed.

36\. Describe a reliability improvement.

37\. Describe a cost optimization.

38\. Describe a time you automated manual work.

39\. Describe a time you learned a new technology quickly.

40\. Describe an example of entrepreneurship.

41\. Describe how you handled ambiguity.

42\. How do you mentor senior engineers?

43\. How do you resolve team conflict?

44\. How do you run architecture reviews?

45\. How do you document decisions?

46\. How do you handle disagreement after a decision?

47\. What would your manager say about you?

48\. What would your teammates say about you?

49\. Where do you want to grow technically?

50\. Why move toward AI/agentic engineering?

51\. How do you keep your skills current?

52\. How do you balance hands-on coding and leadership?

# Coding Exercise Library — 60 Problems

1\. Reverse a string without library helpers; discuss Unicode considerations.

2\. Find first non-repeating character.

3\. Determine whether two strings are anagrams.

4\. Implement an LRU cache.

5\. Implement a thread-safe singleton and explain why you might avoid it.

6\. Implement a generic retry policy with exponential backoff.

7\. Implement bounded async concurrency using SemaphoreSlim.

8\. Implement producer/consumer using Channel&lt;T&gt;.

9\. Process 100,000 records asynchronously with cancellation and backpressure.

10\. Implement a timeout wrapper around an async operation.

11\. Write a LINQ query for top 3 orders per customer.

12\. Remove duplicates while preserving order.

13\. Group transactions by customer and calculate rolling totals.

14\. Convert nested objects into a flat dictionary.

15\. Implement pagination over IQueryable correctly.

16\. Create a custom middleware for correlation IDs.

17\. Build global exception handling with ProblemDetails.

18\. Build a typed HttpClient with timeout and retry.

19\. Implement policy-based authorization for an admin endpoint.

20\. Create an API with cursor pagination.

21\. Implement idempotency for POST /payments.

22\. Implement optimistic concurrency using a row version.

23\. Write EF Core query projection for an order summary.

24\. Fix an N+1 EF Core query.

25\. Implement Dapper repository with transaction.

26\. Write SQL for top N products by category.

27\. Write SQL for duplicate detection and safe deletion.

28\. Write SQL for gaps-and-islands.

29\. Write SQL for running total and moving average.

30\. Write SQL for keyset pagination.

31\. Design indexes for a given slow query.

32\. Implement Strategy pattern for payment methods.

33\. Implement Decorator pattern for notification logging/retry.

34\. Implement Factory for document exporters.

35\. Implement Chain of Responsibility for risk checks.

36\. Implement Outbox persistence workflow.

37\. Implement an idempotent RabbitMQ consumer.

38\. Implement retry + DLQ handling.

39\. Implement gRPC unary service.

40\. Implement gRPC server streaming.

41\. Build REST-to-gRPC adapter.

42\. Create Angular reactive form with validation.

43\. Create Angular HTTP interceptor for auth/correlation IDs.

44\. Implement RxJS typeahead with switchMap and debounce.

45\. Build React order list with pagination.

46\. Implement React error boundary.

47\. Build Dockerfile for ASP.NET Core multi-stage build.

48\. Create Azure DevOps YAML build/test/publish pipeline.

49\. Create a deployment pipeline with environment approval.

50\. Build FastAPI CRUD endpoint using Pydantic.

51\. Implement Python async API client.

52\. Build an LLM tool-calling assistant.

53\. Return structured JSON from an LLM call and validate it.

54\. Implement document chunking with overlap.

55\. Implement cosine similarity search over a small vector store.

56\. Build a simple RAG pipeline.

57\. Build an agent with two tools and tool-result state.

58\. Build an Azure DevOps pipeline failure-analysis workflow.

59\. Build a Jira defect creation tool with duplicate detection.

60\. Add evaluation tests for an AI/RAG system.

# System Design Practice — 16 Deep Dives

## Payment Platform

Requirements → APIs → idempotency → payment provider adapters → outbox → queue → reconciliation → audit → security → observability → DR.

## Travel Management

Users → trips → itinerary → bookings → suppliers → payments → documents → notifications; discuss multi-tenancy and consistency.

## Order Management

Catalog → order → inventory reservation → payment → fulfillment; use Saga/outbox and idempotent commands.

## Notification Platform

Email/SMS/push providers behind Strategy; queue, retry, DLQ, preferences, throttling and delivery tracking.

## File Processing

Blob upload → event/queue → worker → processing status → result storage → notification; discuss poison files and retries.

## Webhook Platform

Subscription management → signed delivery → retry schedule → DLQ → replay → idempotency → rate limits.

## Risk Analysis

Request → feature retrieval → external risk provider/ML model → decision → audit; discuss timeout/fallback.

## EFT Processing

Request creation → validation → file generation → bank submission → response ingestion → reconciliation → exception workflow.

## Multi-tenant SaaS

Tenant isolation, tenant-aware authorization, database strategy, quotas, noisy-neighbor control and tenant configuration.

## CI/CD Failure Agent

Pipeline logs → classifier → test/code retrieval → RAG → root-cause agent → human approval → Jira defect.

## Real-time Dashboard

Event ingestion → stream/queue → aggregation → cache → WebSocket/SSE → historical store.

## Document Knowledge System

Ingestion → OCR/parser → chunking → embeddings → vector/hybrid retrieval → reranking → grounded answer.

## Rate Limiter

Token bucket/distributed Redis design; discuss clock, atomicity, fail-open vs fail-closed.

## Audit Platform

Append-only events, immutable audit records, retention, query model, compliance, PII minimization.

## Job Scheduler

Scheduling API, durable jobs, worker leasing, retries, concurrency, misfire handling, observability.

## AI Agent Platform

Agent runtime, tool registry, memory/state, RAG, policy guardrails, approvals, evaluation and cost controls.

# Senior-Level Answer Frameworks

## Concept question

Definition → why it exists → internals → practical example → trade-off → when not to use.

## Architecture question

Clarify requirements → functional/non-functional → estimate scale → components → data → APIs/events → failure modes → security → observability → trade-offs.

## Performance question

Measure first → isolate bottleneck → form hypothesis → change one variable → benchmark → monitor → prevent regression.

## Production incident

Impact → timeline → detection → containment → root cause → fix → verification → prevention → measurable result.

## Behavioral STAR

Situation → Task → Actions personally taken → Result with metrics → Lesson.

## Technology choice

Requirements → options → decision criteria → selected approach → alternatives rejected → operational impact.

## AI/RAG question

Data → ingestion → retrieval → generation → grounding → evaluation → safety → latency/cost.

# Model Senior Answers — 25 High-Value Questions

## Dependency Injection lifetimes

Transient creates a new instance per resolution; scoped normally creates one instance per request/scope; singleton lives for the application lifetime. I choose based on state and thread-safety rather than performance assumptions. DbContext is commonly scoped because it represents a unit of work and is not thread-safe. A key senior concern is avoiding a singleton capturing a scoped service.

## Task vs ValueTask

Task is the default abstraction for asynchronous operations. ValueTask can avoid an allocation when an operation frequently completes synchronously, but it has usage constraints and can add complexity. I use Task by default and benchmark before introducing ValueTask in a hot path.

## IEnumerable vs IQueryable

IEnumerable represents in-memory enumeration and delegates execute locally. IQueryable builds an expression tree that a provider such as EF Core can translate to SQL. A senior concern is accidentally materializing early with ToList and then filtering in memory.

## EF Core N+1

N+1 occurs when one query loads parents and then a separate query runs for each parent. I detect it through logs/profiling and fix it using projection, Include where appropriate, batching or explicit queries. I avoid blindly adding Include because it can create large joins/cartesian explosion.

## Repository with EF Core

I don't automatically add repositories around EF Core. DbContext already provides unit-of-work/change tracking behavior. A repository can still be useful when it represents a meaningful domain boundary, hides a complex persistence model, or supports a technology boundary. I avoid abstractions that simply duplicate DbSet methods.

## Idempotent payment API

I require an idempotency key from the client, persist the key with the operation result/status, and enforce uniqueness transactionally. Repeated requests return the original result rather than creating a second payment. External provider calls also need provider-side idempotency where supported.

## RabbitMQ duplicate messages

I assume at-least-once delivery and make consumers idempotent. The consumer records a processed event/message ID or uses a business idempotency key under a unique constraint. Acknowledgement happens only after durable processing, with retry/DLQ for failures.

## Outbox pattern

The service writes the business state change and an outbox event in the same database transaction. A background publisher reads unsent outbox rows and publishes them, then marks them sent. This avoids the dual-write problem where the database commits but event publishing fails.

## Circuit breaker

A circuit breaker prevents repeatedly calling an unhealthy dependency. After enough failures it opens, failing fast; after a cool-down it enters half-open to test recovery. It should be combined with timeouts and bounded retries, otherwise it can merely move the overload elsewhere.

## REST vs gRPC

REST is usually the better external/public API choice because it is broadly interoperable and HTTP semantics are familiar. gRPC is attractive for internal low-latency service-to-service communication, strong contracts and streaming. The choice depends on clients, network boundaries, observability, compatibility and operational constraints.

## Kestrel vs IIS

Kestrel is the ASP.NET Core web server. IIS can act as a reverse proxy/front-end on Windows and provides integration with Windows hosting capabilities. In modern deployments Kestrel commonly runs behind a reverse proxy/load balancer, while the exact topology depends on platform requirements.

## JWT authentication

The client obtains an access token from an identity provider. The API validates issuer, audience, signature and expiry, then maps claims to authorization policies. I keep access tokens short-lived, avoid embedding unnecessary sensitive data, and use secure token acquisition/refresh patterns.

## Authentication vs authorization

Authentication answers who the caller is; authorization answers what that identity is allowed to do. In ASP.NET Core I separate authentication middleware/token validation from policy/role/claim authorization.

## SQL query slow

I first measure: execution plan, duration, CPU, logical reads, waits and row counts. Then I look for scans, missing/poor indexes, non-SARGable predicates, bad cardinality estimates, parameter sniffing, blocking and excessive result sets. I make a targeted change and compare before/after metrics.

## Thread pool starvation

Symptoms include rising request latency while CPU may not be saturated. Common causes are blocking calls such as Result/Wait, synchronous I/O or excessive work queued to the pool. I inspect runtime counters/traces and remove blocking, make I/O asynchronous, and control concurrency.

## API resilience

For each downstream dependency I define timeout, retry policy, circuit breaker and fallback behavior based on business semantics. Retries use exponential backoff with jitter and only retry transient/idempotent operations. I also enforce an overall request deadline.

## Clean Architecture

I keep business rules independent of frameworks and infrastructure. Presentation depends on application contracts; infrastructure implements application abstractions. The goal is testability and controlled coupling, not creating layers for their own sake.

## Microservices vs monolith

I choose microservices when independent scaling, deployment, team ownership or domain boundaries justify the operational cost. Otherwise a modular monolith can be simpler and safer. I look at organizational boundaries and operational maturity as much as technical decomposition.

## Caching

Cache-aside is a common pattern: read cache first, load from source on miss, then populate. I define TTL, invalidation, consistency expectations and stampede protection. I never treat cache as the only source of truth unless the system explicitly supports that model.

## RAG

RAG retrieves relevant external knowledge and supplies it as context to an LLM. Quality depends heavily on ingestion, chunking, embeddings, retrieval filters and reranking. I evaluate retrieval separately from generation and include source attribution where trust matters.

## Agent vs chatbot

A chatbot primarily generates responses. An agent can decide to invoke tools, inspect results, maintain state and execute a multi-step workflow. For production agents I constrain tool permissions, validate inputs/outputs, log tool calls and add human approval for high-impact actions.

## Prompt injection

I treat retrieved documents and user content as untrusted input. System/developer policies remain authoritative; tools use least privilege; tool parameters are validated; sensitive operations require approval; and outputs are filtered. RAG content should never automatically gain authority over tool policy.

## Technical leadership

My role is to make good decisions repeatable: clarify requirements, document trade-offs, establish coding/testing standards, mentor engineers, remove blockers and stay accountable for production outcomes. I remain hands-on where it provides leverage rather than becoming a bottleneck.

## Production incident

I separate containment from root-cause analysis. First protect customers and stabilize the system, then preserve evidence and identify the failure mechanism. After the fix I add monitoring, tests, guardrails or process changes so the same class of incident becomes less likely.

# Final 7-Day Mock Interview Sprint

Day 1: 90-min C#/.NET technical interview + 2 coding problems + review mistakes.

Day 2: 60-min SQL/EF/Dapper + 45-min API/security + 30-min coding.

Day 3: 60-min Azure/DevOps/Docker + 60-min microservices/messaging.

Day 4: 60-min Angular/React + 60-min system design.

Day 5: 45-min Python + 45-min LLM/RAG/agents + 45-min AI coding.

Day 6: 75-min full system design + 45-min leadership/STAR.

Day 7: Full 90–120 minute mock: intro → coding → architecture → debugging → AI → behavioral.

# Interview Scorecard

| Area         | Target | Warning sign                         | Fix                             |
| ------------ | ------ | ------------------------------------ | ------------------------------- |
| C#/.NET      | 9/10   | Can define but not explain internals | Write + explain 10 examples     |
| SQL/Data     | 8/10   | Cannot diagnose slow query           | Execution-plan drills           |
| Architecture | 8/10   | Jumps to microservices               | Requirements + trade-offs first |
| Azure/DevOps | 8/10   | Only service-name knowledge          | Deploy one complete system      |
| Frontend     | 7/10   | Framework trivia only                | Build authenticated dashboard   |
| AI/Python    | 7/10   | Only theoretical LLM knowledge       | Build RAG + agent project       |
| Leadership   | 9/10   | Generic STAR stories                 | Prepare metric-based stories    |

Question bank total: 698 questions. Coding exercises: 60. System-design deep dives: 16.

Recommended rule: do not memorize the model answers word-for-word. Use them as structure, then replace examples with your own production experience and measurable outcomes.