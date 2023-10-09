# Beyond Request/Response: Why and how we should change the way we build web applications

Chris Nelson &mdash; *Co-Founder and Principal Engineer*

- [Twitter](http://twitter.com/superchris)
- [LinkedIn](https://www.linkedin.com/in/chris-nelson-038875/)
- [Website](https://launchscout.com/blog)

## Bio

Chris Nelson is the Co-Founder of Launch Scout, an agile software development firm in Cincinnati. He heads up the company’s apprenticeship program, mentors young developers and sets technology direction. What does he love most about his job? Sharing what he’s learned from over 20 years developing software across a wide range of industries. Chris has given workshops across the country and spent time teaching at Dev Bootcamp in Chicago. He’s spoken at conferences including Elixirconf, RailsConf, RubyConf, JavaOne, CodeMash and Scottish Ruby Conf.

## Abstract

As web developers, we’ve been building web applications the same way for 25 years. We send a request, and we receive a response. We might get a whole page back, or we might get some data to render, but the common thread for almost every web application that has ever been built is the request/response cycle. What if we didn’t have to do it this way? What kind possibilities would open up to us?

In this session, we’ll take a simple, existing design pattern that you are probably already familiar with even if you don’t know it by name: the Event/State Reducer pattern. You’ve already used it if you’ve worked with Redux or Elm. We are going to stretch this pattern just a little: we will publish events from the client, use reducer functions on the server to compute our new state, and subscribe to these state changes on the client.

We’ll explore this idea with several code examples that gradually increase in complexity. We’ll see how building collaborative and real-time applications becomes natural and straightforward. We’ll also see how to combine statically generated websites with interactive applications in a way that was difficult or impossible before. You can expect to come away with practical but hopefully mind expanding new approaches to building your next application. 


- **Level**: Intermediate
- **Tags**: Front-End &  Web, Patterns & Practices
  