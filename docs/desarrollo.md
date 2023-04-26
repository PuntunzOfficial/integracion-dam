# Desarrollo

Durante todo el proyecto utilicé exclusivamente Unreal Engine, con el Blueprint Editor integrado y C++. Todos los activos se proporcionan en el motor y están bajo licencia de uso y venta gratuitos siempre que se usen en el juego y no solo se revendan. Para otros modelos 3D usé Blender.


![image](https://user-images.githubusercontent.com/64560568/231734587-6cd886b7-8c20-4170-886e-a873e4875df1.png)
Aquí hay solo un pequeño fragmento de la clase Blueprint para la animación de la araña, en el lado izquierdo hay funciones visibles que también se usan aquí para la parte principal del código, similar a cómo podemos llamar funciones en un estilo de programación más típico .


![image](https://user-images.githubusercontent.com/64560568/231734885-bda43aec-bdf8-4411-b06a-29479c0483d6.png)
Este es Quixel Bridge, es la herramienta de motor integrada que le permite importar y modificar activos 3D proporcionados por Epic Games (Unreal Engine)
![image](https://user-images.githubusercontent.com/64560568/231735383-c4304c9c-7a0f-4052-832e-824f50616661.png)


La única "herramienta" que utilicé fue YouTube y la documentación del motor proporcionada por Epic Games.
https://docs.unrealengine.com/5.1/en-US/


![image](https://user-images.githubusercontent.com/64560568/234611818-07218dc7-5b63-4a31-a8a1-8de6bfe26f01.png)
Después de encontrar un modelo 3D de araña adecuado y hacerlo funcionar para mi estilo de juego, y luego de terminar el código, pude colocarlo en la escena y aplicar el material correcto que le da su textura de madera/roca haciendo que la araña parezca antigua.

![image](https://user-images.githubusercontent.com/64560568/234612279-aa1dc14d-cf0b-4cae-8d12-f0ff477d0b62.png)
Aquí hay una parte del proceso de última etapa de cómo puedo modificar fácilmente el sol, su sombra e intensidad, cambiando fácilmente de un día a una noche sin causar que el juego se rompa o se cargue.
![image](https://user-images.githubusercontent.com/64560568/234612381-4b8adfd9-d152-4e91-bfeb-e9bb4ddce6a9.png)


![image](https://user-images.githubusercontent.com/64560568/234612780-d7aaac98-1363-46ff-a9d9-931d2c39610e.png)
Aquí está la otra parte importante del juego, el objetivo principal es escapar de la araña y encontrar la salida escondida en la isla, hay múltiples cruces que funcionan como llaves, y una vez que hayas encontrado suficientes, la puerta se abrirá.
![image](https://user-images.githubusercontent.com/64560568/234613236-9116b052-f0b3-4ac0-a1cc-a53a32d3baf7.png)
![image](https://user-images.githubusercontent.com/64560568/234613679-cd9e38b0-8d91-4251-8bb9-063296f64feb.png)

![image](https://user-images.githubusercontent.com/64560568/234614042-9f06ce80-239c-443e-a386-fe8ba163b59f.png)
Y finalmente terraformación. En Unreal Engine es muy fácil diseñar tus propias palabras, incluso si es una isla, todo lo que necesitas es saber qué herramientas usar y todo es intuitivo después.

Después de diseñar la forma y el aspecto de mi isla, agregué texturas (de código abierto) y está hecho más o menos, todo lo que se necesita hacer es establecer la compensación de altura para que en una pendiente más pronunciada la hierba se convierta en roca.
![image](https://user-images.githubusercontent.com/64560568/234617487-67ceba3b-1ffd-45c2-be15-6a3c0e2b2d51.png)


El último es el follaje, que también es relativamente fácil, después de usar los modelos de código abierto proporcionados, puedo colocarlos en una densidad aleatoria alrededor de la isla y luego limpiar los árboles que se cortan entre sí.

![image](https://user-images.githubusercontent.com/64560568/234613112-3b298131-d5f1-4083-8fab-dd23dabd08ec.png)
