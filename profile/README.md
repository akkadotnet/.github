# Akka.NET

![Akka.NET Logo](/profile//akkalogo.png)

Akka.NET is a .NET port of the popular [Akka project](https://akka.io/) from the Scala / Java community. We are an idiomatic [.NET implementation of the actor model](https://petabridge.com/blog/akkadotnet-what-is-an-actor/) built on top of the .NET Common Language Runtime.

We are a [.NET Foundation member project](https://dotnetfoundation.org/projects/akkadotnet).

[![Discord](https://img.shields.io/discord/974500337396375553?style=flat&logo=discord&label=Join%20Akka.NET%20Discord)](https://discord.com/invite/GSCfPwhbWP)

* **Website**: [https://getakka.net/](https://getakka.net/)
* **Twitter** 🐦: [AkkaDotNet](https://twitter.com/AkkaDotNet)
* **Discussions** 📣: [Akka.NET GitHub Discussions](https://github.com/akkadotnet/akka.net/discussions)
* **Chat** 💬: [Akka.NET on Discord](https://discord.gg/GSCfPwhbWP)
* **StackOverflow** ✔️: [Akka.NET on StackOverflow](https://stackoverflow.com/questions/tagged/akka.net)

## How is Akka.NET Used?

Akka.NET can be used in-process or inside large, distributed real-time systems; we support a wide variety of use cases.

Akka.NET can be used to solve the following types of problems:

1. **Concurrency** - Akka.NET actors only process messages one-at-a-time and they do so in first in, first out (FIFO) order; this means that any application state internal to an actor is automatically thread-safe without having to use `lock`s or any other shared-memory synchronization mechanisms.
2. **Stream Processing** - Akka.NET actors and [Akka.Streams](https://getakka.net/articles/streams/introduction.html) make it easy to build streaming applications, used for processing incoming streams of data or incoming streams of live events such as UI or network events inside native applications.
3. **Event-Driven Programming** - actors make it easy to build event-driven applications, as actors' message-processing routines naturally express these types of designs.
4. **Event Sourcing and CQRS** - [Akka.Persistence](https://getakka.net/articles/persistence/architecture.html), used by actors to make their state re-entrant and recoverable across restarts or migrations between nodes, natively supports event sourcing. [Akka.Persistence.Query](https://getakka.net/articles/persistence/persistence-query.html) can be used to compute CQRS-style projections and materialized views from Akka.Persistence data.
5. **Location Transparency** - [Akka.Remote](https://getakka.net/articles/remoting/index.html) makes it simple for actors in remote processes to transparently communicate with each other.
6. **Highly Available, Fault-Tolerant Distributed Systems** - [Akka.Cluster](https://getakka.net/articles/clustering/cluster-overview.html), [Akka.Cluster.Sharding](https://getakka.net/articles/clustering/cluster-sharding.html), and other tools built on top of Akka.Cluster make it possible to build highly available and fault-tolerant distributed systems by leveraging peer-to-peer programming models with topology-aware message routing and distribution.
7. **Low Latency, High Throughput** - Akka.NET aims to be low latency and high throughput, processing 10s millions of messages per second in-memory and hundreds of thousands of messages per second over remote connections.

## Where Can I Learn Akka.NET?

You can start by taking the [Akka.NET Bootcamp](https://learnakka.net/), but there are many other great [learning resources for Akka.NET Online](https://getakka.net/community/online-resources.html).

* [Petabridge's Akka.NET Videos on YouTube](https://www.youtube.com/c/PetabridgeAcademy)
* "[.NET Conf - When and How to Use the Actor Model An Introduction to Akka.NET Actors](https://www.youtube.com/watch?v=0KnIMDoJpZs)"
* _[Reactive Applications with Akka.NET](https://www.manning.com/books/reactive-applications-with-akka-net)_
* _[Akka.NET Succinctly](https://www.syncfusion.com/succinctly-free-ebooks/akka-net-succinctly)_

## Getting Help
Need help with Akka.NET? Please [see our `SUPPORT.md` file](SUPPORT.md) for places you can go to get support for you and your company.

## Contribuing to Akka.NET

If you'd like to contribute to Akka.NET, please take a look at [our contribution guidelines](https://getakka.net/community/contributing/index.html)!
