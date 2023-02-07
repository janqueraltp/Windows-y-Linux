<div id='id100' />

# Práctica 1: Direcciónes IP y MAC en Windows y Linux

 ## **Índice**
 1. [Ubuntu](#id1)  
 1.1 [Conocer mi IP](#id2)  
 1.2 [Conocer direccion MAC](#id3)  
 1.3 [Spoofing Ubuntu](#id4)  
 2. [Windows](#id5)  
 2.1 [Conocer mi IP](#id44)  
 2.2 [Conocer direccion MAC](#id45)  
 2.3 [Spoofing Windows](#id46)



<div id='id1' />

# Ubuntu :computer:



<div id='id2' />

## Conocer mi IP :shipit:
![image](img/img1.png)

<div id='id3' />

## Conocer mi direccion MAC
Abrir aplicacion RED. Donde pone direccion fisica, eso es nuestra direccion MAC
![image](img/img2.png)


<div id='id4' />

## 1.1 Spoofing Ubuntu

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
![image](https://user-images.githubusercontent.com/116662838/217329696-b05ac2ed-bc33-4c50-ad09-d741ad95b039.png)



<div id='id5' />

# Windows :computer:


<div id='id44' />

## Conocer mi IP :shipit:

```
ipconfig
```
![image](https://user-images.githubusercontent.com/116662838/217331043-93213ccb-f993-4307-a12d-00d666d85f17.png)



<div id='id45' />

## Conocer direccion MAC
***Configuracion / Estado de red / Propiedades***  

![image](img/Captura.PNG)









# [Volver arriba ⬆️](#id100)  
