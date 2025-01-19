<p align="center">
    <img height="170"src="./img/echo-simple-icon-black.svg">
</p>

# Distributed Async Await

This **reading list** explores the foundational literature that informs the design and development of Distributed Async Await.

---

## Events vs. Threads

### [On the Duality of Operating System Structures](https://dl.acm.org/doi/pdf/10.1145/850657.850658)
* **Author(s):** Hugh C. Lauer, Roger M. Needham
* **Published:** 1979
* **Summary:** This paper discusses the duality between procedure-based systems and event-based systems, illustrating how both paradigms can model equivalent structures.

### [Why Threads Are a Bad Idea (for Most Purposes)](https://sites.cc.gatech.edu/classes/AY2010/cs4210_fall/papers/ousterhout-threads.pdf)
* **Author(s):** John Ousterhout
* **Published:** 1995
* **Summary:** The author critiques thread-based implementations for their subpar efficiency compared to event-based implementations.

### [Why Events Are a Bad Idea (for High-Concurrency Servers)](https://web.stanford.edu/class/cs240e/papers/threads-hotos-2003.pdf)
* **Author(s):** Rob von Behren, Jeremy Condit, and Eric Brewer
* **Published:** 2003
* **Summary:** The authors critique event-based implementations for their subpar developer experience compared to thread-based implementations.

---

## Sequential Programming Models & Event-Driven Execution Models

### [Cooperative Task Management without Manual Stack Management](https://dl.acm.org/doi/10.1145/99998.100020)
* **Author(s):** Atul Adya, Jon Howell, Marvin Theimer, William J. Bolosky, John R. Douceur
* **Published:** 2002
* **Summary:** This paper is a foundational contribution to understanding how sequential programming model can be implemented on top of a event-driven execution model. Additionally, the paper introduces the notion of *stack ripping* as the primary reason for the subpar developer experience of event-based implementations.

### [A Language-Based Approach to Unifying Events and Threads](https://www.cis.upenn.edu/~stevez/papers/LZ06b.pdf)
* **Author(s):** Peng Li, Steve Zdancewic
* **Published:** 2006
* **Summary:** This paper presents a language-level implementation of a sequential programming model implemented on top of a event-driven execution model.

### [Combining Events And Threads For Scalable Network Services. Implementation And Evaluation Of Monadic, Application-level Concurrency Primitives](https://dl.acm.org/doi/10.1145/1273442.1250756)
* **Author(s):** Peng Li, Steve Zdancewic
* **Published:** 2007
* **Summary:** The authors evaluate monadic primitives for managing concurrency at the application level.

---

## Concurrent Systems

### [Revisiting Coroutines](https://dl.acm.org/doi/pdf/10.1145/1462166.1462167)
* **Author(s):** Ana Lucia de Moura, Roberto Ierusalimschy  
* **Published:** 2009  
* **Summary:** This paper classifies coroutines and provides a formal model using small-step operational semantics, offering insights into their use as an alternative to callbacks.

### [A Poor Man’s Concurrency Monad](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/A369E310ADAE4455020C918FC1D47958/S0956796899003342a.pdf/a-poor-mans-concurrency-monad.pdf)
* **Author(s):** Koen Claessen  
* **Published:** 1999  
* **Summary:** This paper presents an implementation of concurrency by defining atomic operations and continuations.

### [Semantics of Asynchronous JavaScript](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/08/asyncNodeSemantics.pdf)
* **Author(s):** Matthew C. Loring, Mark Marron, and Daan Leijen
* **Published:** 2017  
* **Summary:** This paper presents a comprehensive
formalization of the Node.js asynchronous execution model

### [A Model of Cooperative Threads](https://homepages.inf.ed.ac.uk/gdp/publications/Semantics_Cooperative_Threads_journal.pdf)
* **Author(s):** Martin Abadi, Gordon D. Plotkin  
* **Published:** 1998  
* **Summary:** This paper develops a model of concurrent imperative programming with threads, focusing on a small imperative language with cooperative threads that execute without interruption until they terminate or explicitly yield control.
---

## Distributed Systems

### [A Note on Distributed Computing](https://scholar.harvard.edu/files/waldo/files/waldo-94.pdf)
* **Author(s):** Jim Waldo, Geoff Wyant, Ann Wollrath, and Sam Kendall
* **Published:** 1994
* **Summary:** The authors argue that a distributed system is intrinsicly different from a non-distributes system

## Contributing
If you have suggestions for additional papers related to distributed async await, please open an issue or submit a pull request.

