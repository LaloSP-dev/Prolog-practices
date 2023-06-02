# Prolog

Es un lenguaje de programación lógico e interpretado usado habitualmente en el campo de la Inteligencia artificial.

## Programación en Prolog

Hay dos tipos de cláusulas: Hechos y Reglas.

```prolog
Cabeza :- Cuerpo.
```

esto se lee como "La cabeza es verdad si el cuerpo es verdad". El cuerpo de una regla consiste en llamadas a predicados, que son los objetivos de las reglas. El predicado ,/2 (esto es un operador que recibe dos argumentos).

## Consola
Forma de correr prolog en consola:
```bash
PS\Peliculas: swipl
```
Ahora para correr un archivo como movies.pl es de la forma:

```bash
?- [movies].
true.
```

Para volver a cargar el archivo cuando se hace un cambio en el código:
```bash
?- make.
true.
```

Para salirnos el comando es: 
```bash
?- halt.
% The following threads wouldn't die: [gc]
```
tiene que ir un punto simpre al final de cada petición.
