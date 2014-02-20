# Tops eSport!

## Syfte
Här tänkte jag att vi kunde använda för att börja jobba fram en plan för utveklingen av Tops-eSport.se. Denna fil kan med fördel delas upp senare så att den inte blir för stor och svårläst

### Frågor
Fyll på med frågor som ni kommer på under tiden gång

1. Vad ska sidan använda till?
    * Skriv svar här: 
    * Svar: 
2. Vem bygger vi sidan till?
    * Svaret här

### Att göra lista
Här kan vi skriva upp vad som ska göras vad som är gjort och vad som är på gång
- [x] Är genomfört
- [ ] Inte genomfört

### Förslag till kodningsstandard
Här kan vi ange vad hur våran kod ska standardiseras eller stil sättas eller huir man nu utrycker sig. Tex. hur koden ska indenteras? vart vill vi ha måsvingarna i en funktion? hur ska html indenteras osv.

```javascript
 var s = "JavaScript syntax highlighting";
 alert(s);
```

```php
class TestThing
{
    public $objectProperty;

    public function methodName() {
    }
}

function function_name( $argument = null ) {

}
```

##### Strängar
När en sträng blir för lång bör den delas upp för bättre läslighet. Det är speciells användbart på sql strängar. 

```php
$sql = "SELECT `id`, `name` from `people` "
. "WHERE `name`='Fred' OR `name`='Susan'";
```

##### PhpDocumentor
[PhpDocumentor](http://phpdoc.org/) ska användas så mycket som möjligt.

```php
/**
 * @var \ArrayObject|\DateTime[]
 */
$dates = array()

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
```

### Referenser
* För att skriva i denna fil bör man vara vad [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) är.

