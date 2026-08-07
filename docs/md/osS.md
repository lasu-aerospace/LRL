Solaris es una arquitectura de acceso orbital basada en un sistema de lanzamiento asistido sin propelente en la fase inicial, seguido por una etapa química encargada de llevar la carga a una trayectoria suborbital e insertarla en órbita.

El principio se mantiene: complejidad mínima en fases críticas, pero ahora con una condición adicional —la energía inicial no proviene de combustión a bordo.

# Fase de lanzamiento (Δv = 0 a bordo)

La primera etapa es un sistema externo de aceleración.

Puede adoptar varias formas realistas:

- Rampa electromagnética (tipo railgun / mass driver)
- Sistema de lanzamiento asistido por cable (tipo skyhook parcial o catapulta)
- Plataforma de aceleración horizontal con transición a vertical

El vehículo no genera empuje propio. Toda la energía cinética inicial proviene del sistema terrestre.

Esto implica tres consecuencias directas:

- El “Δv = 0” es correcto desde el punto de vista del vehículo, pero no del sistema.
- El cuello de botella pasa a ser estructural y aerodinámico, no propulsivo.
- Las cargas útiles y la segunda etapa deben tolerar aceleraciones elevadas.

Resultado de esta fase:
El sistema entrega velocidad inicial y altitud parcial, típicamente en régimen subsónico o supersónico bajo, dependiendo de la tecnología empleada.

## Segunda etapa química

Aquí está el cambio crítico:
La segunda etapa deja de ser “de inserción” y pasa a ser la única etapa propulsiva real del vehículo.

Funciones:
- Completar ascenso atmosférico
- Llevar la carga a trayectoria suborbital
- Realizar inserción orbital en apogeo

### Configuración:

- UDMH / NTO
- Pressure-fed
- Encendido múltiple o prolongado (idealmente)
- Control vectorial + RCS

### Implicación técnica:

El Δv requerido ahora depende de cuánto aporte el sistema de lanzamiento, esta etapa podría necesitar del orden de 4–7 km/s de Δv efectivo.

## Perfil de misión ajustado
aceleración externa (sin propelente a bordo)
separación del sistema de lanzamiento
encendido de la etapa química
ascenso y trayectoria suborbital
apagado cerca del apogeo (o coast phase)
corrección de actitud
reencendido y circularización

# Infraestructura orbital

El sistema no termina en la inserción. Se apoya en una red de comunicaciones y seguimiento que permite control continuo, sincronización de maniobras y soporte a operaciones posteriores. Esto convierte el lanzamiento en un sistema operativo, no en un evento aislado.

# Subsistemas de integración (post-inserción)

## Velas solares (propulsión pasiva)
Se usan para correcciones orbitales de bajo empuje, transferencias lentas y extensión de misión. No intervienen en el acceso a órbita. Operan donde su bajo thrust-to-mass ratio es aceptable.

## Navegación astronómica (ANST)
Sistema autónomo basado en sensores estelares (star trackers) y, si se requiere, referencia solar/lunar. Permite determinación de actitud y navegación sin dependencia continua de GNSS o estaciones terrestres.
Ventaja clave: robustez en espacio profundo y redundancia frente a pérdida de enlace.
Función: soporte a control de actitud, validación de órbita y sincronización de maniobras en misiones de larga duración.

## Propulsión iónica (eléctrica)
Sistema de alto Isp (≈1500–4000 s) para maniobras de bajo empuje y larga duración.
Uso: elevación de órbita, transferencias interorbitales y ajustes finos con consumo mínimo de propelente.
Requisito: fuente de potencia eléctrica estable (paneles solares o reactor).

## Propulsión nuclear (térmica o eléctrica)
Escala el sistema más allá de LEO.

Nuclear térmica (NTR): alto empuje relativo y Isp superior al químico para transferencias rápidas.
Nuclear eléctrica (NEP): muy alto Isp con bajo empuje, ideal para cargas sostenidas y misiones profundas.
Rol: habilitar misiones interplanetarias sin rediseñar la arquitectura base.

Estos subsistemas no interfieren con el lanzamiento. Se integran después de la inserción, manteniendo desacopladas las fases de alto riesgo.

## Ensamblaje orbital

Permite acoplar módulos, expandir estructuras y configurar vehículos mayores en órbita. Reduce restricciones de masa/volumen del lanzador y habilita crecimiento progresivo del sistema.
