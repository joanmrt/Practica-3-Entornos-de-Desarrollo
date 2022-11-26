# Practica-3-Entornos-de-Desarrollo

He hecho un repositorio desde cero, donde he metido un .txt con 3 versiones diferentes para cada commit.

![imagen](https://user-images.githubusercontent.com/74322611/204100490-82d0e482-40d7-465e-a6a8-1edf5e9ed412.png)

Ahora empezaremos con los comandos de la práctica.


## 1. git tag


Vamos a etiquetar el primer commit y el tercer commit "v1" y "v2" respectivamente.

![imagen](https://user-images.githubusercontent.com/74322611/204101472-84a31c53-96b0-4bbe-86c2-a8c85dada66d.png)


He usado el comando de tag correspondiente, pero como el comentario no es muy descriptivo voy a borrarlo y volver a meterle un mensaje mejor.

![imagen](https://user-images.githubusercontent.com/74322611/204101599-21791f77-ebfd-44f1-98c9-641d244ebbdf.png)


## 2. Usar etiquetas para movernos


Nos podemos mover más fácilmente gracias a los tags, ya que no tenemos que poner el hash de cada commit.

![imagen](https://user-images.githubusercontent.com/74322611/204101686-4c7cae9e-45d5-4e66-b423-700627b19a5b.png)


## 3. git show


Este comando nos ayudará a saber los cambios sobre el anterior commit. En mi caso solo hice 3 commits; uno con una linea que ponía "Version 1", el sgundo con otra "Version 2" y una tercera con "Version 3".

![imagen](https://user-images.githubusercontent.com/74322611/204102124-70fa1c15-ecd0-4443-8733-7ee160c16a1b.png)

![imagen](https://user-images.githubusercontent.com/74322611/204102156-34808475-0146-467e-b6b9-6bea3d53c54d.png)

Aquí se puede ver como en el v1 se añade el archivo al repositorio con la línea "Version 1" y v2 se añaden las otras dos líneas.


## 4. git diff


Este comando nos dirá todos los cambios entre un rango de commits.

![imagen](https://user-images.githubusercontent.com/74322611/204102365-9937c337-9438-4530-acb8-00baa3f939a8.png)


## 5. Diferencia entre diff y show


![imagen](https://user-images.githubusercontent.com/74322611/204102418-0db1e894-29a9-4ee7-bd7b-118735a03b98.png)

El comando "git show v1..v2" nos muestra por pantalla todos los cambios de los commits respecto el anterior desde v1 hasta v2, es decir los cambios del primer commit con el anterior, el segundo con el anterior, y el tercero con el anterior.
El comando "git diff v1..v2" nos muestra solo los cambios que ha habido desde el primer commit hasta el tercero, no lo compara con el anterior.
