Web.Api - Maps to the layers that hold the Web, UI and Presenter concerns. 
In the context of our API, this means it accepts input in the form of 
http requests over the network (e.g., GET/POST/etc.) and returns its 
output as content formatted as JSON/HTML/XML, etc. The Presenters contain 
.NET framework-specific references and types, so they also live here as 
per The Dependency Rule we don't want to pass any of them inward.

https://fullstackmark.com/post/18/building-aspnet-core-web-apis-with-clean-architecture