
Реализуйте статический метод `MakeItFunny()` в классе `App`, который принимает на вход строку и возвращает её копию, у которой каждый n-ный элемент переведен в верхний регистр. n – задается на входе в функцию. Для определения каждого n-ного элемента понадобится остаток от деления `%`. Подумайте, как его можно использовать.

```cs
var text = "I never look back";
// Каждый третий элемент
App.MakeItFunny(text, 3); // "I NevEr LooK bAck"
```