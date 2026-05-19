# Angular Deep Dive

A collection of hands-on explorations into Angular internals - built to understand 
how the framework works under the hood, not just how to use it.

Inspired by the official Angular documentation, these examples are written and run 
locally to gain a deeper understanding of core concepts.

## Why this repo?

Reading docs is one thing. Making the code actually run and observing the behavior 
firsthand is another. These examples are built to answer the question: 
**"But how does it actually work?"**

## Examples

### `zone.js` — Manual change detection
A vanilla JavaScript implementation showing why Zone.js exists and what problem 
it solves, exploring:
- How Angular knows when to re-render
- Why async operations (XHR, setTimeout, Promises) require special handling
- What manual `detectChange()` looks like before Zone.js patches these APIs
- How Zone.js eliminates the need for manual change detection calls

## Stack
- TypeScript
- Angular
- Zone.js

## References
- [Angular Zone.js Guide](https://github.com/angular/angular/blob/17.3.x/aio/content/guide/zone.md)
