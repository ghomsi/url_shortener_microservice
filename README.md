# Author
![@ghomsi](https://avatars2.githubusercontent.com/u/4965336?v=3&s=460)

Created by ghomsi

[Github](https://github.com/ghomsi) | [FreeCodeCamp](https://www.freecodecamp.com/ghomsi) | [CodePen](http://codepen.io/adrienDev/) | [E-Mail](mailto:kemchepatou@gmail.com)

# FreeCodeCamp API Basejump: URL Shortener Microservice

## User stories:
1. I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
2.  If I pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain an error instead.

## Example creation usage:

```js
https://little-url.herokuapp.com/new/https://www.google.com
https://little-url.herokuapp.com/new/http://foo.com:80
```
## Example Example creation output:
```js
{ "original_url":"http://foo.com:80", "short_url":"https://little-url.herokuapp.com/8170" }
```
## Example usage
```js
https://little-url.herokuapp.com/2871
```
## Will redirect to:
```js
https://www.google.com/
```