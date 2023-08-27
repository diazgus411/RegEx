# RegEx Tutorial Starter Code                                                                                    ![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description

For this assignment, I decided to explain what this RegEx does and how it works. `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` This RegEx is used to validate hexadecimal color codes in HTML and CSS. Simply said, it will match a valid color code for hexadecimal and reject an invalid color code. Now lets break down what the phrase above means; '/' is simply used to start the regular expression. '^' is used to indicate the beggining of the hexadecimal string. '#' is used to match the literal character that is being used in the string or expression. '?' is used to match the previous token, '#', optional in the string. '()' is used to capture the contents of a group. ([a-f0-9]{6}|[a-f0-9]{3}): This is a grouping that matches either a six-digit hexadecimal color code or a three-digit hexadecimal color code. This is what the individual components mean. [a-f0-9], matches any character that is a lowercase letter from "a" to "f" or a digit from "0" to "9". This is the variety of characters used in hexadecimal notation. {6} specifies that the preceding character group should appear six times exactly. This makes it match a complete six-digit color code for hexadecmial. {3}, specifies that the preceding character group should appear three times. This matches a three-digit color code for hexadecimal. Lastly, '$' is used to match the end of the string, while the '/' component is used to end the regular expression (RegEx).
In conclusion, this RegEx is used to validate hexadecimal color codes in HTML and CSS. It will match a valid color code for hexadecimal and reject an invalid color code. Every time hexadecimal color codes are used in HTML and CSS, this RegEx is used to validate the color code. and is a very common RegEx used in HTML, CSS, and JavaScript.

## Table of Contents
- [Description](#description)
- [License](#license)
- [Links](#links)

## License
MIT

## Links
For more information, visit our GitHub page: [diazgus411](https://github.com/diazgus411/RegEx)