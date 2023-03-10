<div id='id100' />

# Práctica 1: Direcciónes IP y MAC en Windows y Linux
### Jan Queralt e Ivan Molina

 ## **Índice**
 1. [***Ubuntu***](#id1)  
 1.1 [Conocer mi IP](#id2)  
 1.2 [Conocer direccion MAC](#id3)  
 1.3 [Spoofing Ubuntu](#id4)  
 2. [***Windows***](#id5)  
 2.1 [Conocer mi IP](#id44)  
 2.2 [Conocer direccion MAC](#id45)  
 2.3 [Spoofing Windows](#id46)



<div id='id1' />

# Ubuntu :computer:



<div id='id2' />

# Conocer mi IP :shipit:

```
hostname -i
```
![image](img/img1.png)

<div id='id3' />

# Conocer mi dirección MAC
### Abrir aplicación RED. Donde pone dirección física, eso es nuestra dirección MAC
![image](img/img2.png)


<div id='id4' />

# 1.1 Spoofing Ubuntu

### Abrimos la terminal
![image](img/img3.png)

```
ip link show
```
![image](img/img4.png)


```
sudo ip link set dev ens33 address 74:d0:3b:9f:d8:48
```
![image](img/img5.png)


```
ip link show
```
![image](img/img6.png)



<div id='id5' />

# Windows :computer:


<div id='id44' />

# Conocer mi IP :shipit:

```
ipconfig
```
![image](img/img7.png)



<div id='id45' />

# Conocer dirección MAC
***Configuración / Estado de red / Propiedades***  

![image](img/Captura.PNG)



# Spoofing Windows
1. Entrar a Administrador de Dispositivos.  
2. Seleccionar el apartado de Adaptadores de Red.  
3. Escogemos la interfaz de red a la que queremos cambiar la dirección MAC.  
4. Hacemos clic derecho en lo escogido y seleccionamos la opción «Propiedades«.  
5. Pasamos a la pestaña «Opciones Avanzadas«, luego a la cajita de «Propiedad» y nos encontraremos con Direcciones Administradas Localmente o Locally Administered Address  
6. Fíjate en el campo de texto (Valor) en donde se encuentra la dirección MAC y siéntete libre de borrarlo y cambiarlo  
7. Acto seguido, vuelve a introducir la dirección MAC de tu preferencia, respetando el formato y sin separadores/espacios.  
8. Reinicia el ordenador  
9. Vuelve a ejecutar el cmd  
10. Escribes «ipconfig/all» y listo: dirección MAC alterada.  


<div id='id46' />

# [Volver arriba ⬆️](#id100)  
