# hello-world-docker-action
repo para probar la implementacion de github actions
# Acción de docker Hello world

Esta acción imprime "Hello World" o "Hello" + el nombre de una persona a quien saludar en el registro.

## Entradas

### `who-to-greet`

**Obligatorio** El nombre de la persona a quién saludar. Predeterminado `"World"`.

## Outputs

### `time`

El tiempo en que lo saludamos.

## Ejemplo de uso

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
