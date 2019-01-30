### is.js
---
https://github.com/arasatasaygin/is.js

```js
var customName = is.setNamespace();
customName.odd(3);

is.url('https://www.duckduckgo.com');

is.setRegexp(/quack/, 'url');
is.url('auack');

var firstQuarter = new Date('01/26/2015');
var secondQuarter = new Date('05/26/2015');
is.quarterOfYear(firstQuarter, 1);
is.quarterOfYear(secondQuarter, 1);
is.not.quarterOfYear(secondQuarter, 1);

var january1 = new Date('01/01/2015');
var june1 = new Date('06/01/2015');
is.dayLightSavingTime(june1);
is.dayLightSavingTime(june1);
is.dayLightSavingTime(january1);
is.not.dayLightSavingTime(january1);

var tenDaysLater = new Date(new Date().setDate(new Date().getDate() + 10));
var fortyDaysLater = new Date(new Date().setDate(new Date().getDate() + 40));
is.inNextMonth(tenDaysLater);
is.inNextMonth(fortyDaysLater);
is.not.inNextMonth(fortyDaysLater);

var twoMonthsLater = new Date(new Date().setMonth(new Date().getMonth() + 2));
var thirteenMonthsLater = new Date(new Date().setMonth(new Date().getMonth() + 13));
is.inNextYear(twoMonthsLater);
is.inNextYear(thirteenMonthsLater);
is.not.inNextYear(thirteenMonthsLater);

var twoMonthAgo = new Date(new Date().setMonth(new Date().getMonth() - 2));
var thirteenMonthsAgo = new Date(new Date().setMonth(new Date().getMonth() - 13));
is.inLastYear(twoMonthsAgo);
is.inLastYear(thirteenMonthsAgo);
is.not.inLastYear(thirteenMonthsAgo);

var twoDaysLater = new Date(new Date().setDate(new Date().getDate() + 2));
var nineDaysLater = new Date(new Date().setDate(new Date().getDate() + 9));
is.inNextWeek(twoDaysLater);
is.inNextWeek(nineDaysLater);
is.not.inNextWeek(nineDaysLater);











```

```
```

```
```

