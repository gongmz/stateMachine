stateMachine

A feature-rich, yet simple finite state machine (FSM) implementation in C.

For when a simple switch statement just isn't enough. [Documentation](http://misje.github.io/stateMachine).

### TODO:

1. 事件缓冲队列，另外还需要考虑中断中发送事件的场景；
2. 多级的状态调用；
3. 目前状态支持条件状态变换，一个event只对应一种跳转方式，不是很灵活；
