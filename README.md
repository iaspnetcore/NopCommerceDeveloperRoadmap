# Guide to Learn NopCommerce step by step for NopCommerce Developer

In this tutorial you’ll set up and deploy a production-ready ASP.NET Core application NopCommerce with a MongoDb Server on Ubuntu 18.04 using Nginx.


## Resources

1. Prerequisites

   - [C#](https://www.pluralsight.com/paths/csharp)
   - [Entity Framework](https://www.pluralsight.com/search?q=entity%20framework%20core)
   - [ASP.NET Core](https://www.pluralsight.com/search?q=asp.net%20core)
   - SQL Fundamentals

2. Install
   1. .NET 6.x
   - Learn GIT, create a few repositories on GitHub, share your code with other people
   - Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)
   - [How to Install and uninstall reinstall  upgrade .NET 6.x on Ubuntu 18.04*64 step by step](https://www.iaspnetcore.com/Blog/BlogPost/618a75d3635c733c81dc77c3/how-to-install-and-uninstall-reinstall-upgrade-net-6x-on-ubuntu-180464-step-by-step)
   - Learn [dotnet CLI](https://docs.microsoft.com/en-us/dotnet/core/tools/?tabs=netcore2x)
   - Read a few books about algorithms and data structures

3. Dependency Injection

   1. DI Containers
      - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-2.2)
      - [AutoFac(used by nopcommerce)](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
      - [Ninject](http://www.ninject.org/)
      - [StructureMap](https://github.com/structuremap/structuremap)
      - [Castle Windsor](https://github.com/castleproject/Windsor)
   2. [Life Cycles](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-2.2#service-lifetimes)
   3. [Scrutor](https://github.com/khellang/Scrutor)

4. Databases

   1. Relational
      1. [SQL Server(used by nopcommerce)](https://www.microsoft.com/en-us/sql-server/sql-server-2017)
      2. [PostgreSQL](https://www.postgresql.org/)
      3. [MariaDB](https://mariadb.org/)
      4. [MySQL](https://www.mysql.com/)
   2. Cloud Databases
      - [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db)
      - [DynamoDB](https://aws.amazon.com/dynamodb/)
   3. Search Engines
      - [ElasticSearch](https://www.elastic.co/)
      - [Solr](http://lucene.apache.org/solr/)
      - [Sphinx](http://sphinxsearch.com/)
   4. NoSQL
      - [MongoDB](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-2.2&tabs=visual-studio)
      - [Redis](https://redis.io/)
      - [Apache Cassandra](http://cassandra.apache.org/)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
      - [RavenDB](https://github.com/ravendb/ravendb)
      - [CouchDB](http://couchdb.apache.org/)

5. Caching

   1. Entity Framework 2nd Level Cache
      1. [EFSecondLevelCache.Core](https://github.com/VahidN/EFSecondLevelCache.Core)
      2. [EntityFrameworkCore.Cacheable](https://github.com/SteffenMangold/EntityFrameworkCore.Cacheable)
   2. [Distributed Cache](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/distributed?view=aspnetcore-2.2)
      1. [Redis(used by nopcommerce)](https://redis.io/)
      2. [Memcached](https://memcached.org/)
   3. [Memory Cache](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-2.2)

6. Logging

   1. Log Frameworks
      - [Serilog](https://github.com/serilog/serilog)
      - [NLog](https://github.com/NLog/NLog)
      - [Elmah](https://elmah.github.io/)
      - [own Log Frameworks]nopCommerce uses its own logging implementation (available in admin area)
   2. Log Management System
      - [Sentry.io](http://sentry.io)
      - [Loggly.com](https://loggly.com)
      - [Elmah.io](http://elmah.io)

7. Template Engines
   1. [Razor](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/razor?view=aspnetcore-2.2)
   2. [DotLiquid](https://github.com/dotliquid/dotliquid)
   3. [Scriban](https://github.com/lunet-io/scriban)
   4. [Fluid](https://github.com/sebastienros/fluid)
8. Real-Time Communication

   1. [SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr)

9. Object Mapping

   - [AutoMapper(used by nopcommerce)](https://github.com/AutoMapper/AutoMapper)
   - [Mapster](https://github.com/MapsterMapper/Mapster)
   - [AgileMapper](https://github.com/agileobjects/AgileMapper)
   - [ExpressMapper](http://expressmapper.org/)

10. API Clients

    1. REST
       - [OData](https://blogs.msdn.microsoft.com/odatateam/2018/07/03/asp-net-core-odata-now-available/)
       - [Sieve](https://github.com/Biarity/Sieve)
    2. GraphQL
       - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

11. Good to Know

    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation(used by nopcommerce)](https://github.com/JeremySkinner/FluentValidation)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [Polly](https://github.com/App-vNext/Polly)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [GenFu](https://github.com/MisterJames/GenFu)

12. Testing

    1. Unit Testing
       1. Frameworks
          - [MSTest](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-mstest)
          - [NUnit](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-nunit)
          - [xUnit](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test)
       2. Mocking
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       3. Assertion
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
          - [Shouldly](https://github.com/shouldly/shouldly)
    2. Behavior Testing
       - [BDDfy](https://github.com/TestStack/TestStack.BDDfy)
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
       - [LightBDD](https://github.com/LightBDD/LightBDD)
    3. Integration Testing
       - [WebApplicationFactory](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-2.2)
       - [TestServer](https://koukia.ca/integration-testing-in-asp-net-core-2-0-51d14ede3968)
    4. E2E Testing
       - [Selenium](https://www.automatetheplanet.com/webdriver-dotnetcore2/)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)

13. Task Scheduling

    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Coravel](https://github.com/jamesmh/coravel)
    - [Fluent Scheduler](https://github.com/fluentscheduler/FluentScheduler)
    
14. MicroServices

    1. Message-Broker
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview)
    2. Message-Bus
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [CAP](https://github.com/dotnetcore/CAP)

15. SOLID

    - [Single Responsibility Principle (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [Open-Closed Principle (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [Liskov Substitution Principle (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [Interface Segregation Principle (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [Dependency Inversion Principle (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

16. Design-Patterns
    - [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
    - [Decorator](https://www.dofactory.com/net/decorator-design-pattern)
    - [Strategy](https://www.dofactory.com/net/strategy-design-pattern)
    - [Observer](https://www.dofactory.com/net/observer-design-pattern)
    - [Builder](https://www.dofactory.com/net/builder-design-pattern)
    - [Singleton](https://www.dofactory.com/net/singleton-design-pattern)
    - [Facade](https://www.dofactory.com/net/facade-design-pattern)
    - [Mediator](https://www.dofactory.com/net/mediator-design-pattern)
17. NopCommerce Extensions
     - [nopCommerce v4.10 asp.net core 3 blazor server-side(single page eStore)](https://github.com/aybelanov/spaCommerce)
    
    

## Wrap Up

If you think the roadmap can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to star this repository to revisit.

Idea from : [React Developer RoadMap](https://github.com/adam-golab/react-developer-roadmap)

## Contribution

Want to contribute? We encourage community feedback and contributions. Please follow our [contributing guidelines](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap/blob/master/CONTRIBUTING.md).

## Credits

### Contributors

This project exists thanks to all the people who contribute. [[Contribute](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap/blob/master/CONTRIBUTING.md)].

<img src="https://opencollective.com/AspNetCore-Developer-Roadmap/contributors.svg?width=890&button=false" />

### Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/AspNetCore-Developer-Roadmap#backer)]

<a href="https://opencollective.com/AspNetCore-Developer-Roadmap#backers" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/backers.svg?width=890"></a>

### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/AspNetCore-Developer-Roadmap#sponsor)]

<a href="https://opencollective.com/AspNetCore-Developer-Roadmap/sponsor/0/website" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/sponsor/0/avatar.svg"></a>

### mozilla firefox download url


<a href="http://ftp.mozilla.org/" target="_blank">http://ftp.mozilla.org/</a>

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
