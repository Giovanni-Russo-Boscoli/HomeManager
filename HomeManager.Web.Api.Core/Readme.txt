Web.Api.Core - Maps to the layers that hold the Use Case and Entity 
concerns and is also where our External Interfaces get defined. 
These innermost layers contain our domain objects and business rules.
The code in this layer is mostly pure C# - no network connections, 
databases, etc. allowed. Interfaces represent those dependencies, 
and their implementations get injected into our use cases as we'll 
see shortly.

https://fullstackmark.com/post/18/building-aspnet-core-web-apis-with-clean-architecture