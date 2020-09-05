# Repositorio del TFM del MCyP de Abraham S.C. en la URJC

En este repositorio se ha ido trabajando para el desarrolo del Trabajo Fin de Máster (TFM), del Máster de Ciberseguridad y Privadicadad (MCyP) de la Uiversidad Rey Juan Carlos (URJC)

* **Título:** DevSecOps en aplicaciones Docker y/o Kubernetes
* **Alumno:** Abraham Santana Cebrián
* **Tutor:** Micael Gallego Carrillo
* **Directora:** Marta Beltrán Pardo

#DevSecOps #Demo #TFM #MCyP #URJC #AWS #Docker #Kubernetes

A continuación se puede acceder a los vídeos correspondientes a la predefensa del TFM a decha de 05/09/2020:

* [Presentación de la defensa del TFM][presentacion]
* [Demo de la ejecucción exitosa del Pipeline DevSecOps][demoPipeline]

   [demoPipeline]: <https://youtu.be/HkFP6tAobp0>
   [presentacion]: <https://youtu.be/HkFP6tAobp0>


# Instrucciones

## 1. Instalación

Tan solo hace falta clonar el repo para poder disponer de la configuración necesaria para levantar el ecosistema DevSecOps.

```shell
git clone https://github.com/MCYP-UniversidadReyJuanCarlos/18-19_absace.git
```

## 2. Puesta en marcha

Una vez realizada la clonación del repo, tan solo hace falta levantar la configuración del esquema YAML en el fichero `docker-compose.yml` haciendo uso del siguiente comando:


```shell
docker-compose up 
```