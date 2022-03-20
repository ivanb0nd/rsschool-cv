# Ivan Bondarev

## Contacts

- Location: Barnaul, Russia
- Phone: +7 960 948 26-12
- Email: ivanboarthrills@gmail.com
- GitHub: [ivanb0nd](https://github.com/ivanb0nd)

## About me

Trying to become a Front-End Developer.

## Skills

- HTML5, CSS3
- JavaScript
- SASS/SCSS
- Git
- Figma 


## Code example

**Code wars kata**

Detect Pangram

A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant).

Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

```
function isPangram(string) {
  let lettersCode = string
                      .toLowerCase()
                      .split('')
                      .filter((i) => /\w/.test(i))
                      .map((i) => i.charCodeAt() - 96)

  for (let i = 1; i < 26; i++) {
    if (!lettersCode.includes(i)) {
      return false;
    }
  }
  return true;
}
```

## Experience

Nothing yet

## Education
- FreeCodeCamp 
  - Responsive Web Design Certification
  - JavaScript Algorithms and Data Structures
- JavaScript Manual on [JavaScript.ru](https://learn.javascript.ru/)

## Language

- English level - A2
