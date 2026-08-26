\# Reflexión sobre Git y GitHub



\### Pregunta 1: Importancia de git status

Ejecutar git status ANTES de git add evita incluir accidentalmente archivos no deseados o temporales. Ejecutarlo DESPUÉS permite validar exactamente qué cambios ingresaron al área de preparación (staging) antes de confirmar el commit.



\### Pregunta 2: Orden de pull y push

Intentar un git push sin haber hecho git pull cuando el remoto fue actualizado provoca un error non-fast-forward. Para solucionarlo, se ejecuta git pull para integrar las novedades del remoto, se resuelven los conflictos en caso de haberlos, y posteriormente se realiza el git push.



\### Pregunta 3: Autoevaluación

Lo más desafiante fue resolver el conflicto de credenciales de usuario y comprender el flujo entre el equipo local y el servidor remoto. El comando que más utilizaré a diario es git status para mantener el control sobre el estado del proyecto.

