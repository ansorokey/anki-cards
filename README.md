# anki-cards
Text files formatted for use with Anki and Ankidroid

## What is Anki?
Anki is an in-depth flashcard studying application. You can check it out (here)[https://apps.ankiweb.net/].

## Text File Format
You can view the official documentation (here)[https://docs.ankiweb.net/intro.html]. Below will be a very brief overview of the most esectial 
Cards can be generated through Anki from a plain .txt file.
An anki flashcard can have multiple fields. A field should be separated from another by one of the following accepted separators:
```
| (pipe)
; (semicolon)
: (colon)
, (comma)
(tab)
(space) 
```
Separated fields would look like this:
```
Field one;Field two
Front;Back
```

## Examples
```
This will be on the front.;This will be on the back.

This will be another card's front.;This will be another card's back.

"If a card happens to have a separator inside a field; we can escape it by enclosing it within quotes.";And that will keep it safe.

"quotes also allow
for the use of new lines";within a single field
```
