MassTransit
===========

MassTransit is a _free, open-source_ distributed application framework for .NET. MassTransit makes it easy to create applications and services that leverage message-based, loosely-coupled asynchronous communication for higher availability, reliability, and scalability.

![Mass Transit](https://avatars2.githubusercontent.com/u/317796?s=200&v=4 "Mass Transit")

MassTransit is Apache 2.0 licensed.

## Documentation

Get started by [reading through the documentation](https://masstransit-project.com/).

Build Status
------------

| Branch        |                                                                                                Status                                                                                                      |
|---------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| master        |    [![master](https://github.com/MassTransit/MassTransit/actions/workflows/build.yml/badge.svg?branch=master&event=push)](https://github.com/MassTransit/MassTransit/actions/workflows/build.yml)          |
| develop       |   [![develop](https://github.com/MassTransit/MassTransit/actions/workflows/build.yml/badge.svg?branch=develop&event=push)](https://github.com/MassTransit/MassTransit/actions/workflows/build.yml)         |
| documentation | [![documentation](https://github.com/MassTransit/MassTransit/actions/workflows/docs.yml/badge.svg?branch=develop&event=push)](https://github.com/MassTransit/MassTransit/actions/workflows/docs.yml)       |
| net7.0        | [![MassTransit](https://github.com/fineksus-ahmetulusoy/MassTransit/actions/workflows/build.yml/badge.svg?branch=net7.0)](https://github.com/fineksus-ahmetulusoy/MassTransit/actions/workflows/build.yml) |

MassTransit NuGet Packages
---------------------------

| Package Name                                                    | .NET | .NET Standard | .NET Framework |
|-----------------------------------------------------------------|:----:|:-------------:|:--------------:|
| **Main**                                                        |      |               |                |
| [MassTransit][MassTransit.nuget]                                | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Abstractions][MassTransitAbstractions.nuget]       | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Newtonsoft][MassTransitNewtonsoft.nuget]           | 7.0  |      2.1      |     4.8.0      |
| **Other**                                                       |      |               |                |
| [MassTransit.Analyzers][Analyzers.nuget]                        |      |      2.1      |                |
| [MassTransit.Templates][Templates.nuget]                        | 7.0  |               |                |
| [MassTransit.SignalR][SignalR.nuget]                            | 7.0  |               |     4.8.0      |
| [MassTransit.Interop.NServiceBus][MassTransitNServiceBus.nuget] | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.TestFramework][TestFramework.nuget]                | 7.0  |      2.1      |     4.8.0      |
| **Monitoring**                                                  |      |               |                |
| [MassTransit.Prometheus][Prometheus.nuget]                      | 7.0  |      2.1      |     4.8.0      |
| **Persistence**                                                 |      |               |                |
| [MassTransit.AmazonS3][AmazonS3.nuget]                          | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Azure.Cosmos][Cosmos.nuget]                        | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Azure.Storage][AzureStorage.nuget]                 | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Azure.Table][AzureTable.nuget]                     | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Dapper][Dapper.nuget]                              | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.DynamoDb][DynamoDb.nuget]                          | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.EntityFrameworkCore][EFCore.nuget]                 | 7.0  |      2.1      |                |
| [MassTransit.EntityFramework][EF.nuget]                         |      |      2.1      |     4.8.0      |     
| [MassTransit.Marten][Marten.nuget]                              | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.MongoDb][MongoDb.nuget]                            | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.NHibernate][NHibernate.nuget]                      | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Redis][Redis.nuget]                                | 7.0  |      2.1      |     4.8.0      |
| **Scheduling**                                                  |      |               |                |
| [MassTransit.Hangfire][Hangfire.nuget]                          | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Quartz][Quartz.nuget]                              | 7.0  |      2.1      |     4.8.0      |
| **Transports**                                                  |      |               |                |
| [MassTransit.ActiveMQ][ActiveMQ.nuget]                          | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.AmazonSQS][AmazonSQS.nuget]                        | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Azure.ServiceBus.Core][AzureSbCore.nuget]          | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.Grpc][Grpc.nuget]                                  | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.RabbitMQ][RabbitMQ.nuget]                          | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.WebJobs.EventHubs][EventHubs.nuget]                | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.WebJobs.ServiceBus][AzureFunc.nuget]               | 7.0  |      2.1      |     4.8.0      |
| **Riders**                                                      |      |               |                |
| [MassTransit.Kafka][Kafka.nuget]                                | 7.0  |      2.1      |     4.8.0      |
| [MassTransit.EventHub][EventHub.nuget]                          | 7.0  |      2.1      |     4.8.0      |

## Discord 

Get help live at the MassTransit Discord server.

[![alt Join the conversation](https://img.shields.io/discord/682238261753675864.svg "Discord")](https://discord.gg/rNpQgYn)

## GitHub Issues

**Pay attention**

Please do not open an issue on GitHub, unless you have spotted an actual bug in MassTransit. 

Use [GitHub Discussions](https://github.com/MassTransit/MassTransit/discussions) to ask questions, bring up ideas, or other general items. Issues are not the place for questions, and will either be converted to a discussion or closed.

This policy is in place to avoid bugs being drowned out in a pile of sensible suggestions for future 
enhancements and calls for help from people who forget to check back if they get it and so on.

## Building from Source

 1. Install the latest [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
 2. Clone the source down to your machine<br/>
    ```bash
    git clone https://github.com/MassTransit/MassTransit.git
    ```
 3. Run `dotnet build`

## Contributing

 1. Turn off `autocrlf`
    ```bash
    git config core.autocrlf false
    ```
 2. Hack!
 3. Make a pull request
 
# REQUIREMENTS
* .NET 7 SDK

# CREDITS
Logo Design by _The Agile Badger_

[MassTransit.nuget]: https://www.nuget.org/packages/MassTransit
[MassTransitAbstractions.nuget]: https://www.nuget.org/packages/MassTransit.Abstractions
[MassTransitNewtonsoft.nuget]: https://www.nuget.org/packages/MassTransit.Newtonsoft
[MassTransitNServiceBus.nuget]: https://www.nuget.org/packages/MassTransit.Interop.NServiceBus
[Analyzers.nuget]: https://www.nuget.org/packages/MassTransit.Analyzers
[Templates.nuget]: https://www.nuget.org/packages/MassTransit.Templates
[SignalR.nuget]: https://www.nuget.org/packages/MassTransit.SignalR
[TestFramework.nuget]: https://www.nuget.org/packages/MassTransit.TestFramework

[Prometheus.nuget]: https://www.nuget.org/packages/MassTransit.Prometheus

[Cosmos.nuget]: https://www.nuget.org/packages/MassTransit.Azure.Cosmos
[AzureStorage.nuget]: https://www.nuget.org/packages/MassTransit.Azure.Storage
[AzureTable.nuget]: https://www.nuget.org/packages/MassTransit.Azure.Table
[Dapper.nuget]: https://www.nuget.org/packages/MassTransit.DapperIntegration
[DynamoDb.nuget]: https://www.nuget.org/packages/MassTransit.DynamoDb
[EFCore.nuget]: https://www.nuget.org/packages/MassTransit.EntityFrameworkCore
[EF.nuget]: https://www.nuget.org/packages/MassTransit.EntityFramework
[Marten.nuget]: https://www.nuget.org/packages/MassTransit.Marten
[MongoDb.nuget]: https://www.nuget.org/packages/MassTransit.MongoDb
[NHibernate.nuget]: https://www.nuget.org/packages/MassTransit.NHibernate
[Redis.nuget]: https://www.nuget.org/packages/MassTransit.Redis

[Hangfire.nuget]: https://www.nuget.org/packages/MassTransit.Hangfire
[Quartz.nuget]: https://www.nuget.org/packages/MassTransit.Quartz

[ActiveMQ.nuget]: https://www.nuget.org/packages/MassTransit.ActiveMQ
[AmazonS3.nuget]: https://www.nuget.org/packages/MassTransit.AmazonS3
[AmazonSQS.nuget]: https://www.nuget.org/packages/MassTransit.AmazonSQS
[AzureSbCore.nuget]: https://www.nuget.org/packages/MassTransit.Azure.ServiceBus.Core
[Grpc.nuget]: https://www.nuget.org/packages/MassTransit.Grpc
[RabbitMQ.nuget]: https://www.nuget.org/packages/MassTransit.RabbitMQ
[EventHubs.nuget]: https://www.nuget.org/packages/MassTransit.WebJobs.EventHubs
[AzureFunc.nuget]: https://www.nuget.org/packages/MassTransit.WebJobs.ServiceBus

[Kafka.nuget]: https://www.nuget.org/packages/MassTransit.Kafka
[EventHub.nuget]: https://www.nuget.org/packages/MassTransit.EventHub
