# Pruebas de API REST — Swagger Petstore v2

Repositorio con la evidencia, colección y variables de entorno correspondientes a las pruebas funcionales y de validación de contrato realizadas en **Postman** sobre los módulos `user` de la API Swagger Petstore.

## Contenido del repositorio
* **`Informe_Pruebas_Petstore.docx`** *(o `.pdf`)*: Documentación técnica con los endpoints evaluados, descripción de cada caso de prueba y capturas de ejecución.
* **`Coleccion_Petstore2.postman_collection.json`**: Colección exportada con las peticiones (`POST`, `GET`, `PUT`, `DELETE` y caso de error `400`) y sus respectivos scripts en *After response* (`pm.test` y `pm.environment.set`).
* **`Entorno_Petstore.postman_environment.json`**: Variables de entorno utilizadas durante la ejecución (`base_url`, `id_usuario`, `nombre_usuario`, `correo_usuario`).

## Instrucciones de ejecución en Postman
1. Abrir Postman y hacer clic en **Import** .
2. Arrastrar o seleccionar ambos archivos `.json` (`collection` y `environment`).
3. En la esquina superior derecha de Postman, seleccionar el entorno importado en el desplegable de *Environments*.
4. Ejecutar las peticiones de la carpeta `actividad` en orden secuencial (`POST` → `GET` → `PUT` → `DELETE`) y verificar los resultados en la pestaña **Test Results**.
