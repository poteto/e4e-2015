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
