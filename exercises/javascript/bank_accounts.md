## Cuentas bancarias

Usando el siguiente objeto:

```javascript
let savingsAccount = {
    balance: 1000,
    interestRatePercent: 1,
    deposit: function addMoney(amount) {
        if (amount > 0) {
            savingsAccount.balance += amount;
        }
    },
    withdraw: function removeMoney(amount) {
        var verifyBalance = savingsAccount.balance - amount;
        if (amount > 0 && verifyBalance >= 0) {
            savingsAccount.balance -= amount;
        }
    }
};
```

Añade el método **printAccountSummary()** que devuelva el siguiente mensaje

```
Bienvenido,
Tu saldo es de $1000 y tu porcentaje de intereses es 1%
```

[Back](../../readme.md)