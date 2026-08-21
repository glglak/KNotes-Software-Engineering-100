# Software Engineering 100

**100 software-engineering books. One idea worth keeping from each.**

A curated, opinionated reading map for software engineers, senior engineers, architects, Staff/Principal ICs, and engineering leaders. This is **not an objective ranking** and it is not a claim that every recommendation in every book still applies unchanged in 2026; the goal is to preserve the most useful engineering idea from each book.

> **KNotes:** The point is not to finish 100 books. The point is to know which ideas are worth carrying into real engineering decisions.

## How to use this repo

- Start with **[Top 15](TOP-15.md)** if you want the highest-return subset.
- Pick a **role-based reading path** if you are optimizing for career progression.
- Browse **topic pages** if you are solving a specific engineering problem.
- Use the list below as the complete one-sentence reference.

## Reading paths

- [Software Engineer](reading-paths/software-engineer.md)
- [Senior Engineer](reading-paths/senior-engineer.md)
- [Software Architect](reading-paths/software-architect.md)
- [Staff / Principal](reading-paths/staff-principal.md)

## Topics
- [Architecture & Design](books/architecture-design.md)
- [Distributed Systems & Data](books/distributed-systems-data.md)
- [Code Craft](books/code-craft.md)
- [Testing & Quality](books/testing-quality.md)
- [Reliability, DevOps & Delivery](books/reliability-devops-delivery.md)
- [Security](books/security.md)
- [Systems & Performance](books/systems-performance.md)
- [Engineering Organizations](books/engineering-organizations.md)
- [Product, Planning & Discovery](books/product-planning-discovery.md)
- [AI & ML Engineering](books/ai-ml-engineering.md)

## The 100

| # | Book | Author(s) | One-sentence takeaway |
|---:|---|---|---|
| 1 | **The Pragmatic Programmer** | Andrew Hunt & David Thomas | Great software engineers continuously improve their tools, judgment, communication, and code instead of blindly following processes. |
| 2 | **Designing Data-Intensive Applications** | Martin Kleppmann & Chris Riccomini | Understand databases, replication, partitioning, consistency, streams, and distributed-system trade-offs well enough to design systems rather than merely assemble technologies. |
| 3 | **Refactoring** | Martin Fowler | Improve the internal structure of working software through small, safe transformations instead of waiting for giant rewrites. |
| 4 | **Code Complete** | Steve McConnell | Good software construction comes from disciplined design, readable code, defensive programming, reviews, testing, and deliberate engineering rather than clever syntax. |
| 5 | **A Philosophy of Software Design** | John Ousterhout | The central enemy of software design is complexity, so create deep modules with simple interfaces that hide difficult decisions. |
| 6 | **Design Patterns** | Erich Gamma, Richard Helm, Ralph Johnson & John Vlissides | Recurring design problems often have reusable structural solutions, although patterns should be understood as vocabulary rather than mandatory templates. |
| 7 | **Working Effectively with Legacy Code** | Michael Feathers | The practical definition of legacy code is code without tests, and the safest way to change it is to create testable seams first. |
| 8 | **Software Engineering at Google** | Titus Winters, Tom Manshreck & Hyrum Wright | Software engineering is programming integrated over time, making maintainability, ownership, testing, tooling, and organizational scale first-class design concerns. |
| 9 | **Domain-Driven Design** | Eric Evans | For complex business systems, make the domain model and shared language between engineers and experts the center of the architecture. |
| 10 | **The Mythical Man-Month** | Frederick P. Brooks Jr. | Adding people to a late software project often makes it later because communication and coordination costs grow faster than manpower. |
| 11 | **Clean Code** | Robert C. Martin | Code should communicate intent through understandable names, small abstractions, tests, and disciplined structure, though its specific rules are best treated as heuristics rather than laws. |
| 12 | **Clean Architecture** | Robert C. Martin | Organize software so business rules remain independent of frameworks, databases, delivery mechanisms, and other replaceable details. |
| 13 | **Patterns of Enterprise Application Architecture** | Martin Fowler | Enterprise applications repeatedly encounter the same problems around domain logic, persistence, transactions, layering, and presentation, so learning established patterns prevents reinventing them badly. |
| 14 | **Enterprise Integration Patterns** | Gregor Hohpe & Bobby Woolf | Messaging systems become understandable when integration behavior is described using explicit patterns such as channels, routers, translators, filters, and aggregators. |
| 15 | **Release It!** | Michael T. Nygard | Production systems must be designed to survive latency, dependency failure, cascading faults, overload, and all the ugly realities ignored by happy-path architecture diagrams. |
| 16 | **Site Reliability Engineering** | Betsy Beyer, Chris Jones, Jennifer Petoff & Niall Richard Murphy (eds.) | Reliability can be engineered systematically using SLOs, error budgets, automation, monitoring, incident response, and controlled operational risk. |
| 17 | **Continuous Delivery** | Jez Humble & David Farley | Software should always be kept in a releasable state through automation, fast feedback, repeatable deployments, and small changes. |
| 18 | **Accelerate** | Nicole Forsgren, Jez Humble & Gene Kim | High-performing engineering organizations simultaneously improve delivery speed and stability through measurable capabilities such as deployment frequency, lead time, recovery time, and change-failure rate. |
| 19 | **The DevOps Handbook** | Gene Kim, Jez Humble, Patrick Debois & John Willis | Optimize the entire flow from development to production by shortening feedback loops, automating repetitive work, and making operations a shared responsibility. |
| 20 | **Team Topologies** | Matthew Skelton & Manuel Pais | Architecture and organization design are connected, so structure teams and their interactions around cognitive load and fast flow rather than traditional functional silos. |
| 21 | **Fundamentals of Software Architecture** | Mark Richards & Neal Ford | Architecture is primarily the practice of analyzing competing quality attributes and making explicit trade-offs rather than finding one universally correct structure. |
| 22 | **Software Architecture: The Hard Parts** | Neal Ford, Mark Richards, Pramod Sadalage & Zhamak Dehghani | Difficult architectural decisions around coupling, distributed data, workflows, granularity, and transactions should be evaluated through trade-off analysis rather than ideology. |
| 23 | **Software Architecture in Practice** | Len Bass, Paul Clements & Rick Kazman | Architecture exists to satisfy quality attributes such as performance, modifiability, availability, security, and usability through deliberate design decisions. |
| 24 | **Building Evolutionary Architectures** | Neal Ford, Rebecca Parsons, Patrick Kua & Pramod Sadalage | Architecture should be capable of guided incremental change, with automated fitness functions protecting the properties you care about. |
| 25 | **Building Microservices** | Sam Newman | Microservices are primarily about independently changeable business capabilities and organizational boundaries, not merely splitting an application into many HTTP services. |
| 26 | **Monolith to Microservices** | Sam Newman | Successful modernization usually comes from incremental extraction around business boundaries rather than rewriting the entire monolith. |
| 27 | **Microservices Patterns** | Chris Richardson | Distributed architectures require explicit solutions for service boundaries, transactions, sagas, messaging, discovery, testing, and deployment. |
| 28 | **Understanding Distributed Systems** | Roberto Vitillo | Distributed systems become easier to reason about once you understand networks, failures, replication, consistency, coordination, scalability, and observability from first principles. |
| 29 | **Designing Distributed Systems** | Brendan Burns | Many distributed applications can be constructed from reusable patterns for sidecars, adapters, leaders, work queues, scatter/gather, and other coordination mechanisms. |
| 30 | **Patterns of Distributed Systems** | Unmesh Joshi | Consensus, replication, clocks, partitions, logs, leases, and other apparently complicated distributed behaviors can be understood as combinations of recurring implementation patterns. |
| 31 | **Database Internals** | Alex Petrov | Understanding storage engines, B-trees, LSM trees, indexes, replication, and distributed database internals makes database behavior far less mysterious. |
| 32 | **Streaming Systems** | Tyler Akidau, Slava Chernyak & Reuven Lax | Correct stream processing depends on explicitly reasoning about event time, processing time, windows, watermarks, state, and delivery semantics. |
| 33 | **Designing Event-Driven Systems** | Ben Stopford | Event streams can become the backbone of scalable architectures when events, logs, state, services, and data integration are treated as one coherent model. |
| 34 | **NoSQL Distilled** | Pramod J. Sadalage & Martin Fowler | Choose databases based on data models, access patterns, consistency needs, and operational trade-offs rather than assuming relational databases—or NoSQL—are universally superior. |
| 35 | **API Design Patterns** | JJ Geewax | Good APIs expose consistent abstractions for resources, operations, pagination, long-running jobs, versioning, errors, and evolution instead of leaking implementation details. |
| 36 | **RESTful Web APIs** | Leonard Richardson & Mike Amundsen | Web APIs work best when HTTP, resources, representations, links, and protocol semantics are treated as architectural tools rather than merely transport. |
| 37 | **Implementing Domain-Driven Design** | Vaughn Vernon | DDD becomes practical through bounded contexts, aggregates, domain events, repositories, application services, and explicit integration between models. |
| 38 | **Learning Domain-Driven Design** | Vlad Khononov | DDD is fundamentally a technique for managing business complexity and boundaries, not a collection of fancy tactical coding patterns. |
| 39 | **Domain Modeling Made Functional** | Scott Wlaschin | Types and functional programming can make business rules explicit and prevent invalid domain states from being representable. |
| 40 | **Test-Driven Development: By Example** | Kent Beck | Let small failing tests drive incremental implementation and design while keeping the code continuously working. |
| 41 | **Growing Object-Oriented Software, Guided by Tests** | Steve Freeman & Nat Pryce | Tests can help evolve the architecture of a system by forcing clear responsibilities, boundaries, collaboration, and dependency design. |
| 42 | **xUnit Test Patterns** | Gerard Meszaros | Test suites themselves require good architecture because fixtures, doubles, setup, isolation, and test smells can make tests either valuable assets or expensive liabilities. |
| 43 | **Unit Testing: Principles, Practices, and Patterns** | Vladimir Khorikov | Good tests verify observable behavior rather than implementation details, giving high confidence without making refactoring painful. |
| 44 | **Effective Software Testing** | Maurício Aniche | Testing is a risk-management activity that should deliberately cover boundaries, unusual inputs, contracts, properties, state transitions, and failure conditions. |
| 45 | **The Art of Software Testing** | Glenford J. Myers, Corey Sandler & Tom Badgett | Testing is the process of deliberately trying to expose defects, not demonstrating that the program happens to work. |
| 46 | **Modern Software Engineering** | David Farley | Effective engineering applies fast feedback, experimentation, modularity, automation, and empirical learning so software can evolve safely. |
| 47 | **Agile Software Development: Principles, Patterns, and Practices** | Robert C. Martin | Agile engineering depends as much on technical practices and dependency design as it does on iterations and project-management rituals. |
| 48 | **Extreme Programming Explained** | Kent Beck | Small releases, feedback, testing, simple design, collaboration, and continuous improvement let teams respond safely to changing requirements. |
| 49 | **The Clean Coder** | Robert C. Martin | Professional software engineering includes saying no when necessary, making responsible commitments, practicing deliberately, communicating clearly, and taking ownership of quality. |
| 50 | **97 Things Every Programmer Should Know** | Kevlin Henney (ed.) | Engineering maturity comes from dozens of small habits around simplicity, testing, learning, collaboration, debugging, and maintainability rather than one grand methodology. |
| 51 | **The Programmer’s Brain** | Felienne Hermans | Reading and writing code are cognitive activities constrained by working memory, long-term memory, attention, and how information is represented. |
| 52 | **The Missing README** | Chris Riccomini & Dmitriy Ryaboy | Becoming an effective professional engineer requires skills that university rarely teaches, including code reviews, design docs, on-call work, debugging, collaboration, and career navigation. |
| 53 | **The Effective Engineer** | Edmond Lau | Engineering impact comes from maximizing leverage by prioritizing work that produces disproportionate long-term value. |
| 54 | **Staff Engineer** | Will Larson | Senior individual contributors create impact through technical direction, organizational influence, mentorship, execution, and solving ambiguous cross-team problems rather than simply writing more code. |
| 55 | **The Staff Engineer’s Path** | Tanya Reilly | Staff-level effectiveness comes from developing technical vision, navigating uncertainty, influencing without authority, and making the surrounding organization more capable. |
| 56 | **The Software Engineer’s Guidebook** | Gergely Orosz | Career progression from engineer to senior, lead, and staff levels requires increasing ownership, judgment, technical scope, communication, and organizational impact. |
| 57 | **The Manager’s Path** | Camille Fournier | Engineering management evolves from mentoring individuals to building teams, organizations, processes, and technical cultures without losing sight of engineering reality. |
| 58 | **An Elegant Puzzle** | Will Larson | Engineering organizations are systems that must balance team structure, technical strategy, growth, migrations, priorities, and organizational constraints. |
| 59 | **Peopleware** | Tom DeMarco & Tim Lister | Most software productivity problems are sociological rather than technical, making focus, trust, environment, team cohesion, and management quality crucial. |
| 60 | **Rapid Development** | Steve McConnell | Software schedules improve through disciplined risk management, estimation, lifecycle choices, team practices, and avoiding classic project-management mistakes—not through wishful deadlines. |
| 61 | **Death March** | Edward Yourdon | Projects with impossible schedules or resources must be recognized and managed explicitly rather than pretending normal project-management rules still apply. |
| 62 | **Facts and Fallacies of Software Engineering** | Robert L. Glass | Many widely accepted beliefs about software productivity, maintenance, estimation, reuse, and quality are contradicted by decades of industry evidence. |
| 63 | **Waltzing with Bears** | Tom DeMarco & Timothy Lister | Software risk should be quantified, exposed, and managed instead of quietly converting uncertain estimates into politically convenient commitments. |
| 64 | **Slack** | Tom DeMarco | Organizations need spare capacity because eliminating every bit of apparent inefficiency also eliminates their ability to innovate, respond, and change. |
| 65 | **The Deadline** | Tom DeMarco | Software project management succeeds through understanding people, risk, estimation, pressure, and trade-offs rather than relying on heroic schedules. |
| 66 | **Lean Software Development** | Mary Poppendieck & Tom Poppendieck | Optimize software delivery by eliminating waste, building quality in, delivering quickly, respecting people, and optimizing the whole system. |
| 67 | **Agile Estimating and Planning** | Mike Cohn | Plans should express uncertainty and be continuously revised using empirical delivery data rather than pretending early estimates are precise commitments. |
| 68 | **User Story Mapping** | Jeff Patton | Organize requirements around the user’s end-to-end journey so teams can prioritize meaningful slices of value instead of managing disconnected backlog items. |
| 69 | **Specification by Example** | Gojko Adzic | Concrete examples shared by business and engineering can become executable specifications that reduce ambiguity and align requirements with tests. |
| 70 | **BDD in Action** | John Ferguson Smart | Behavior-driven development uses examples and shared language to connect business outcomes, requirements, automated tests, and implementation. |
| 71 | **The Phoenix Project** | Gene Kim, Kevin Behr & George Spafford | IT delivery behaves like a production system, so controlling work in progress, bottlenecks, feedback, and dependencies dramatically improves flow. |
| 72 | **The Site Reliability Workbook** | Betsy Beyer et al. | SRE concepts become practical through specific techniques for SLOs, alerts, incident response, automation, capacity planning, and reliability engineering. |
| 73 | **Observability Engineering** | Charity Majors, Liz Fong-Jones & George Miranda | Complex systems require high-cardinality, high-dimensional telemetry that lets engineers ask new questions about production behavior without predicting every failure beforehand. |
| 74 | **Distributed Systems Observability** | Cindy Sridharan | Logs, metrics, traces, and operational context are essential for understanding failure in distributed systems where no single component possesses the full truth. |
| 75 | **Chaos Engineering** | Casey Rosenthal & Nora Jones (eds.) | Reliability improves when teams deliberately experiment with failure and verify that systems actually behave as expected under adverse conditions. |
| 76 | **Building Secure and Reliable Systems** | Heather Adkins et al. | Security and reliability should be designed together using least privilege, defense in depth, resilience, recoverability, and controlled change. |
| 77 | **Threat Modeling** | Adam Shostack | Security becomes manageable when teams systematically identify what they are building, what can go wrong, what defenses exist, and whether those defenses are sufficient. |
| 78 | **Security Engineering** | Ross Anderson | Secure systems require understanding economics, protocols, authentication, cryptography, hardware, human behavior, and adversarial incentives rather than merely adding security products. |
| 79 | **Secure by Design** | Dan Bergh Johnsson, Daniel Deogun & Daniel Sawano | Domain modeling and software design can eliminate entire classes of vulnerabilities before security testing begins. |
| 80 | **Alice and Bob Learn Application Security** | Tanya Janca | Developers can prevent many common security failures by learning practical threat modeling, authentication, authorization, injection defenses, dependency hygiene, and secure development practices. |
| 81 | **Infrastructure as Code** | Kief Morris | Infrastructure should be versioned, tested, reproducible, modular, and delivered through automated software-engineering practices rather than maintained manually. |
| 82 | **Cloud Native Patterns** | Cornelia Davis | Cloud-native systems achieve resilience and scalability through patterns involving statelessness, service decomposition, events, automation, configuration, and failure tolerance. |
| 83 | **Kubernetes: Up & Running** | Kelsey Hightower, Brendan Burns & Joe Beda | Kubernetes becomes understandable once you see it as a declarative control system built around desired state, controllers, scheduling, services, and reconciliation. |
| 84 | **Terraform: Up & Running** | Yevgeniy Brikman | Infrastructure automation succeeds when Terraform code is structured into reusable modules, isolated states, automated workflows, and safe environments. |
| 85 | **Systems Performance** | Brendan Gregg | Diagnose performance scientifically by understanding CPUs, memory, disks, networks, operating systems, workloads, observability, and measurement methodologies. |
| 86 | **Computer Systems: A Programmer’s Perspective** | Randal E. Bryant & David R. O’Hallaron | Better programmers understand how source code ultimately interacts with processors, memory, linking, processes, virtual memory, networks, and concurrency. |
| 87 | **Operating Systems: Three Easy Pieces** | Remzi H. Arpaci-Dusseau & Andrea C. Arpaci-Dusseau | Operating systems become understandable through the core ideas of virtualization, concurrency, and persistence. |
| 88 | **High Performance Browser Networking** | Ilya Grigorik | Application performance depends heavily on what actually happens across TCP, TLS, HTTP, browsers, mobile networks, latency, and bandwidth. |
| 89 | **Debugging** | David J. Agans | Difficult bugs become tractable when debugging is treated as disciplined hypothesis testing based on evidence rather than random changes. |
| 90 | **Software Architecture for Developers** | Simon Brown | Software architecture should be lightweight, understandable, explicitly communicated, and closely connected to the code developers actually build. |
| 91 | **Documenting Software Architectures: Views and Beyond** | Paul Clements et al. | Architecture documentation works best when different stakeholder concerns are represented through deliberately chosen views rather than one enormous diagram. |
| 92 | **Just Enough Software Architecture** | George Fairbanks | Architecture decisions should be driven by risk, with enough upfront reasoning to address expensive uncertainties without turning design into bureaucracy. |
| 93 | **The Software Architect Elevator** | Gregor Hohpe | Effective architects travel between executive strategy and implementation detail, translating business goals into technical decisions and technical realities back into business consequences. |
| 94 | **97 Things Every Software Architect Should Know** | Richard Monson-Haefel (ed.) | Architecture is less about drawing boxes than understanding trade-offs, communicating decisions, resisting accidental complexity, and helping teams make better choices. |
| 95 | **AI Engineering** | Chip Huyen | Building production systems with foundation models is primarily an engineering problem involving evaluation, retrieval, agents, latency, cost, data, observability, and continuously changing model behavior. |
| 96 | **Designing Machine Learning Systems** | Chip Huyen | Production ML systems must treat data, training, deployment, distribution shift, monitoring, feedback, and infrastructure as one lifecycle rather than focusing only on model accuracy. |
| 97 | **Machine Learning Design Patterns** | Valliappa Lakshmanan, Sara Robinson & Michael Munn | Reusable patterns help solve recurring engineering problems in data representation, training, serving, reproducibility, resilience, and ML pipelines. |
| 98 | **Reliable Machine Learning** | Cathy Chen et al. | Machine-learning systems need the same production disciplines as conventional software—testing, observability, failure handling, reproducibility, deployment safety, and incident response. |
| 99 | **Building Machine Learning Powered Applications** | Emmanuel Ameisen | Successful ML products begin with clearly defined product objectives and iterative baselines before escalating to increasingly sophisticated models. |
| 100 | **Shape Up** | Ryan Singer | Software teams can often deliver better by giving small autonomous teams fixed time and flexible scope instead of endlessly grooming backlogs and estimating tasks. |

## Philosophy

A book earns a place here when it contributes a durable mental model: complexity, boundaries, feedback, failure, data, reliability, security, organizational design, or engineering judgment. Some classics remain valuable because of the questions they teach you to ask even when their concrete prescriptions have aged.

## Contributing

Disagree with the ranking, the sentence, or an omission? Good. Open an issue or PR and make the case. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

The original summaries and repository text are licensed under the [MIT License](LICENSE). Book titles and author names belong to their respective owners. No book text is reproduced here.
