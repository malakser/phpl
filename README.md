# PHPL - "spolszczony" interpreter PHP
Do zmiennych można się odnosić nie tylko w dolarach (`$`), lecz również w złotówkach (`zł`, `PLN`).

## Użycie
Poniższy kod wypisuje "`Litwo, ojczyzno moja! ty jesteś jak zdrowie;`":

```php
    <?php
        foo zł = "moja";
        bar PLN = "zdrowie";
        echo("Litwo, ojczyzno " . foo zł . "! ty jesteś jak " . bar PLN . ";\n");
    ?>
```
    

