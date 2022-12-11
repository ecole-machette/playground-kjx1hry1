# Exercice d'opération

Déterminez le prix TTC

```php runnable
<?php
    // Prix en €
   $prix_ht = 50;
   // TVA en %
   $tva = 20;
   $prix_ttc = ($prix_ht * $tva / 100) + $prix_ht;
   echo 'Le prix TTC du produit est de '.$prix_ttc.' €.';
?>
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced PHP template](https://tech.io/select-repo/574)
