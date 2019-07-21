Конструктор `new Date` стандартно использует местную временную зону. Единственная важная вещь, которую нужно запомнить - это то, что месяцы начинаются с нуля.

Поэтому февраль обозначается числом 1.

```js run
let d = new Date(2012, 1, 20, 3, 12);
alert( d );
```