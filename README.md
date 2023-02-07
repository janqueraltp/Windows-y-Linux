<div id='id100' />

# Práctica 1: Direcciónes IP y MAC en Windows y Linux

 ## **Índice**
 1. [Instalar Ubuntu](#id1)  
 1.1 [Conocer mi IP](#id2)  
 1.2 [Conocer direccion MAC](#id3)  
 1.3 [Spoofing Ubuntu](#id4)  
 2. [Windows](#id5)  
 2.1 [Conocer mi IP](#id44)  
 2.2 [Conocer direccion MAC](#id45)  
 4.1 [Spoofing Windows](#id6)  

# Ubuntu :computer:

<div id='id1' />

## 1. Instalar Ubuntu [^nota1]
[^nota1]: V-16.04.2

### Abrir VM Ware y Seleccionamos Crear Maquina Virtual :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844099-cbb00f1c-34ac-408f-98e1-4d6b58ebdb6b.png)
### Custom (Avanzado) :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844260-ec9ae651-b23c-427a-a508-f857dcf10591.png)
### Version por defecto :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844291-fa3f67e1-fa21-4bc2-b3fa-f1830aa57838.png)
### Seleccionamos ISO de Ubuntu :arrow_heading_down: [^nota1] 
![image](https://user-images.githubusercontent.com/116662838/215844368-946dfc13-999c-4562-a37c-cee02660b261.png)
### Número de procesadores :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844774-a94a1f2f-856b-40bf-a852-d0d9738a4067.png)
### 2GB RAM :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844802-10a25d97-f513-4a22-b7a8-5177dc5f95fa.png)
### Red NAT :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844829-d82a52fb-b2a3-485d-90dc-30a8d09a4598.png)
### LSI logic :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844854-d7a1aa19-2465-44b6-a4ef-84f002fd4833.png)
### SCSI :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844885-16add5d6-efa3-492d-ace0-635449c250b6.png)
### Nuevo disco :arrow_heading_down:
![image](https://user-images.githubusercontent.com/116662838/215844902-880d9391-9cbb-4655-852c-261f50e1468f.png)
![image](https://user-images.githubusercontent.com/116662838/215844955-36227e13-bc24-402a-9b4f-d125bac1ab8e.png)
## Instalado :white_check_mark:  
![image](https://user-images.githubusercontent.com/116662838/215845340-ea4bede9-7f60-4e9f-b2d1-94171983fa96.png)
![image](https://user-images.githubusercontent.com/116662838/215848843-0a5a1708-7729-4377-877e-e5f6f526a2ed.png)

<div id='id2' />

## Conocer mi IP :shipit:
![image](https://user-images.githubusercontent.com/116662838/215849402-d3e6192c-110c-440a-b103-2c2d036ff0ca.png)

<div id='id3' />

## Conocer mi direccion MAC
Abrir aplicacion RED. Donde pone direccion fisica, eso es nuestra direccion MAC
![image](https://user-images.githubusercontent.com/116662838/215849855-43a2babd-523e-47d3-ae60-5118511f9f01.png)


<div id='id4' />

## 1.1 Spoofing Ubuntu

### Abrimos la terminal
![image](https://user-images.githubusercontent.com/116662838/217061983-0cdebb16-a48b-4482-9b5d-bedee9bb1eb1.png)

```
ip link show
```
![image](https://user-images.githubusercontent.com/116662838/217329041-1c618914-23ea-42fd-9641-fbe226764ab5.png)


```
sudo ip link set dev ens33 address 74:d0:3b:9f:d8:48
```
![image](https://user-images.githubusercontent.com/116662838/217329626-eae44134-33c4-4ad8-8c44-5cc3a6af75eb.png)


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
![image](img/Captura.PNG)









# [Volver arriba ⬆️](#id100)  
