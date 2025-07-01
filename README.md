# Audition

Audition is an AI code reviewer and linter. 

#### TODO

- Ability to flag critical pieces of code for review /* @audition [INSTRUCTIONS] */
- Hook directly into github actions
- Have some kind of 


## Example usage

Code:

```typescript

/**
 * @audition this is mission critical code. I want you to make sure that it's as tight and small as possible.
 */

const updatePost = () => {
  // TODO
}
```

CLI:

```bash
audition ./path/to/file.ts
```
