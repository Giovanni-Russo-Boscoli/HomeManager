Web.Api.Infrastructure - Maps to the layers that hold the Database and Gateway concerns. 
In here, we define data entities, database access (typically in the shape of repositories), 
integrations with other network services, caches, etc. This project/layer contains the 
physical implementation of the interfaces defined in our domain layer.

Alright, we now have a skeletal solution spun up that looks to support the high-level layers 
requested by Clean Architecture - cool! 😎

https://fullstackmark.com/post/18/building-aspnet-core-web-apis-with-clean-architecture