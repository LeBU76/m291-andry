# Prédictions — e1-6 Prédis avant de cliquer

Règle : j’écris ma prédiction **avant** de cliquer sur Lancer.

## Extrait 1 — Afficher

```js
document.getElementById("out1").textContent = "Bonjour la classe";
```

- Je pense que l’écran / la console va montrer :
- Ce qui s’est passé :
- Si je me suis trompé, pourquoi (une phrase) :

## Extrait 2 — Calculer

```js
let a = 4;
let b = 3;
let total = a + b;
document.getElementById("out2").textContent = total;
```

- Je pense que l’écran / la console va montrer :
- Ce qui s’est passé :
- Si je me suis trompé, pourquoi (une phrase) :

## Extrait 3 — Compter

```js
let fruits = ["pomme", "poire", "kiwi"];
document.getElementById("out3").textContent = fruits.length;
```

- Je pense que l’écran / la console va montrer :
- Ce qui s’est passé :
- Si je me suis trompé, pourquoi (une phrase) :

## Extrait 4 — Condition

```js
let note = 5;
let texte;
if (note >= 4) {
  texte = "suffisant";
} else {
  texte = "insuffisant";
}
document.getElementById("out4").textContent = texte;
```

- Je pense que l’écran / la console va montrer :
- Ce qui s’est passé :
- Si je me suis trompé, pourquoi (une phrase) :

## Extrait 5 — Boucle simple

```js
let message = "";
for (let i = 1; i <= 3; i = i + 1) {
  message = message + i + " ";
}
document.getElementById("out5").textContent = message;
```

- Je pense que l’écran / la console va montrer :
- Ce qui s’est passé :
- Si je me suis trompé, pourquoi (une phrase) :

## Extrait 6 — Clic

```js
let n = 0;
document.getElementById("b6").addEventListener("click", function () {
  n = n + 1;
  document.getElementById("out6").textContent = n;
});
```

- Je pense que le nombre va (après plusieurs clics) :
- Ce qui s’est passé :
- Si je me suis trompé, pourquoi (une phrase) :

<!-- Pour les rapides : décommente cette partie
## Extrait 7 — inventé par moi (4 lignes max)

```js

```

- Prédiction de mon camarade (prénom) :
- Ma prédiction :
- Ce qui s’est passé :
-->
