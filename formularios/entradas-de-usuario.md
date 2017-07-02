# Entrada de Usuario \(user input\)

Las acciones del usuario, como hacer clic en un enlace, pulsar un botón o la introducción de texto provoca eventos en el  DOM. Esta página explica cómo enlazar estos eventos a los controladores de eventos de los componentes utilizando la sintaxis de enlace de eventos de angular.

Corre el [ejemplo vivo](https://angular.io/generated/live-examples/user-input/eplnkr.html) o en este enlace el [ejemplo de descargar](https://angular.io/generated/zips/user-input/user-input.zip).

## linkBinding para eventos de entrada de usuario

Puede utilizar [enlaces de eventos angular](https://angular.io/guide/template-syntax#event-binding) para responder a cualquier [evento de DOM](https://developer.mozilla.org/en-US/docs/Web/Events). Muchos eventos DOM son activadas por el usuario. La unión a estos eventos proporciona una manera de conseguir la entrada del usuario.

Para unirse a un evento de DOM, rodear el nombre del evento DOM entre paréntesis y asignar un citado [comunicado plantilla](https://angular.io/guide/template-syntax#template-statements) a la misma.

El siguiente ejemplo muestra un suceso de unión que implementa un controlador de clic:

src / app / click-me.component.ts

```
<button (click)="onClickMe()">Click me!</button>
```



