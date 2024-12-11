## 3.5.0

* Add support for line breaks with unicode character u2028 (line separator). This line break type appears when copy pasting, for example, code from the IntelliJ IDE (and probably more software packages) 

## 3.4.0

* Improve remove bullets to remove Figma-created bullets. When you type the asterisk character, Figma will create a “list” of which you can also set up the list spacing. In previous versions, we only removed bullet-like characters (like •). Now we also remove Figma-created bullets.

## 3.3.0

* Have an extra command for “join with breaks”, because sometimes that is what you want

## 3.2.0

* Added new "Split words" feature to split a text layer into individual word layers
* Added new "Remove bullets" feature to remove bullets from text

## 3.1.2

* Fix issue with joined text, where the joined text would not end up on one line

## 3.1.1

* Fix some build shenanigans related to Typescript and dynamic pages

## 3.1

* Plugin now retains formatting of individual characters per line when splitting or joining text

## 3.0

* Initial release