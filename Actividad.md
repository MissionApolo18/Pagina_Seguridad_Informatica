# Analisis de código

## Vulnerabilidades
- Archivo **.env** visible para todos en código, no es un archivo ejemplo
- Login / registo usuario:
    - Nombre de usuario: permite +10 dígitos indiscriminadamente entre letras y números
    - Contraseña:
        - No pide un mínimo o máximo de digitos, tampoco pide alguna combinación entre letras y digitos
        - No hay hash (cualquiera puede ver que se escribió en front)
- Login / registro admin: 
    - Mismos problemas que usuario
- Conexión a la bdd directo en el código y visible para todos

## Mejoras
- Documentación (Archivo readme sólo con información no tan útil), no hay cómo instalarlo ni como usarlo
- Hash en el login y registro
- Que no abra una nueva página cada que se inicia o cierra sesión
- Archivo *.env*



## Funcionalidad 
- Si registra nuevos usuarios y administradores
- Si reconoce a los nuevos usuarios creados