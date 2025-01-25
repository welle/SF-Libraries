# Lightning Web Component: PubSub

To communicate between components that are not in the same DOM tree, we use a singleton library that follows the publish-subscribe pattern.

In a publish-subscribe pattern, one component publishes an event while the other components subscribe to receive and handle the event. 
Every component that subscribes to the event receives the event. 
Let's say, you have two components to a Lightning page in App Builder, then use the pubsub module to send events between them. 

Pubsub is not given by default, you have to add it to by yourself. 