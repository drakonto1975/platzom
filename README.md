# Platzom
Platzom es un idioma inventado para el curso de Fundamentos de JavaScript de [Platzi](http://www.platzi.com).
## Descripción del idioma
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas.
- Si la palabra termina en "ar", se le quitan esos dos caracteres.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unir con un guión del medio.

## Instalación
```
npm install platzom
```
## Uso
```
import platzon from 'platzom'
console.log(platzom("Programar")) // Program
console.log(platzom("Zorro")) // Zorrope
console.log(platzom("Zarpar")) // Zarppe
console.log(platzom("abecedario")) // abece-dario
console.log(platzom("sometemos")) // SoMeTeMoS
```
## Créditos
- [Milton Miranda Cruz](https://github.com/drakonto1975)

## Licencia

[MIT](https://opensource.org/licenses/MIT)