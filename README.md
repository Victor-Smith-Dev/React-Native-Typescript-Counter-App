![Header Tech](https://i.ibb.co/k6kDkdk/image.png)

# Description / Descripción

En este proyecto encontrarás una aplicación **básica**, que se ocupa de un simple contador. Sin embargo, esto puede servir como plantilla para iniciar un proyecto, ya que se basa en un texto mecanografiado, o simplemente para crear una **aplicación de prueba**.

En este proyecto se uso:

1. Componentes Funcionales.
2. Hooks.
3. Código especifico para cada plataforma.
4. Estilos de React Native.
5. Interafces.

## Vista previa

![Vista Previa](https://i.ibb.co/RCXsfhF/gif.gif)

## Scripts Disponibles

### `npm install | npm i | yarn install`

Ejecutar este script en la raiz del proyecto para instalar las dependencias neceasarias.

### `npm run ios`

Ejecutar este script en la raiz del proyecto para desplegar la app para **IOS**.

### `npm run android`

Ejecutar este script en la raiz del proyecto para desplegar la app para **Android**.

## Desarrollo de componentes:

### `Pantalla de contador`

![Pantalla de contador](https://i.ibb.co/6rX0Kh3/image.png)

En esta pantalla, se hace uso del hook useState nativo de React, adcionalmente se importa el componente para mostrar los botones con la funcionalidad de incrementar o decrementar, el cual es reutilizado con propiedades particulares.

### `Componente FAB (Floating Action Button)`

![Componente FAB (Floating Action Button)](https://i.ibb.co/1ZWhPzn/image.png)

En este componente es donde ocurre toda la magia de la app, en el mismo se desarrollan componentes funcionales especificos para cada plataforma.

### `Estilos de los FAB`

![Estilos de los FAB](https://i.ibb.co/L5TDFZ6/image.png)

Estos estilos pertenecen a los Floating Action Button que se usaron para ejecutar el contador que renderiza en la pantalla principal.

## Particular de cada plataforma

Al momento de realizar esta practica el componente `<TouchableOpacity />` tenia ciertos inconvenientes para el funcionamiento en `Android` así que se usó `<TouchableNativeFeedback />` para logras una mejor visualización en ambas plataformas.

### `FAB IOS`

![FAB IOS](https://i.ibb.co/k8gCpYJ/image.png)

### `FAB ANDROID`
![FAB ANDROID](https://i.ibb.co/2Zbyc0v/image.png)


