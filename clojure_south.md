Understand / state your problem

Prefer simple, general purpose tools

Nicotine time: time to think (hammock)

Account for every detail

Write things down.  Do it again and again.

Bias for action: act precisely with direction. Take your time.

---

Share vocabulary to domain model

Loan Data: Just a map. No class. No object. No behaviour

Loan event: data about what happened

Persistent data structure: performance for giganstic data. bonus / easy parallelism

Flow

---

Dealing with legacy code

Defmethod: polymorphism

Schema contract for tests

Components to solve different providers

Remove business logic from the notification service. Nuconta, credit have their own business logic and just call notification service passing the template stored in the s3

Documentation: architecture decisions

Metrics and alerts: use logs for all the flows. Do we have all the metrics to understand if this will work?

Using edn for rollouts

---

Confident clojurist

Java is like brocolli,  it can be good for you. But it's disgusting

---

Event source

Fluxo de transferencia: pedido de transferencia gera uma retirada (balança correta?), e faz a transferencia de fato

Event tracing: qual ponto do fluxo deveria ter funcionado mas quebrou. Para debugging

Como lidar com Falhas

Transferencia falhou no banco central: reverter a retirada do balanço e mostrar erro pro cliente / rollback de eventos

Transferencia se inicia como pendente.

Request - redemption - transfer - state

Como calcular o saldo? Passar por todos os eventos de retiradas e depositos. E quando

Cache de saldo. Só muda cache quando tem deposito e retiradas.

---

Monolitos acoplados e que tem dificuldade de extender e modificar

Long onboarding for newcomers

Pure functions in the level of the system.

Domain model: pure

Application: calls pure functions

IO: side effects

---

Tests: confidence

Property based testing: all possible inputs

Run lot of testsYp

Spec:

- Validation: type validation
- Generator for the spec
- Generate outputs
- Generative testing is all about data.
