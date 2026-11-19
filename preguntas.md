##1. ¿Qué diferencia hay entre preparar un archivo y confirmarlo?
-Preparar un archivo lo añade a un área temporal de revisión, mientras que confirmarlo guarda esos cambios de forma permanente en el historial.

##2. ¿Cuándo puedes usar Descartar cambios y qué riesgo tiene?
-Puedes usar "Descartar cambios" cuando hayas modificado un archivo en tu carpeta de trabajo y quieras devolverlo al estado exacto del último commit.

##3. ¿Qué pasa con tu trabajo cuando cambias de una rama a otra?
-Al cambiar de rama (git switch o git checkout), Git actualiza automáticamente los archivos de tu carpeta para que coincidan con el estado de la nueva rama.

##4. ¿Por qué no hubo conflicto al fusionar rama-a pero sí al fusionar rama-b?
-Los conflictos ocurren únicamente cuando dos ramas modifican las mismas líneas de un mismo archivo de forma diferente.

##5. ¿Para qué sirve crear una rama de experimento, aunque luego se borre?
-Una rama de experimento sirve como un entorno aislado y seguro para probar ideas arriesgadas sin romper el código principal que ya funciona.

##6. Si descubres hoy un error cometido hace cinco commits, ¿qué haces para arreglarlo?
-La forma más segura y recomendada es crear un nuevo commit que corrija el fallo o usar el comando git revert si quieres deshacer ese commit específico.