# Sistema-de-reserva
## Diagrama de Caso de uso
### Errores
- La relaciones, no se puede identificar si son include o extend
- Los Actores apiReserva Externa y Sistema de notificaciones no califican como un actor ya que no son usuarios del sistema, mas bien son parte de el
- El titulo del sistema debe estar fuera del rectángulo que lo identifica
- El usuario no deveria poder eliminar el historial de reservas, no es una buena practica para el sistema
### Correccion
![image](https://github.com/user-attachments/assets/b07b954a-276a-46dd-b137-f79b3b2c2224)


## Diagrama de Clases
### Errores
- No se esta ocupando ningún patrón de diseño en el diagrama de clases, se podría usar el patrón adapter para el sistema de notificaciones por ejemplo
- La clases no están relacionadas correctamente por ejemplo, La clase usuario tiene que usar sistema de reservar para interactuar con la sala
- El administrador no deveria interactuar con el usuario, mas bion con el sistema de reserva
### Correccion
![image](https://github.com/user-attachments/assets/d084f12d-766f-49d6-a20d-4a8de72865de)


## Diagrama de Implementación
### Errores
- El nodo donde esta el administrador no esta definido ni se menciona
- El gestor de notificaciones al aplicar el patron bridge es suficiente, no nesesita conectar con otro nodo
- La disponibilidad de salas tiene que ser controlada por el administrador, no por una apa, esto complemente el primer error
### Correccion
![image](https://github.com/user-attachments/assets/a46df9ef-d9c8-4056-8f7e-5a107e6964f7)

