# System Design resources for Interview preparation

### Motivation: WHY I am making this repository?

```diff
As a beginner I wanted to learn how to design large scale distributed systems.

Prepare for the System Design interview.
```

As you might know that we need to have good understanding of various Computer Science Fundamentals involving **Distributed Systems, Computer Network, Operating System** along with good problem solving skills (**Data Structures and Algorithms**) for acing the interviews at top product based companies. 

Let's first learn **Basic Concepts**  for *designing higly scalable data intensive applications*.

- Caching 
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/caching.html) - gitbooks
  - [educative post](https://www.educative.io/courses/grokking-the-system-design-interview/3j6NnJrpp5p)
  - [medium article](https://medium.com/system-designing-interviews/system-design-chapter-4-caching-b59a4cf83f10)
  
- Data Partitioning 
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/sharding-or-data-partitioning.html) - gitbooks
  - [educative post](https://www.educative.io/courses/grokking-the-system-design-interview/mEN8lJXV1LA)
  - [ScienceDirect post](https://www.sciencedirect.com/topics/computer-science/data-partitioning) 

- Sharding
  - [medium article](https://medium.com/system-designing-interviews/system-design-chapter-2-sharding-484960c18f6) 
  - [Understanding Database Sharding](https://www.digitalocean.com/community/tutorials/understanding-database-sharding) - digital ocean

- Load Balancing
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/load-balancing.html) - gitbooks
  - [educative post](https://www.educative.io/courses/grokking-the-system-design-interview/3jEwl04BL7Q)
  - [medium article](https://medium.com/system-designing-interviews/system-design-chapter-3-load-balancing-e1c89148e37)

- Indexes
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/indexes.html) - gitbooks


- Proxies
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/proxies.html) - gitbooks

- Queues
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/queues.html) - gitbooks


- Redundancy and Replication
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/redundancy-and-replication.html) - gitbooks
  - [educative post](https://www.educative.io/courses/grokking-the-system-design-interview/xV1qvj6PKkJ)
  - [medium post](https://medium.com/baseds/redundancy-and-replication-duplicating-in-a-distributed-system-7ab4322d7378#:~:text=Both%20of%20them%20involve%20creating,all%20of%20its%20other%20copies.)
  

- SQL vs NoSQL
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/sql-vs-nosql.html) - gitbooks


- CAP Theorem 
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/cap-theorem.html) - gitbooks
  - [educative post](https://www.educative.io/courses/grokking-the-system-design-interview/RMkqx1Egxqz)
  - [CAP Theorem: Revisited](https://robertgreiner.com/cap-theorem-revisited/)


- Consistent Hashing
  - [brief explanation](https://weifoo.gitbooks.io/systemdesign/content/chapter1/consistent-hashing.html) - gitbooks
  - [educative post](https://www.educative.io/courses/grokking-the-system-design-interview/B81vnyp0GpY)
  - [A Guide to Consistent Hashing](https://www.toptal.com/big-data/consistent-hashing#:~:text=Consistent%20Hashing%20is%20a%20distributed,without%20affecting%20the%20overall%20system.)
  - [detailed explanation](https://www.acodersjourney.com/system-design-interview-consistent-hashing/)
  

> ## [System Design Interview Questions – Concepts You Should Know](https://www.freecodecamp.org/news/systems-design-for-interviews/)


## Design Questions

1. Designing Tiny URL
   - [Educative io post](https://www.educative.io/courses/grokking-the-system-design-interview/m2ygV4E81AR)
   - [Geek for Geeks](https://www.geeksforgeeks.org/how-to-design-a-tiny-url-or-url-shortener/) post
   - [Medium](https://medium.com/better-programming/how-would-you-design-tinyurl-and-instagram-987dfc06cbe9) - Tiny URL and Instagram design
   - [Leetcode](https://leetcode.com/discuss/interview-question/124658/Design-a-URL-Shortener-(-TinyURL-)-System/) discussion
   - [Detailed blog](https://nlogn.in/designing-a-realtime-scalable-url-shortening-service-like-tiny-url/) by *nlogn*
      - [YouTube video explanation](https://www.youtube.com/watch?v=JQDHz72OA3c&list=PLkQkbY7JNJuC99VDJcpQdww-4aT3QhdJv&index=21)

   
   
2. Designing Instagram
   - [Educative io post](https://www.educative.io/courses/grokking-the-system-design-interview/m2yDVZnQ8lG)
   - [Instagram Architecture](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)
 
 
3. Designing Twitter
   - [Educative io post](https://www.educative.io/courses/grokking-the-system-design-interview/m2G48X18NDO)
   - [gitbooks post](https://weifoo.gitbooks.io/systemdesign/content/system-design-examples/twitter.html)
      - [YouTube video explanation](https://www.youtube.com/watch?v=wYk0xPP_P_8&list=PLkQkbY7JNJuC99VDJcpQdww-4aT3QhdJv&index=19)
   
   
4. Designing Dropbox
   - [Educative io](https://www.educative.io/courses/grokking-the-system-design-interview/m22Gymjp4mG)
   - [gitbooks post](https://weifoo.gitbooks.io/systemdesign/content/system-design-examples/dropbox.html)
     - [YouTube video explanation](https://www.youtube.com/watch?v=U0xTu6E2CT8&list=PLkQkbY7JNJuC99VDJcpQdww-4aT3QhdJv&index=14)

   
5. Designing YouTube or Netflix
   - [Educative io post](https://www.educative.io/courses/grokking-the-system-design-interview/xV26VjZ7yMl)
      - [YouTube video explanation](https://www.youtube.com/watch?v=psQzyFfsUGU&list=PLkQkbY7JNJuC99VDJcpQdww-4aT3QhdJv&index=20)

   
6. Designing a Parking lot
   - [Educative io post](https://www.educative.io/courses/grokking-the-object-oriented-design-interview/gxM3gRxmr8Z)  
      - [YouTube video explanation](https://www.youtube.com/watch?v=tVRyb4HaHgw)


7. Designing Whatsapp - Chat Messaging System
   - [Gaurav Sen explanation on YouTube](https://www.youtube.com/watch?v=vvhC64hQZMk)
      - [YouTube video explanation](https://www.youtube.com/watch?v=ovnrSH6G6vw)
   
   
8. Designing Facebook Messenger
   - [medium article](https://medium.com/@eileen.code4fun/design-facebook-messenger-438d76639985)
   
   
   
## Blogs 
- [High Scalability](http://highscalability.com/)
- [The complete guide to System Design in 2022 by Educative.io](https://www.educative.io/blog/complete-guide-to-system-design)
- [Medium](https://medium.com/system-design-blog) - system design concepts
- [How Web Works](https://github.com/vasanthk/how-web-works)
- [Hired In Tech](https://www.hiredintech.com/courses/system-design) - System Design for Tech Interviews
- [101 Design Patterns & Tips for Developers](https://sourcemaking.com/design-patterns-and-tips)
- [Introduction to Distributed System Design](https://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html) - Google Code University
- [Hackernoon](https://hackernoon.com/anatomy-of-a-system-design-interview-4cb57d75a53f) -  Anatomy of a System Design Interview
- [How NOT to design Netflix in your 45-minute System Design Interview?](https://hackernoon.com/how-not-to-design-netflix-in-your-45-minute-system-design-interview-64953391a054)
- [What Powers Instagram: Hundreds of Instances, Dozens of Technologies](https://instagram-engineering.com/what-powers-instagram-hundreds-of-instances-dozens-of-technologies-adf2e22da2ad)
- [How to Develop Chat System Design like Facebook Messenger | Whatsapp](https://www.cronj.com/blog/how-to-develop-chat-system-design-like-facebook-messenger/)
- [8 Steps to acing your next system design interview](https://www.hackerearth.com/blog/developers/8-steps-to-acing-your-next-system-design-interview/)
- [best practices for building something like a news feed](https://www.quora.com/Software-Engineering-Best-Practices/What-are-the-best-practices-for-building-something-like-a-news-feed)


   
**Understanding Google File System Architecture (GFS)**
- [GFS original paper](https://github.com/NirmalSilwal/system-design-resources/blob/master/Google%20File%20System.pdf)
- [MIT lecture - YouTube](https://www.youtube.com/watch?v=EpIgvowZr00)
- [IIT Patna lecture - YouTube](https://www.youtube.com/watch?v=EpIgvowZr00)
- Detailed explantion by [ScienceDirect](https://www.sciencedirect.com/topics/computer-science/google-file-system)
- [MapReduce Simplified Data Processing on Large Clusters](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)


**Understanding Google Search engine**
- [The Anatomy of a Large-Scale Hypertextual Web Search Engine](http://infolab.stanford.edu/~backrub/google.html)


**Understanding DynamoDB Architecture**
- [Dynamo: Amazon’s Highly Available Key-value Store](https://github.com/NirmalSilwal/system-design-resources/blob/master/Amazon%20Dynamo%20db%20database%20design.pdf)
- [Best Practices for Designing and Architecting with DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/best-practices.html)

## Video Tutorials on System Design
- [Gaurav Sen playlist](https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX) - must do playlist
- [Grokking the System Design Interview](https://www.youtube.com/playlist?list=PL73KFetZlkJSZ9vTDSJ1swZhe6CIYkqTL)
- [Udit Agarwal low level designs, design patterns, system design videos](https://www.youtube.com/c/anomaly2104/playlists) - suggested by Googler :)
- [Tech Dummies playlist](https://www.youtube.com/c/TechDummiesNarendraL/playlists)
  - [Redis system design - Distributed cache System design](https://www.youtube.com/watch?v=DUbEgNw-F9c&list=PLkQkbY7JNJuC99VDJcpQdww-4aT3QhdJv&index=17) 
  - [S3 system design | cloud storage system design | Distributed cloud storage system design](https://www.youtube.com/watch?v=UmWtcgC96X8)
  - [Yelp system design](https://www.youtube.com/watch?v=TCP5iPy8xqo)
  - [Uber system design](https://www.youtube.com/watch?v=umWABit-wbk&t=2s)
  - [Netflix system design](https://www.youtube.com/watch?v=psQzyFfsUGU&t=4s)
  - [Twitter system design](https://www.youtube.com/watch?v=wYk0xPP_P_8&t=1s)
- [Tushar Roy playlist](https://www.youtube.com/playlist?list=PLrmLmBdmIlps7GJJWW9I7N0P0rB0C3eY2)
- [System Design Interview channel](https://www.youtube.com/c/SystemDesignInterview/videos)
- [Reditt Scaling](https://www.youtube.com/playlist?list=PLVi1LmRuKQ0NINQfjKLVen7J2lZFL35wP)
- [Amazon System Design Preparation (SIP)](https://www.youtube.com/watch?v=gf8R7sgme6o)
- [Success in tech playlist](https://www.youtube.com/playlist?list=PLA8lYuzFlBqAy6dkZHj5VxUAaqr4vwrka) - Coding and System Design Interview Questions
- [Think Software channel playlist](https://www.youtube.com/playlist?list=PLK8IOvtbwVsuYW8KovGg9o6dlhspym8O_) - Systems Design Interview Questions
- [Scalability lecture by David Mellan Harvard](https://www.youtube.com/watch?v=-W9F__D3oY4&list=PLmhRNZyYVpDmLpaVQm3mK5PY5KB_4hLjE&index=10)
- [Code Karle YouTube playlists](https://www.youtube.com/c/codeKarle/playlists) and their [website blogs](https://www.codekarle.com/)
- [Design Patterns in Object Oriented Programming playlist](https://www.youtube.com/playlist?list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc) - Christopher Okhravi

## Tech Talk
- [Facebook and memcached - Tech Talk](https://www.youtube.com/watch?v=UH7wkvcf0ys&t=283s)
- ["Caching at Netflix: The Hidden Microservice" by Scott Mansfield](https://www.youtube.com/watch?v=Rzdxgx3RC0Q)
- [Why Google Stores Billions of Lines of Code in a Single Repository](https://www.youtube.com/watch?v=W71BTkUbdqE)
- [Scaling Instagram Infrastructure](https://www.youtube.com/watch?v=hnpzNAPiC0E)
- [Google Production Environment](https://www.youtube.com/watch?v=dhTVVWzpc4Q)
- [Microservices at Netflix Scale: Principles, Tradeoffs & Lessons Learned](https://www.youtube.com/watch?v=57UK46qfBLY)
- [Four Distributed Systems Architectural Patterns by Tim Berglund](https://www.youtube.com/watch?v=tpspO9K28PM)
- [Seattle Conference on Scalability: YouTube Scalability](https://www.youtube.com/watch?v=ZW5_eEKEC28)
- [Operations at Twitter: Scaling Beyond 100 Million Users](https://www.youtube.com/watch?v=z8LU0Cj6BOU)
- [Scaling Redis at Twitter](https://www.youtube.com/watch?v=rP9EKvWt0zo)


## System Design Cheatsheet
1. [basic concepts](https://gist.github.com/vasanthk/485d1c25737e8e72759f#system-design-cheatsheet)
2. [Scalable System Design Patterns](http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html)

## System Design Template
- [template here](https://leetcode.com/discuss/career/229177/My-System-Design-Template)

## Understanding Design Patterns
- [design patterns for Humans](https://github.com/kamranahmedse/design-patterns-for-humans)
- [Refactoring guru design patterns](https://refactoring.guru/design-patterns)

## Notable github repo to understand concepts more
- [system-design-and-architecture](https://github.com/puncsky/system-design-and-architecture)
- [system-design-primer](https://github.com/donnemartin/system-design-primer)
