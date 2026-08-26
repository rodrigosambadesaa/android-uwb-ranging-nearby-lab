# Enunciado didáctico reconstruido — UWB Ranging / Nearby

Laboratorio Android orientado a practicar **Ultra-Wideband (UWB)** con AndroidX Core UWB.

La aplicación debe:

1. comprobar si el dispositivo soporta y tiene disponible UWB;
2. solicitar el permiso `UWB_RANGING` cuando corresponda;
3. crear un `UwbManager` únicamente en hardware compatible;
4. obtener un ámbito de sesión de ranging;
5. construir los `RangingParameters` necesarios;
6. suscribirse a los eventos de distancia/posición producidos por la sesión;
7. informar de forma clara cuando el dispositivo no soporta la tecnología o no dispone de los datos necesarios para establecer una sesión real.

La dirección del peer incluida en la demo es sintética. Para obtener ranging real se necesitan dos dispositivos UWB compatibles y un intercambio fuera de banda de los datos reales de sesión/canal.

No existe una base de datos asociada.
