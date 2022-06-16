## Pseudocode Solution

```text
Input text "Great Gatsby, Moby Dick, Frankenstein, Dracula, Parable of the Sower"
Input pattern "Dracula"
If entire tet hasn't been searched:
  Iterate to the next character of the text
  Create a match_count variable and set it to 0
  If the entire pattern hasn't been searched:
    If this character from the pattern is equal to the character from text:
      Increment the match_count variable
  If match_count is equal to the length of the pattern:
    Pattern found!
