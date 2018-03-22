# GraphQL Outside the Box

Talk given at Reactathon 2018

By: Tyler Martinez, slightlytyler@gmail.com

### Synopsis

At Docker, we are using GraphQL alongside our existing REST APIs and making it work without a GraphQL server. Instead, we use GraphQL client side, where it serves as the interface to our network layer and the glue that binds our components together. We have taken this approach as a progressive solution to the difficult problem of introducing GraphQL to an existing application stack. By breaking the rules a bit we gain many of the benefits that GraphQL provides immediately while spreading out the implementation over many releases. While a novel approach I also envision a future where running GraphQL on the client is not uncommon. With the advent of blockchain technology and the concept of “dapps” we must reconsider the role of the application that runs on the end user’s device. By running GraphQL on the client we can consume remote GraphQL services, interact directly with the blockchain, browser / native APIs, and more through GraphQL.
