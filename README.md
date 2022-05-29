# Lab 3 Topicos Telematica 
## Requisitos previos:
* Par de claves EC2
* Bucket S3 
## Creación del clúster en AWS
* Configuración

![image](https://user-images.githubusercontent.com/53055930/170852268-6dba8ef0-ac16-45c3-b119-c785ef95f9e5.png)

![image](https://user-images.githubusercontent.com/53055930/170852293-06f0146e-dc49-4012-adc9-6d424976ae2f.png)
* Seguridad
![image](https://user-images.githubusercontent.com/53055930/170852307-e086ab87-ce1d-4561-bf55-aa4b6528e3a9.png)
![image](https://user-images.githubusercontent.com/53055930/170852387-b4222855-6847-460f-a094-79bab6725b2a.png)
![image](https://user-images.githubusercontent.com/53055930/170852422-35230399-8419-4b0e-8e62-54a29f6df20b.png)


### Activacion Cluster

![image](https://user-images.githubusercontent.com/53055930/170852458-06d321b5-ead8-4770-a663-7c34a3e394d2.png)


### Conexion con Hue 
![image](https://user-images.githubusercontent.com/53055930/170852528-7bfda6b6-233e-4155-9e11-9839ab0c59c2.png)

## Gestión de archivos hacia HDFS y AWS S3
### Hacia HDFS via SSH 
* Entrar a la isntancia del master con el comando SSH
![image](https://user-images.githubusercontent.com/53055930/170852577-98bed633-0aa5-4b4a-a371-a815a7bf39a4.png)

* Subir los datos al HDFS
![image](https://user-images.githubusercontent.com/53055930/170852594-8590f1e6-7ddb-4cf7-9616-bcf8d520c60b.png)

![image](https://user-images.githubusercontent.com/53055930/170852599-9a43632b-dc4c-4363-9543-452a9e771abf.png)

![image](https://user-images.githubusercontent.com/53055930/170852603-ad5c7e37-a7fe-4b50-a3f9-0ed1066909ae.png)

### Hacia HDFS via HUE

![image](https://user-images.githubusercontent.com/53055930/170852633-607733a6-b697-46e8-bfb8-cbefc997588b.png)
![image](https://user-images.githubusercontent.com/53055930/170852636-82af57d4-d737-4710-a914-2b521ab082d3.png)
![image](https://user-images.githubusercontent.com/53055930/170852646-a245ff8a-246d-484e-8390-6ad70c9a5639.png)

### Hacia AWS S3 via SSH  
![image](https://user-images.githubusercontent.com/53055930/170852691-ff37e8ab-d7ae-4b0f-8660-2459b5987f8c.png)

* Comprobar que esta todo correcto
![image](https://user-images.githubusercontent.com/53055930/170852718-3b54231d-11e7-4eb0-96b2-1336df19b895.png)


### Hacia AWS S3 via HUE

![image](https://user-images.githubusercontent.com/53055930/170852674-fab7640c-bc17-4d5c-bb94-6dcc5472b27c.png)

### Bucket S3
![image](https://user-images.githubusercontent.com/53055930/170852739-e714a6a3-3036-42dc-b5a2-6574331f8d60.png)

[Link de un archivo](https://valdedatos.s3.amazonaws.com/datasets/export-data.csv)


