# Api REST con SprinBoot
## Requisitos

Para poder ejecutar este proyecto, necesitarás tener instalado lo siguiente:

- Java Development Kit (JDK) 17
- Maven 3.3.0
- Spring Boot

Asegúrate de tener estas herramientas instaladas y configuradas correctamente antes de intentar ejecutar el proyecto.

## Docker
```bash
docker compose up -d --build
```
## Demostracion con Maker

```diff
http://localhost:8080/api/maker/findAll
```
![maker](img/findAll.png)

```diff
http://localhost:8080/api/maker/find/2
```
![maker](img/find-2.png)

```diff
http://localhost:8080/api/maker/save
```
![maker](img/save.png)
![maker](img/save-2.png)

```diff
http://localhost:8080/api/update/4
```
![maker](img/update.png)
![maker](img/update-2.png)

```diff
http://localhost:8080/api/Delete/4
```
![maker](img/delete.png)
![maker](img/delete-2.png)

## Demostracion con Product
```diff
http://localhost:8080/api/product/findAll
```
![maker](img/product.png)

```diff
http://localhost:8080/api/product/find/7
```
![maker](img/product-2.png)

```diff
http://localhost:8080/api/product/save
```
![maker](img/psave.png)
![maker](img/psave-2.png)

```diff
http://localhost:8080/api/product/update/10
```
![maker](img/pupdate.png)
![maker](img/pupdate-2.png)

```diff
http://localhost:8080/api/product/delete/10
```
![maker](img/pdelete.png)
![maker](img/pdelete-2.png)