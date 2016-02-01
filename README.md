# is.brazil.js

Micro library for Brazilian check based on [is.js](https://github.com/arasatasaygin/is.js)

### Usage
```javascript
is.br.rg('911225341');
=> true

is.br.cep('2312301');
=> false

is.br.boleto('3000111.12.92938282');
=> false

is.br.carnaval('04/02/2015');
=> true

is.br.pascoa('12/02/2015');
=> false
```
