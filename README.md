---
languages: javascript
tags: strings, substitution
---

# Pig Latin
## Getting Started

Run `npm install`

## Tests

Review the `pigLatin.js` file inside the `lib` directory, and then the `pigLatin.spec.js` file inside the `spec` directory. Review each of the tests, and then start implementing your solutions to make each test pass in `pigLatin.js`.


Run `grunt watch` then edit your files. Grunt will watch for changes. Grunt
will only run tests that start with `it`. When you finish passing a test,
remove the `x` from `xit` to convert it to a runnable test.

## Background

Pig Latin is a made-up children's language that's intended to be confusing. It obeys a few simple rules (below) but when it's spoken quickly it's really difficult for non-children (and non-native speakers) to understand.

* **Rule 1**: If a word begins with a vowel sound, add an "ay" sound to the end of the word.
* **Rule 2**: If a word begins with a consonant sound, move it to the end of the word, and then add an "ay" sound to the end of the word.

There are a few more rules for edge cases, and there are regional variants too.

See <http://en.wikipedia.org/wiki/Pig_latin> for more details.
