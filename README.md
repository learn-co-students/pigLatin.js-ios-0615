# Pig Latin

![smart pig photo](https://s3-us-west-2.amazonaws.com/web-dev-readme-photos/js-vowels/pig-latin.jpg)

## Background

Pig Latin is a made-up children's language that's intended to be confusing. It obeys a few simple rules (below) but when it's spoken quickly it's really difficult for non-children (and non-native speakers) to understand.

* **Rule 1**: If a word begins with a vowel sound, add an "ay" sound to the end of the word.
* **Rule 2**: If a word begins with a consonant sound, move it to the end of the word, and then add an "ay" sound to the end of the word.

There are a few more rules for edge cases, and there are regional variants too.

See [this Wikipedia article](http://en.wikipedia.org/wiki/Pig_latin) for more details.

## Objectives

Create a function, `pigLatin`, that turns a string in English into Pig Latin. It should behave as seen in the examples below.

## Examples

If the string starts with a vowel, just add "ay" to the end of the string:

```javascript
pigLatin('apple')
// => 'appleay'
```

If the string starts with a consonant, move the consonant to the end and add "ay":

```javascript
pigLatin('jiffy')
// => 'iffyjay'
```

If the string starts two or more consonants, move them to the end then add "ay":

```javascript
pigLatin('thrice')
// => 'icethray'
```

If the string contains multiple words, translate each word separately:

```javascript
pigLatin('we are the change that we seek')
// => 'eway areay theay angechay atthey eway eeksay'
```

## Instructions

Run your testing suite to get started.

## Resources

* [Wikipedia](http://en.wikipedia.org/) - [Pig Latin](http://en.wikipedia.org/wiki/Pig_latin) 
* [MDN JavaScript Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/) - [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

<a href='https://learn.co/lessons/pigLatin.js' data-visibility='hidden'>View this lesson on Learn.co</a>
