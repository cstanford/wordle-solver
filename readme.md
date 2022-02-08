# Simple Wordle Solver

## To Run
`node wordle-solver.js <orderedLetters> <lettersToInclude> <lettersToExclude>`

## Parameters

### Ordered Letters
- your green letters in the wordle
- unknown letters are represented by `*`
- example: if you knew the first and last letters of the wordle, you can represent it by `f***e`

### Letters to Include
- your yellow letters in the wordle without spaces
- if not applicable pass `*`

### Letters to Exclude 
- your grey letters in the wordle without spaces
- if not applicable pass `*`

## Example

`node wordle-solver.js f***e ba krm`

output: 

```
letters: [
  { letter: 'f', index: 0 },
  { letter: '*', index: 1 },
  { letter: '*', index: 2 },
  { letter: '*', index: 3 },
  { letter: 'e', index: 4 }
]

include: [ 'b', 'a' ]
exlcude: [ 'k', 'r', 'm' ]
possible answers: [ 'fable' ]
```


