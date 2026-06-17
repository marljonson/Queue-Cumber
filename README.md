# Queue-Cumber 🥒
A .NET distributed health tech pipeline.

Tech stack: `C#`, `ASP.NET Core`, `Blazor`, `Hl7.Fhir.R4`, `Microsoft SQL Server`, `EF Core`, `RabbitMQ`, `Microsoft Azure`
- Engineered a high-throughput RESTful Web API using ASP.NET Core to process 5,000+ simulated daily clinical data payloads
- Integrated Hl7.Fhir.R4 to dynamically parse and serialize relational database health records into standardized JSON FHIR formats
- Optimized query efficiency by 25% by configuring asynchronous message queues and repository patterns using EF Core and SQL Server
- Enforced enterprise security by implementing JWT and role-based access tokens to satisfy strict healthcare compliance standards

- Test git change after linking this repo to Visual Studio