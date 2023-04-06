# How scalable is contract testing with specmatic?

In Jio, we've 4K+ contracts and it works pretty fast

# How is specmatic different from Pact?

specmatic.in/blog/comparisons/specmatic-vs-pact-io-and-pactflow-io

# Is it possible to do something like this for an event based system ?

Use asyncAPI

# How do you perform contract testing for asynchronous communication?

We can use asyncAPI

# If using mono-repo for my microservices, do you see any problem using the same repo for central contract repo ?

In my experience people typically use mono-repo for their microservices (provider) but their consumers can be in their own repo. So it is highly recommended we use a central git repo for the contracts (which is a single source of truth.)

# Is there a certain team size/stage that you'd say would not benefit enough from this style of development (CDD) to justify following it?

This is a very common question. Maybe I'm biased, but I think small team size makes collaboration easy, however on small team you might not have the bandwidth to manually write a lot of API tests. With specmatic we generate a lot of them for free (no-code.) Also the sooner you make this a practice, as the team scales, it becomes easy to manage contracts.

# How about the producer has already finished building the api and deployed it before the consumer. I don't see why the contract is needed?

1. Producer is finished and deployed. However when the consumer is build their stuff, they would not want to depend on an actual deployment of the provider in their CI pipeline and locally. Test data management is a huge challenge. Also simulation several negative scenarios becomes challenging. 2. In future when provider changes, how do you ensure those changes won't break the consumer? Or for that matter that those changes are expected changes and not some accidental changes?

# Any tips for GraphQL API contract testing?

We have not addressed GraphQL yet, but certainly on our list. Specmatic's architecture is such that we can add new protocols easily. Is this something you would like to contribute?

# How to support different versions of contracts?

Yes, we recommend you use semantic versioning for your APIs. Specmatic understand versioning and each consumer can define which version they depend on in their specmatic.json file.

# How do you handle more complex semantics? E.g. a sequence of operations that need to produce an outcome.

You would handle each one in isolation first, make sure each one is working as expected. Then you would use a workflow test to run them in sequence to make sure the final result is what you expected.

# How would you approach test-data consistency / integrity in UAT envs ? My experience is teams owning the service can provide basic test data, e.g. out of contract  test, but consumers typically need specific use cases which aren't covered.

Sure, so you would still do those types of tests in the higher testing env. However, we ensure that in the lower env we have tackled all the contract and individual API level stuff. Reduce the problem space and hence improve the effectiveness of testing in each env.

# Is this not like API Gateway/Manager

API Gateway generally concerns with North / South traffic Service mesh is really interested with East / West or service to service within a domain

# How does service mesh influence latency?Can you use it in low latency contexts?

There is always an impact on latency, but you need to think about what you get the benefits for that latency. There are ways of limiting the latency, such as using non application protocol aware L4, but with this comes limitation on traffic shaping and observability

# is the service mesh following the zero trust approach?

Yes, Zero Trust is a core principle of Service Mesh. Traffic should be tightly controlled and the source identifiable
