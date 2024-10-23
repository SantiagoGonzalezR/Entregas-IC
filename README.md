# Entrega: Taller de CI/CD

## URL del repo con el código

- https://github.com/SantiagoGonzalezR/Taller-1-IC

## URL de los entornos

- Entorno inicial (env): http://protobootapp-env.eba-penqpjhv.us-east-2.elasticbeanstalk.com
- Entorno de produccion (prod): http://protobootapp-prod.eba-penqpjhv.us-east-2.elasticbeanstalk.com

## Evidencias y comentarios

### Jenkins

![image](https://github.com/user-attachments/assets/9a2d1bfd-52bd-490a-bdf8-8c32cd6bead3)

Imagen de la primera integracion de Jenkins despues del setup inicial

![image](https://github.com/user-attachments/assets/bbd30a43-6ca9-4c22-8dcd-a8cbb0c7d0ab)

Pruebas aceptadas, visualizadas desde Blue Ocean

![image](https://github.com/user-attachments/assets/22895bb6-513e-450e-b5b1-e49c237c4e9a)

![image](https://github.com/user-attachments/assets/87059c52-44f1-4873-9aba-50e128b1d520)

Pruebas falladas, vistas tanto desde Jenkins como desde Blue Ocean

![image](https://github.com/user-attachments/assets/956f8fb4-7ad8-4497-b4a6-da00e03436d4)

![image](https://github.com/user-attachments/assets/d2ddea06-8fcb-4141-b7b1-6f8a6a38a9ce)

Cambio a JaCoCo y a CheckStyle

![image](https://github.com/user-attachments/assets/dbc5e825-b3ca-4e05-a398-bdf165543726)

Resultado de los cambios, se genera como error aunque fue exitoso por los cambios a los thresholds de JaCoCo

### Git Actions

![image](https://github.com/user-attachments/assets/9414007e-d35e-4b36-b81c-b5ec1ebe6f19)


GitHub Actions con pruebas exitosas y fallidas

![image](https://github.com/user-attachments/assets/df75e9cd-26cf-4892-83e4-571235f218e3)
Fallos especificos de la integracion fallida

### AWS

![image](https://github.com/user-attachments/assets/eb7dca26-696a-47d0-b7be-b47755f5a616)

Manual Approval funcionando

![image](https://github.com/user-attachments/assets/9fd6554f-1b7f-486f-b6d0-f35dfa755f51)

Pipeline ejecutado exitosamente

![image](https://github.com/user-attachments/assets/c32af14d-d57c-4a2b-a326-20f9d4a52d63)

Reporte de pruebas de CodeBuild Reports

![image](https://github.com/user-attachments/assets/b438ec12-d821-4c8a-a924-172d9051e53b)

![image](https://github.com/user-attachments/assets/f75e9aec-357b-4514-9199-20c8c6fe5668)

![image](https://github.com/user-attachments/assets/6b454e56-c661-4775-ba44-f28f2fe471ea)

Imagenes de los vinculos "actuator"

![image](https://github.com/user-attachments/assets/a2f15d0a-0aa2-42ca-ab94-942ae581bdec)

Pruebas fallidas vistas desde CodeBuild Reports

![image](https://github.com/user-attachments/assets/11804a19-0fb2-494e-8a97-09d3c9c5188c)

![image](https://github.com/user-attachments/assets/6d03a898-418d-401b-bec9-1039e0ea8933)

Resultados despues de borrar "mvn test"

![image](https://github.com/user-attachments/assets/81ff419b-8e62-493f-a2ff-9fdd45a00811)

![image](https://github.com/user-attachments/assets/c6a03aa1-e4d0-457a-9760-2c9d4e0580be)

Lo encontrado en CloudWatch, principalmente metricas de todo lo que esta siendo usado en la cuenta
