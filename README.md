# Tops eSport!

## Syfte
Här tänkte jag att vi kunde använda för att börja jobba fram en plan för utveklingen av Tops-eSport.se

### Frågor
Fyll på med frågor som ni kommer på under tiden

1. Vad ska sidan använda till?
..* Skriv svar här: 
..* Svar: 
2. Vem bygger vi sidan till?
..* Svaret här

### Förslag till kodningsstandard
Här kan vi ange vad hur våran kod ska standardiseras eller stil sättas eller huir man nu utrycker sig. Tex. hur koden ska indenteras? vart vill vi ha måsvingarna i en funktion? hur ska html indenteras osv.

```javascript
 var s = "JavaScript syntax highlighting";
 alert(s);

```php
class TestThing
{
    public $objectProperty;

    public function methodName() {
    }
}

```php
function function_name( $argument = null ) {

}


##### Strängar
När en sträng blir för lång bör den delas upp för bättre läslighet. Det är speciells användbart på sql strängar

```php
$sql = "SELECT `id`, `name` from `people` "
. "WHERE `name`='Fred' OR `name`='Susan'";


##### PhpDocumentor
[PhpDocumentor](http://phpdoc.org/) ska användas så mycket som möjligt.

```php
/**
 * @var \ArrayObject|\DateTime[]
 */
$dates = array()


```php
<?php
 /**
  * En kort beskrivning av funktionen
  *
  * En längre beskirvning om det behövs. Detta kan tas bort om den inte används
  *
  * @param string $myArgument Skriv gäran en beskrivning vad den förväntas innehålla.
  *
  * @return void
  */
  function myFunction($myArgument) {
  }


### Referenser
* För att skriva i denna fil bör man vara vad [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) är.

## License
(The MIT License)

Copyright (c) 2012 Juraj Vitko (http://ypocat.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.