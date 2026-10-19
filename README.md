# Proyecto Django — Oliver Daniel Domínguez Padilla

## Demo en vivo (producción)
https://u3s6-dominguez-padilla-oliver-daniel.onrender.com/

## Semana 6 — Autenticación, sesiones y seguridad
Registro/login/logout propios; cada usuario ve y edita solo
sus propios servicios (probado con usuario_a y usuario_b).

## Prueba de aislamiento
Registré dos cuentas en producción (usuario_a y usuario_b) y creé 2 servicios con cada una.
El listado de usuario_b mostró solo sus servicios. Al abrir a mano
/servicios/<id>/editar/ y /servicios/<id>/eliminar/ con el id de un servicio de usuario_a,
la respuesta fue 404 en ambos casos.