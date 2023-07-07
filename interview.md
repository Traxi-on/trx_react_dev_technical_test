## Code Challenge

Resumen: Realizar una applicación que permita leer códigos QR desde la cámara del dispositivo extraer la data y enviarlo a un servicio.

### Requerimientos

- Pantalla para visualizar la cámara lectora 
- Extraer la información de los QR de muestra y mostrarlo en alguna parte de la pantalla
- Enviar la data extraída del QR por medio de un POST hacía: `https://jsonplaceholder.typicode.com/posts`
- Mostrar en alguna parte de la pantalla la respuesta de la solicitud POST (Success/Failure)

#### Servicio

```
POST: https://jsonplaceholder.typicode.com/posts
BODY: {
  title: "string - Extracted from QR value"
}
```

#### QR pruebas

![QR1](https://user-images.githubusercontent.com/16879799/249898195-cdb4a306-7344-4ac6-8234-271b51a23472.jpg)
![QR2](https://user-images.githubusercontent.com/16879799/249898231-a69941f8-48f2-4465-91e9-c6b95d656e8a.jpg)



### ¿Qué se puede utilizar?

- Cualquier cliente HTTP
- Cualquier librería necesaria.


### Entregables

- Apk o ipa de la aplicación
- URL del respositorio de GitHub público

### Extras - Opcionales
- Git flow
- Clean code
- Hooks
- Testing
- TDD