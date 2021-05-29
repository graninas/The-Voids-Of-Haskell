# The Voids Of Haskell

I often hear how happy Haskellers are because they have such a great and unique language. They must be proud of how the outer world respects this Haskell technical superiority, and how the language influences all the other languages. This is deserved for sure, and it’s definitely a reason for pride.

But when it comes to the closer comparison with any other mainstream language, we see that not everything in the Haskell ecosystem is good enough. The skies are getting dark revealing some problems, some imperfectness of the bright picture we’re trying to present to the outer world. It’s not a total eclipse; the community has made a great effort to improve the ecosystem: theoretical foundations of the language, the GHC compiler, packaging/building tools (stack & cabal), IDEs (HLS), libraries, the Haskell process itself (Haskell Foundation), - all these things are reasonably good and getting better.

However, there is a sunspot, a definite flaw in the ecosystem that causes the suboptimal expansion of the language. The flaw that makes the outer world considering Haskell to be impractical and incapable of being a low-risk language. The flaw that scares away many people who could be our colleagues but who considered Haskell not worth learning.

And the sunspot is - the lack of understanding of how to use Haskell for solving real-world business problems.

The language has a known complexity. It’s barely possible to avoid difficult, sophisticated features of the language when building more or less big programs. Many popular libraries require extra knowledge beyond the beginner level. Learning of those libraries can’t be easy because they use a tricky Haskell, and do it in crafty, inventive ways. We found interesting solutions to many local problems, yet we aren’t that good at explaining what magic is working there. And the main problem is not our inability to explain things well, although this also has some place. The main problem is that the approaches from the deep Haskell don’t represent a structured, well-formed and elaborated methodology. It’s not an engineering field, it’s the domain of individual hackers, each of whom owns the secrets of the craft. It’s not portable knowledge, it’s folklore and subjective wisdom.

People love discussing tons and tons of cool abstract things, but it seems Haskell lacks the mindful, practical engineering discipline unifying the concepts we have today. If I ask a fellow Haskeller what this new feature is about, what answer will I get? This: *“The feature can be used here and here, in this form, together with those features, like the example shows”*, or that: *“The feature is just a representation of that Math thing, so it can be used for writing a correct code”*? For sure, having Math foundations is great, but this won’t help in understanding how to apply this knowledge in practice, and how it’s all related to the big picture of Software Design.

The modern software industry has come to a reasonable strategy to simplify the way the code is written, because this enables more developers with fewer skills, and decreases the risks for the project. Working with complexity, managing the complexity, reducing the complexity is the main task of Software Design, and the main thing every senior developer should bother about. But when the complexity is unavoidable, we can and should mitigate it by better teaching, by being more practice-oriented, by providing good learning materials.

Aren't we fine so far? Don’t we have a great language? Isn’t it growing?

That’s true. Haskell is growing. But it could grow much faster if we demonstrated more pragmatism and the ability to solve business problems. Haskell still makes an impression of being an academic-only language, and many Haskellers want it to be academic-only. But the language can’t survive without industry adoption. And since Haskell claims to be a trendsetter in the Functional Programming world, it should prove this, or stop claiming. If Haskellers claim that they know what they are doing, this should be proven by more good materials on how to do things. More articles. More showcase projects. More success stories. And, of course, more books.

That’s the fact: Haskell has an insufficient number of books on almost everything. How did it happen that this big and rich language is unable to express its ideas well? We have maybe 30 Haskell books, more or less advanced, more or less obsolete, more or less applied. But considering the number of features and the expressibility of concepts, we could have hundreds of books. Python, a very simple language, has 400+ books. Java, an intermediate language, has even more. Golang, being a primitive language, has twice more books than Haskell has. Haskell failed to deliver for 30 years of evolution while Golang overproduced during a single decade. Why is Haskell worse here? Isn’t that Haskell only pretends to be superior to other languages while it’s not?

How come? My answer is that mainstream languages are aiming to be useful and friendly. The authors do their best to bring life into languages. They, first, produce knowledge on how to solve real tasks, and second, communicate the ideas of the languages to the rest of the world. They make the expansion of a particular language possible by attracting more attention to it and enabling more efficient education for learners. The language feels alive when, first, it gets new versions, and second, new features are not hanging in the vacuum. New features are coming with an understanding of how to use them in real scenarios, and how to teach those features to the developers. Take a look at Rust: there is no feature that could be accepted without a detailed explanation on how to teach it. And that’s an official position of the Rust language creators.

I’ve heard the opinion that we have great blog posts, and therefore we don’t need Haskell books anymore. Like, why repeat what was already said. Just read blog posts and papers, and you’ll get everything you need.

I strongly disagree. The value of a book in its systematic, comprehensive exposition into a specific theme. You will never get a full picture of Software Design from blog posts. You will never get a consistent methodology on how to do things. You will never get complete, structured knowledge. You can only get occasional wisdom on small, separated things. Books are important because they look at the theme from a higher, more general, and more conscious position than blog posts. Books have a different goal: to not just share one’s findings but to form the Software Engineering discipline and fixate its current state.

I’m very scared by the number of gaps we have in the Haskell world. In addition to ~30 existing books, there are 30+ big themes to cover. If we consider that every author has their own style of writing, we’d better have multiple books on every theme. This means we lack hundreds of books, and this number will only increase with time. Hundreds of books are a lot. And covering this gap isn’t an easy deal. This can’t be fixed without support from the community, but to make this happen, the community should realize the problem. It should finally see that we have big voids in the ecosystem. The Voids Of Haskell.

How do I know? You’re in your right not taking my words for it. But I’m not a theorist, I’m a practitioner, and I have evidence for you. I prepared a list of books we could have. Imaginary books with their concepts and ideas, - those books I’d love reading personally. The books that could teach me everything we have in other popular languages but for some reason are unable to reproduce in Haskell. Check out my list of books we’re missing - I’m sure you’ll find it entertaining.

---

### The Voids Of Haskell

* [Clean Functional Code](#Clean-Functional-Code)
* [Beyond The Functions: Design Patterns In Functional Programming](#Beyond-The-Functions-Design-Patterns-In-Functional-Programming)
* [Database Programming With Haskell](#Database-Programming-With-Haskell)
* [Going Fancy: Type-Safe Relational Mapping With Haskell](#Going-Fancy-Type-Safe-Relational-Mapping-With-Haskell)
* [Domain-Driven Design In Haskell](#Domain-Driven-Design-In-Haskell)
* [Boringly Simple Haskell: The Path Of A Rebellion](#Boringly-Simple-Haskell-The-Path-Of-A-Rebellion)
* [Event Sourcing, CQRS, And Reliable Systems In Haskell](#Event-Sourcing--CQRS--And-Reliable-Systems-In-Haskell)
* [The Actors Of FRP](#The-Actors-Of-FRP)
* [Game Development In Haskell](#Game-Development-In-Haskell)
* [The Correct Software. A Haskeller’s Perspective](#The-Correct-Software--A-Haskeller-s-Perspective)
* [Conquering The Concurrency: The Engineering Approach](#Conquering-The-Concurrency--The-Engineering-Approach)
* [Mimic The Enemy: Object-Oriented Programming In Haskell](#Mimic-The-Enemy-Object-Oriented-Programming-In-Haskell)
* [A Rest-Full Guide On Web Development In Haskell](#A-Rest-Full-Guide-On-Web-Development-In-Haskell)
* [The Pink Glasses: Haskell’s Optics For Working With Data](#The-Pink-Glasses-Haskell-s-Optics-For-Working-With-Data)
* [The Happy Marriage Of Haskell And Category Theory](#The-Happy-Marriage-Of-Haskell-And-Category-Theory)
* [Domain-Driven Design With Category Theory](#Domain-Driven-Design-With-Category-Theory)
* [Mastering Functional Streams With Haskell](#Mastering-Functional-Streams-With-Haskell)
* [Data Science In Haskell](#Data-Science-In-Haskell)
* [Never Be Back: Domain-Specific Languages In Haskell](#Never-Be-Back-Domain-Specific-Languages-In-Haskell)
* [Mine it! Blockchains In Haskell](#Mine-it--Blockchains-In-Haskell)
* [Testing Practices With Haskell](#Testing-Practices-With-Haskell)
* [Test-Driven Development In Haskell](#Test-Driven-Development-In-Haskell)

#### Clean Functional Code

This promises to be a great 400 pages book that will teach hundreds of thousands of developers what is good functional code. This book will be the most popular book of all having Haskell as a model language. It will bring a lot of fame and money to the authors. This will be much easier, much more rewarding, much more beneficial than writing any other book on Haskell. This one will be known in the whole functional programming world. Scala, F#, Elm, even C#, JavaScript, C++ - all these camps will learn from the book and will see that Haskell is not scary.

* [Code Complete](https://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670)
* [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)

#### Beyond The Functions: Design Patterns In Functional Programming

Surely, we have some Haskell books about Functor-Applicative-Monad, but they don’t cover the recent discoveries. Just talking about “functors” is not enough. You can discuss interesting properties of data structures, but you won’t get a full picture of how to design the code, only small parts of it. What is missing here is the understanding of the difference between functional idioms and design patterns. Functors, applicatives, monads are more internal, inherent functional idioms rather than external, compound design patterns. Functional idioms reveal the math nature of a data structure whereas design patterns allow constructing solutions to common programming problems. The new 500 pages book on design patterns in Haskell should demonstrate this distinction and provide a comprehensive GoF-like reference on all the design patterns recently discovered in functional languages.

* [(GoF Book) Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8)
* [Functional Design And Architecture](https://leanpub.com/functional-design-and-architecture)
* [Haskell Design Patterns](https://www.google.ru/books/edition/Haskell_Design_Patterns/Q_KoCwAAQBAJ?hl=en&gbpv=0)
* [Functional Programming Patterns in Scala and Clojure](https://www.amazon.com/Functional-Programming-Patterns-Scala-Clojure/dp/1937785475)
* [Scala Design Patterns](https://www.amazon.com/Scala-Design-Patterns-Practical-Reuse/dp/3319021915)

#### Database Programming With Haskell

By reading this book, you’ll become proficient in implementing database-related code. You’ll get everything you wanted to know about persistence in Haskell, and even more than that. Relational databases, key-value databases, object databases, file shares, distributed and cloud storages. The questions of connectivity, type-safe querying, schema migration, DB model design, error handling, reliability of the code, versioning, and also - libraries comparison, the related design patterns, even the CAP theorem and its consequences. This would be a really dense 1000 pages book, an epoch-making work, extremely helpful and ideas-intensive. But writing it will require a dramatically high level of knowledge and involvement. More than a single person can afford.

* [Database Programming With C#](https://www.amazon.com/Database-Programming-C-Carsten-Thomsen/dp/1590590104)
* [NoSQL Databases A Complete Guide 2020 Edition](https://www.amazon.com/dp/0655909338?tag=uuid10-20)
* [C++ Object Databases: Programming With the Odmg Standard](https://www.amazon.com/Object-Databases-Programming-ODMG-Standard/dp/0201634880)

#### Going Fancy: Type-Safe Relational Mapping With Haskell

Today, we have a dozen libraries for relational databases, quite different and sometimes sophisticated. What’s hidden there? What smart tricks and approaches are used for providing a type-safe, type-level methodology of defining relational DB schema? What’s interesting is there? What deep and intricate Haskell features can be used? How can we construct a querying eDSL, and what will be our solutions to make it extensible? This 600 pages book will be quite useful for both: interested in learning a fancy Haskell, and those who want to improve their library constructing skills.

* [Core Java™ Data Objects](https://www.oreilly.com/library/view/core-javatm-data/0131407317/)
* [Databases, Types And the Relational Model: The Third Manifesto 3rd Edition](https://www.amazon.com/Databases-Types-Relational-Model-3rd/dp/0321399420)

#### Domain-Driven Design In Haskell

We often claim that Functional Programming is much better for describing complex domains than Object-Oriented Programming. Until recently, our claims were unproven. It was a belief rather than a real practice. There was no unified methodology on how to convert a particular business domain into functional code. There were no best practices and well-known solutions. There was no understanding of how Domain-Driven Design works in Haskell. But this book changes everything. It presents a ready-to-use methodology, a nicely shaped source of knowledge on this theme. By reading it, you’ll know how algebraic data types, while being a great tool, open a door to more interesting applications of different functional concepts. The knowledge presented in this book is universal. It can be used to describe any domain no matter how complex it is, and the code will be well-structured, concise, simple, expressible, safe. Besides that, this 500 pages book provides a reasoning framework for domain analysis and exploration.

* [Domain-Driven Design:  Tackling Complexity in the Heart of Software ](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)
* [Functional and Reactive Domain Modeling](https://www.manning.com/books/functional-and-reactive-domain-modeling)
* [Domain Modeling Made Functional](https://fsharpforfunandprofit.com/books/)

#### Boringly Simple Haskell: The Path Of A Rebellion

If you ever felt like being an outsider in a company of smarter colleagues who could discuss complex and very abstract Haskell things, this book is for you. You’ll see that it’s really possible to write useful programs in Haskell without that difficult stuff. The authors do their best to present you with the intermediate-level Haskell in a rigorous way, with nice samples and exercises. While reading this small 300-page book, you’ll be constructing a program with only simple concepts. This won’t be easy, because doing simple is hard. But when you finish your journey with the book, you’ll be valuing simplicity a lot.

* [The Simple Haskell Handbook](https://leanpub.com/simple-haskell-book)

#### Event Sourcing, CQRS, And Reliable Systems In Haskell

We already know how to build distributed systems. We know how to make our services responsive, resilient, and reliable. All we need is CQRS and Event Sourcing. What we don’t know is how to do it in Haskell. What tools? What approaches? When? Haskell demonstrates a good enough performance for being a tool of a choice, but it needs some ready patterns on how to organize such a project. The book gives all the answers so one can take it as a methodology and build a solution suitable for a particular domain. The book also compares Haskell and Scala to provide a better insight into what is good and what is not. A very useful 400 pages book contributing to the Software Engineering discipline in Haskell.

* [Exploring CQRS and Event Sourcing](https://www.amazon.com/Exploring-CQRS-Event-Sourcing-maintainability/dp/1621140164)
* [Functional and Reactive Domain Modeling](https://www.manning.com/books/functional-and-reactive-domain-modeling)

#### The Actors Of FRP

Haskell has lots of FRP libraries, all having their own approaches and structures. It’s quite easy to get lost in this Pandora box of ideas. This book is a deep, thorough, and practical guide into different kinds of FRP in Haskell. The reader will learn this difficult theme in application to real tasks: web development, game development, distributed applications, microservices. The book provides a comprehensive comparison of the libraries (reactive-banana, reflex, reflex-dom, netwire, yampa) and even teaches the reader to build their own FRP library. A really good source of knowledge presented well, with cool examples and joyful style. 600 pages.

* [Functional Reactive Programming](https://www.manning.com/books/functional-reactive-programming)
* [Functional and Reactive Domain Modeling](https://www.manning.com/books/functional-and-reactive-domain-modeling)
* [Reactive Design Patterns](https://www.manning.com/books/reactive-design-patterns)

#### Game Development In Haskell

Gaming is fun! By reading this funny book, you’ll learn how to build interesting games in Haskell with Gloss, Helm, and LambdaHack. This can be your first Haskell book - so simple it is! Learning from this 300 page book won’t take much time. The best interactive introduction to the language!

* [Introducing JavaScript Game Development: Build a 2D Game from the Ground Up](https://www.amazon.com/Introducing-JavaScript-Game-Development-Ground/dp/1484232518)

#### The Correct Software. A Haskeller’s Perspective

This is a very unique book. You definitely want it! Correctness of Software - what it is, and how to achieve it. Today we know the answer, and the answer is beautiful! Haskell is very suitable for writing correct, type-safe logic having no bugs by construction. The book gives you a deep introduction to type-level programming with a touch of the types-as-proofs theme and the math around this. The material is not only theoretical, - the authors provide a set of real use cases with detailed explanations of techniques used. The book is written well, it only speaks about what’s really important for the narrative, and doesn’t travel too deep into the theory. Book has 500 pages, and it’s very dense.

#### Resource Management With Linear Types

Managing resources was never an easy theme. Doing it right is an extremely difficult task, especially considering that nobody knows what is right and what is wrong. We’ve elaborated some practices and approaches such as RAII in other languages, but not everything is applicable to Haskell 1:1. This 500 pages book presents a new way of resource handling, a methodology based on Linear Types. The authors made a great effort to show how to structure resource-safe applications in Haskell, how to marry Linear Types and exceptions, and how to deal with laziness. A very practical book, but not really simple to read.

#### Conquering The Concurrency: The Engineering Approach

What differentiates this 600 pages book from its predecessors is the approach the authors took. They discuss concurrency from the Software Design point of view. They evaluate different solutions: multithreaded and single-threaded, with STM, MVars, and hand-written concurrent algorithms. They compare the performance, the complexity, the difficulty of the solutions, make conclusions and provide the best strategies on how to organize concurrent applications for different business domains.

* [Parallel and Concurrent Programming in Haskell](https://www.oreilly.com/library/view/parallel-and-concurrent/9781449335939/)

#### Mimic The Enemy: Object-Oriented Programming In Haskell

"Know thy enemy and know yourself; in a hundred battles, you will never be defeated”, - Sun Tzu once said. For Haskell, implementing an OOP-like programming environment means not only broadening the horizons by learning OOP itself, but also revealing deep insights about Haskell itself. The book is a thorough investigation on how to implement object systems, dynamic dispatch, inheritance, and encapsulation in a strange, unnatural yet useful way. Starting from a general understanding of OOP, the authors of this 600 pages book came to the conclusion that being a mindful Haskell developer also means knowing what other techniques exist.

#### A Rest-Full Guide On Web Development In Haskell

This 500 pages book is intended for those who want to build something useful in Haskell without getting onto the ground of difficult concepts. This book is especially useful because it compares different web servers: Scotty, Servant, Warp, Yesod. Features, performance, design patterns, application architectures of web applications, and other questions presented within a single resource for your convenience.

* [Developing Web Apps with Haskell and Yesod, 2nd Edition](https://www.oreilly.com/library/view/developing-web-apps/9781491915585/)
* [Start Building RESTful Microservices using Akka HTTP with Scala](https://www.amazon.com/dp/1976762545/)

#### The Pink Glasses: Haskell’s Optics For Working With Data

Lenses have got a good share in the Haskell world. It all started from overcoming the flaws of the language and ended up with a whole new universe of precise, math-based abstractions for manipulating data structures. Although lenses are useful, they form a separate language that isn’t easy to learn. Unless you read this excellent book.

And by the way, it’s already written!

* [Optics By Example](https://leanpub.com/optics-by-example)

#### The Happy Marriage Of Haskell And Category Theory

It’s not a secret that Category Theory has rooted in the Haskell world quite reliably. This 500 pages book tries to step back from the path traveled and take a fresh look at it. It turns out that the history of inventing Category Theory in Haskell is entertaining on its own. Nice findings, sudden discoveries, cool math hints, unexpected obstacles on what was seemed simple initially, - the book presents all this in a popular science narration approachable to every curious person. By reading the book, you’ll know what was hidden behind the scenes of introducing Category Theory concepts in Haskell, and you’ll see how much love the researchers have put into it.

#### Domain-Driven Design With Category Theory

This is definitely not a simple book. Category Theory as a Math theory has a known difficulty, and its Haskell branch isn’t simple either. The book does its best to build an approachable, concise methodology on how to apply Category Theory to real tasks and shows how to use it for Domain-Driven Design. The reader will learn a number of tools useful in day-to-day practice and will be able to see the real, math nature of different data structures. The book is very detailed, it makes excursus into Math when needed but does it graciously. This unique 600 pages book presents a new view on Software Design and will be useful to all software engineers.

* [Category Theory for Programmers](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/)

#### Mastering Functional Streams With Haskell

* [Mastering Akka](https://www.oreilly.com/library/view/mastering-akka/9781786465023/)

Functional stream programming wasn’t a new idea. Like many other ideas from Functional Programming, it was there for a couple of decades until it finally reached some adoption in the industry. Scala has Akka-streams, Java has Streams API, C# with its LINQ can provide a base for streaming, C++20 is now packed with ranges, and even web languages such as JavaScript and Python have some features for stream programming. Despite that, we didn’t have an understanding of how to organize our code for the best utilization of the streaming style. But this 500-page book changed everything. Now, it’s clear that streams are an architectural pattern, and should be used with care. It’s not only about performance, but also about complexity, concurrency and testability, - and all of this in the light of different streaming libraries. Before this book, it was very difficult to decide on what library to use: conduits, machines, streamly, streaming, - but now we know the strengths and weaknesses of each.

* [Functional and Reactive Domain Modeling](https://www.manning.com/books/functional-and-reactive-domain-modeling)
* [Reactive Design Patterns](https://www.manning.com/books/reactive-design-patterns)

#### Data Science In Haskell

Functional Programming is slow! Haskell is slow, too! Use Python, it’s good for everything!

Do you see a contradiction here? Python is one of the slowest languages, it’s 20 times less performant than Haskell. And still, it rules the world today. What can Haskell offer to overcome this strange situation? If Haskell is so great at data manipulation, can it replace Python in Data Science? This book provides the answer: Haskell has everything for that. The authors make a great effort to show how it’s easy to do machine learning with Haskell, and how reliable the code becomes. The expressiveness of the language allows us to use different styles when working with neural network and classification algorithms, and it makes even more sense to utilize the full power of applicatives, monads, and arrows for that. A very insightful and practical 600 pages book, that is also backed by application templates. A must-have book even if you don’t do machine learning!

* [Scala for Data Science](
https://www.oreilly.com/library/view/scala-for-data/9781785281372/)
* [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
* [https://www.amazon.com/Python-Data-Analysis-Wrangling-IPython/dp/1491957662/ref=sr_1_2?dchild=1&keywords=Python+Data+Science&qid=1622276271&sr=8-2](Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython 2nd Edition)

#### Never Be Back: Domain-Specific Languages In Haskell

It was stated that Haskell is superior for building domain-specific languages, both embedded and external. If so, why not have this theme covered by a neat book? What would you expect to read in such a book? If it’s about an external domain-specific language, then the topics of parsing, grammar description, translation, testing, syntax design, and semantics design should be covered. If it’s about embedded languages, - well, Haskell has a lot to offer here! Starting from the usual functional declarative languages, going through functors, applicatives, monads, arrows, comonads, zippers, and ending up with type-level domain-specific languages. This 600 pages book has everything you need, and even more than that. It shows why DSLs are a great idea, and how to be more conscious when designing your own.

* [Domain-Specific Languages](https://www.amazon.com/Domain-Specific-Languages-Addison-Wesley-Signature-Fowler/dp/0321712943)
* [DSLs in Action](https://www.manning.com/books/dsls-in-action)

#### Mine it! Blockchains In Haskell

This book represents an honest discussion on the very controversial field. It happened so that Haskell has recommended itself in the blockchain field, and it’s already a notable player there, so at least this should be investigated and reflected somehow. The authors show how different concepts of Haskell make it very suitable for building highly concurrent, massively distributed and extremely complex applications. Besides the fact that it teaches how to build your own blockchain, the book also introduces a couple of new ideas on how to approach the correctness in such systems. The book also touches on the currently existing Haskell blockchain technologies and provides a good picture of how they are built from the engineering point of view.

* [Blockchain For Rust Developers: The Ultimate Beginner’s Guide to build your own Blockchain application with Rust](https://www.amazon.com/Blockchain-Rust-Developers-application-Hands/dp/B0874JFXSD)

#### Testing Practices With Haskell

This might first seem that the only viable testing technique in Haskell is property-based testing, but a closer look proves that big projects need other approaches as well. Integration testing, white-box unit testing, end-to-end testing, property-based testing, manual testing, smoke testing, fuzzy testing - these are only a part of the story. It’s all about testing functional requirements. And what about testing non-functional requirements? How to test the Haskell code on performance, load, memory, and space leaks? What are the best practices? What tools to use? This book is definitely the best source of knowledge on that.

* [Testing in Scala](https://www.oreilly.com/library/view/testing-in-scala/9781449360313/)

#### Test-Driven Development In Haskell

Writing software is hard. It’s difficult not only because we choose difficult tools, but also because we choose to not follow methodologies and turn our projects into a mess. The mainstream world has noticed that there are methodologies that reduce the risks. Test-Driven Development, while being criticized a lot, could be very helpful if taken wisely. The book introduces TDD in Haskell and shows why it makes perfect sense to follow it, and what kind of code quality can be achieved.

* [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)

#### Type-Driven Development With Haskell

The world of types is vast. It’s even bigger than we initially thought. It won’t be an exaggeration to say that type-level programming is on the cutting edge of Software Engineering today. This book shows why Haskell is a grey Cardinal in this movement. This is an advanced language with hundreds of type-level features, and it influences other languages a lot. Rust, Scala, C++, TypeScript are the languages that look at Haskell and borrow its ideas secretly. They are aimed to make the life of a developer simpler by leveraging good practices and approaches to structure applications. This book uses Haskell to describe those approaches, and developers in other languages can also benefit from it very much.

* [Type-Driven Development with Idris ](https://www.manning.com/books/type-driven-development-with-i
dris)
* [Programming with Types ](https://www.manning.com/books/programming-with-types)

### Conclusion

Now you must be understanding why I say that Haskell struggles behind the world. There are so many themes that the community is just neglecting for some reason, there are so many voids in the understanding of how to use the language for building software. This is the Haskell Superiority Paradox: while being an extremely advanced language, it fails to prove this superiority by demonstrating sensible results. A language can’t be considered alive if the outer world sees it as impractical. This, in turn, represents a huge obstacle to expansion.

This is my take: if we want Haskell to be more popular (and I do want this with all my heart), we have to fill these gaps somehow. Writing more practical books is a very difficult, time-consuming, life-draining, money-expensive activity. And because of that, supporting authors should be a community-wide value.
 
### About me

- Author of the fundamental book [Functional Design and Architecture](https://leanpub.com/functional-design-and-architecture) about Software Engineering in Haskell. Currently working on the second edition with Manning Publications.
- Also, writing my second book [Pragmatic Type-Level Design](https://www.patreon.com/pragmatic_type_level_design).
- Author of many Haskell and PureScript frameworks: [Hydra](https://github.com/graninas/Hydra), Juspay’s [Presto.Core](https://github.com/juspay/purescript-presto), Juspay’s [EulerHS](https://github.com/juspay/euler-hs), Enecuum’s [Node](https://github.com/graninas/Node), and some others.
- [An international speaker](https://graninas.com/talks-eng/) with more than 20 talks on Functional Design in Haskell and C++.
- [Expert-level developer](https://www.linkedin.com/in/alexander-granin-46889236/) and [IT consultant](https://graninas.com/cv-contacts/).

Feel free to reach me if you have any questions.
