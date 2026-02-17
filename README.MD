# threading model

#### Goals of this architecture
- interruptible rendering
- Prioritize high-priority events
- Avoiding UI blocking
- Make rendering more predictable

### use two different renders
- UI thread (often called main): The only thread that can manipulate host views.
- JavaScript thread: This is where React’s render phase, as well as layout, are executed.