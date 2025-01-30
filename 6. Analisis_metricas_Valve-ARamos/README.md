
# Proyecto Final analisis de Datos - Analisis de reseñas  sobre los juegos de VALVe

### Dataset utilizados

#### Steam reviews
https://www.kaggle.com/datasets/andrewmvd/steam-reviews
![{D15B1885-B60C-4A4F-9A2E-E8FDFF12128D}](https://github.com/user-attachments/assets/57e424c4-43c4-4ace-9e1c-c195496bb55e)


#### CS reviews
https://www.kaggle.com/datasets/noahx1/csgo-steam-reviews
![{740CD28F-E47F-4AAC-BCA6-0C8BA3164EF0}](https://github.com/user-attachments/assets/a4492afb-ebc9-4c72-b649-06cc0f00df1e)


### Bases de Datos utilizadas
#### MongoDB
![{5A59DAC0-E9FE-4EA7-9531-37350B8F0511}](https://github.com/user-attachments/assets/09875d86-7a00-48fe-a95c-d3c637d62c98)


#### CouchDB
![{5FBDFB87-52F9-4F0E-9AC8-6A2B045381CA}](https://github.com/user-attachments/assets/73b8c4d5-bf53-4ed8-b392-b12a25e9cd80)


#### MySQL Workbench
![{5EF706C4-7FA3-4A39-B062-6010092188E4}](https://github.com/user-attachments/assets/3073dc99-9fc3-4140-b492-6fddbdaa4161)


#### SQL Server
![{3E707BCC-A16B-4ED3-B036-791C2A7752FF}](https://github.com/user-attachments/assets/e386630b-b2fe-43d7-92c3-6c573dbec3ff)



### Recoleccion de Datos
Con el uso de pandas y las diferentes librerias de conexion de las bases de datos se realizaron diferentes dataFrames para seleccionar los datos del dataset principal de kaggle. 
Los datos seleccionados fueron Juegos de VALVe, los cuales se podian identificar por un app_id.
Una vez recolectados los diferentes dataFrames se concatenaron en uno solo y se almacenaron en MongoDB.
![{7EB67766-44B4-4D6D-B41B-8B6B8480F516}](https://github.com/user-attachments/assets/2dc03d27-4104-467b-af7b-3a19294863c1)


### Limpieza de Datos
Una recomendacion es realizar la Limpieza de datos antes de guardarlos en alguna base de datos.
![{BEF99519-D933-4455-ADC1-975C18CB3A37}](https://github.com/user-attachments/assets/1d150ceb-d7cd-4ab5-a94f-c4b9c4b31a8f)


### Trasplazo de Datos
Una vez realizado la Limpieza se procede a repartir la informacion en las diferentes bases de datos planteadas.
#### MySQL Workbench
![{3D1BAC94-A586-49B4-A904-7959F1D4ABD3}](https://github.com/user-attachments/assets/9c943db0-7c55-4502-9067-908d1ee7a4ac)
#### Microsoft SQL Server
![{A43E3D29-DFD6-4A06-AE7C-BC9FCCCCF313}](https://github.com/user-attachments/assets/65b5acc3-a687-4891-a999-fcf141bbb51e)
#### CouchDB
![{1F4C2EE4-AC2B-4AB6-985D-861BD594C884}](https://github.com/user-attachments/assets/9b18e86c-d750-4c60-b548-13177bf445a0)


### Graficacion de Datos
Traer los datos para realizar su analisis general, de sentimientos, y de concurrencia de palabras.
#### Grafico general de las reseñas de todos los juegos de VALVe
![{47DAD932-7C14-4381-B61A-DB2373B71540}](https://github.com/user-attachments/assets/b172a662-e7f8-40b2-92b0-a1813fc30715)
#### Grafico de relacion entre reseñas positivas, negativas y neutras de cada juego
![{FCE7E4C4-604E-42E0-8185-307618D4F82B}](https://github.com/user-attachments/assets/51560ee7-35ec-4985-af44-d966345cd813)
#### Grafico de los juego con mas reseñas
![{C0926D1E-AE30-491E-82E4-C74B1B5E64B1}](https://github.com/user-attachments/assets/6ee82390-992d-4e9e-8a50-328cd3e12afc)
#### Grafico de Nube de las palabras mas usadas
![{81C05F18-7715-4A97-A7B5-F6AF9436E2A6}](https://github.com/user-attachments/assets/fa5b679a-17c6-4f5d-80ef-9b53d10cad23)
#### Juego con peor relacion en base a su cantidad de reseñas
![{CFA2BB66-FAEA-4403-8426-A9FD1C6FD2F7}](https://github.com/user-attachments/assets/9bb3b981-2f2a-4fba-b2b0-0caa53a1fe7d)
#### Juego con mejor relacion en base a su cantidad de reseñas
![{AD03C288-D308-4042-9CA7-2038DFA82DEF}](https://github.com/user-attachments/assets/33f66af6-d795-4ee8-aeef-91f5704a99ed)


