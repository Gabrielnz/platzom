# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educacion online.

## Descripcion del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras.
- Si la palabra inicia con Z, se le anade "pe" al final.
- Si la palabra traducida tiene 10 o mas letra, se debe partir en dos  por la mitad y unir con un guion medio.
- Por ultimo, si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayusculas y minusculas.

## Instalacion

```
npm install @bladelizard/platzom
```

## Uso

```
import platzom from '@bladelizard/platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Creditos
- [Gabriel Nunez](https://twitter.com/@bladelizzard)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
