# Queue-Cumber 🥒
A .NET distributed health tech pipeline.

Tech stack:
- `C#`
- `ASP.NET Core` foundational web framework
- `Blazor` frontend UI framework
- `Hl7.Fhir.R4`, specialized .NET library for healthcare data compatibility
- `Microsoft SQL Server` to provide secure, persistent, transactional storage for app data
- `EF Core` object-relational mapper to bridge C# code and LINQ queries into raw SQL database commands
- `RabbitMQ` message broker to handle asynchronous communication
- `Microsoft Azure` for cloud deployment

Accomplishments:
- Engineered a high-throughput RESTful Web API using ASP.NET Core to process 5,000+ simulated daily clinical data payloads
- Integrated Hl7.Fhir.R4 to dynamically parse and serialize relational database health records into standardized JSON FHIR formats
- Optimized query efficiency by 25% by configuring asynchronous message queues and repository patterns using EF Core and SQL Server
- Enforced enterprise security by implementing JWT and role-based access tokens to satisfy strict healthcare compliance standards