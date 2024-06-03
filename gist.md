# challenge-17-regex-Hex-value

Regex also known as regular expressions are special characters that define a search pattern.These characters are meant to make your code more dynamic. In the folowing README i will be explaining the regex for hex value.

## Summary
In this file I will be explaining the regex for a hex value.
the following characters are what i will be explaining .
Hex Value: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`
### Anchors
`/^#` and `$?` are both considered anchors. The ^ is used at the start and indicated that a string must start with this. the $ is used towards the end and asserts the pattern toward the end of the string. 
### Quantifiers
`/^#?`. the question mark implies a boolean value of 0 or 1.`[a-f0-9]{6},[a-f0-9]{3}` this quantifier indicated how many times the pattern macthes. If the ? is not appened the quantifier will match as many times as it can else it will become lazy.For example this can be used to distinguis between british and amercan spelling.
### Grouping Constructs
`([a-f0-9]{6}|[a-f0-9]{3})` The `()` groups the regular expression between them. The grouping treats multiple characters as a single unit. This can proof useful when extracting information using any programming language. 
### Bracket Expressions
`[a-f0-9]` Bracket expression is a regex that will match a specific pattern of characters (alphabetic, numeric, special characters, symbols etc..) defined within the brackets. A hyphen is usually used to set a range for the characters.
### Character Classes
`a-f0-9 `character classes only match one out of several characters defined in the set. A hyphen is used to describve a rfange of characters and there can be more than one range.
`[0-9]` This character class matches a single digit between 0 and 9
### The OR Operator
`[a-f0-9]{6}`|`[a-f0-9]{3}` is a boolean that matches either the expression before or after. for example it will allow 3 or 5 or both in a string,any varriation of those numbers are allowed.




## Author

https://github.com/Deividhow
My name is Deivid How and my goal is to be become a better developer by bieng able to handle a full stack project easier. I have learned to do js,css and html for fornt end and have learned node,express,sql abd many more things fr the backend. I will keep on striving to improve my skills with the languages I havew learned.
