# CurrencyJS
Create HTML option tag list all currency, update new currency from ISO website

##How to use it 

##### Include **Cerrency.js** to your project

##### HTML code :

> `<select class="currency"></select>`

##### Javascript Code :

> var container = document.querrySelector('select.currency');

> var currentCurrency = 'USD';

> new Currency(container, currentCurrency, false);

##### The result :

```
<select class="currency">
	....
	<option value="USD" selected >USD</option>
	....
</select>

```

Note : if you want to see the country name just set the last para to true, the result will like :

```
<select class="currency">
	....
	<option value="USD" selected >UNITED STATES</option>
	....
</select>

```

