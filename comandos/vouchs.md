# Vouchs

En servidores de recompensas, un vouch es una acreditación a algún usuario tras haber realizado algo como pagar un sorteo, alguna recompensa, etcétera.

Space proporciona herramientas para hacer la gestión de éstos más fáciles.

### Comandos

## Añadir vouchs

`/vouch add`

Añade un vouch a un usuario, esto solo funciona si el servidor no tiene establecido el método de vouchs en `Añadido automáticamente`.

**Parámetros**

| Nombre   | Tipo    | Descripción                            |
| -------- | ------- | -------------------------------------- |
| `alter`  | usuario | El alter al que añadir el vouch        |
| `reason` | texto   | La razón por la que le añades el vouch |
