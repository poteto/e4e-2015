## Keynote - Better Work Through Better Feedback
Keavy McMinn @keavy

### Asking for feedback
- What exactly do you want feedback on? Be explicit.
- When do you want feedback? Is your PR WIP (are you on the right direction?) or ready for review?
- Who do you want feedback from? Whose knowledge, expertise and point of view would you like?

### Giving feedback

When commenting on PRs, and giving feedback in general:

- Wait a few minutes, especially if you disagree
- Ask, don't tell (critique, not criticize)
- Be humble
- Explain reasons for changes to give context
- Use positive language over neutral, as it can be seen as negative
- Use emojis!!!
- Disapproval Matrix - Ann Friedman
  
  ![](http://i.imgur.com/4GWln11.jpg)
- Empathize 

## Functional JavaScript
Ben Anderson @ben_anderson

### The future has to be functional
- DOM is stateful & imperative
- UI layer should be pure – same output for a given input
- Immutable.js provides immutable collections for JS
- Immutable.record as an immutable model for your domain instead
- Services and queries take data and transform it, without mutating the original data
- Your app is a pipeline that processes data, and should be deterministic
- Redux is predictable and behaves consistently, and has a time traveling debugger (!)

## How to Study Design Patterns
Colin Williams, TripAdvisor

- It is not studying design patterns by thinking all you have to do is learn the pattern
- Every decision made in a design pattern is the best choice (for that situation), so it is important to know the reason why that pattern is the best for the problem
- Design patterns are always best on a local scale, but can sometimes be the worst in relation to the surrounding code

### Observer Pattern
- Should the Subject be able to serialize and send its state to its Observers? Depends on the broader context, for example, in a micro-service architecture.

### Mediator Pattern
- The Observer Pattern can lead to deep complexity, when Subjects can also be Observers themselves
- The Mediator Pattern takes the logic that is generalized, and consolidates them into one place so that they can interop. 

