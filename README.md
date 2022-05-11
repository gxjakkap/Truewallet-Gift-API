# [truewalletgiftredeemer](https://yarn.pm/truewalletgiftredeemer)

Forked from [manybaht/Manybaht-Truewallet-API](https://github.com/manybaht/Manybaht-Truewallet-API).

## Installation
```bash
$ yarn add truewalletgiftredeemer
```

or

```bash
$ npm i truewalletgiftredeemer
```

## วิธีใช้งาน

```javascript
import twg from 'truewalletgiftredeemer'

//ตัวอย่าง
twg.redeemvouchers('phone_number', 'giftvoucher/link')
.then(res => {
    console.log(res);
});

/*
Response
{ status: 'SUCCESS', amount: recieved amount }
{ status: 'FAIL/ERROR', reason: why it failed }
*/
```