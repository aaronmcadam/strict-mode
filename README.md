# React Strict Mode examples

This repo demonstrates React Strict Mode.

## Double rendering during development

React ensures our components are resilient to unmounting and remounting by mounting, unmounting, and remounting them during development.

It helps make sure we clean up after ourselves in any effects. Things we might need to clean up include timers and event handlers.

The following video demonstrates this by building one component that doesn't clean up after itself (`BadStopwatch`) and another that does (`GoodStopwatch`):

- https://www.youtube.com/watch?v=j8s01ThR7bQ
