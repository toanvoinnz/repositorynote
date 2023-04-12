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

# Note
Technical Note 

