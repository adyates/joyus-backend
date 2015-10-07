# joyus-backend
An experiment in configurable backend design, starting off with Hapi

# Why?

So the fun of any backend is figuring out how you are going to organizae your code so other people can mess around with it.  Most backends have a couple of mental models in mind for dealing with stuff:
  - Magical ORM, or some sort of persistence abstraction
  - Request handlers
  - Some form of API
  - Sessions
  - Integrations with 3rd party services
  - Internal business logic services
  - Ponies
  
And then you have testing:
  - Unit testing simply services
  - Mocking out requests
  - Stubbing out the persistence layer
  - Parallelism if you can swing it
  - More Ponies
  
So, much like how fizzbuzz-the-musical is a place to mess around with a bunch of languages, joyus-backend is hopefully the place to experiment with a few backends to see what patterns emerge.  Of course, it won't have the code throughput that a series of Fizz Buzz programs can do, it should hopefully be useful to... well, me at least.
