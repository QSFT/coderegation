---
speaker: Elena Kelareva
topic: Product Management for APIs - lessons learnt from the Google Maps API
video: https://vimeo.com/148339305
issue: 14
---

There has been increased interest in recent years in building APIs to turn products into platforms. This session will help you to evaluate whether an API would benefit your product by examining potential benefits of an API, such as driving adoption, enabling niche use cases and opening up new revenue streams.

This session will also help you set a product strategy for your API, give a high-level overview of API design considerations, and present several issues to watch out for, such as differences between web and native mobile APIs, dealing with authentication and abuse, and what to do if your API ends up being too popular or not popular enough.

Notes of our discussion
-----------------------

* It was quite interesting to follow Elena's suggestion and go through each of our APIs and review what benefits they bring to the three groups: the company, the developers using the APIs and the end users.
* https://www.hyrumslaw.com/ and the obligatory XKCD (https://xkcd.com/1172/) came up: no matter what you document, people will start to depend on every observable behavior of your API
* We talked a lot about supportability and the safety of APIs and plugins.
* In regards to safety, we agreed that (a) we need to be prepared and protect against malicious plugins/API users -- and we already do that, and (b) we need to protect the developers against shooting themselves in the foot.
* It is the developers using our APIs who should provide support for the solutions they build on top of those APIs. The problem in our case is that it's sometimes hard to find a developer who would want to create that solution.
* An API by itself cannot act as a safety valve that frees you from overloading your solution with things few people would use. You also need professional services/partners that are able to make use of that API.
* A possible way to make the developers' lives easier would be introducing a plugin store. Plugins could be uploaded for a fee, and in exchange we'd review the code and run automated tests to ensure compatibility through upgrades.
