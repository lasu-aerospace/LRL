# Proyecto Open Skies: SUNBURST

Este informe presenta una propuesta técnica para el desarrollo de un sistema de velas solares modulares acoplables, orientado a la exploración interplanetaria y a la expansión progresiva de la infraestructura orbital. El concepto se basa en la acumulación de cargas pequeñas lanzadas a órbita, que se ensamblan de forma incremental para constituir velas solares de gran escala, potencialmente de orden kilométrico.
El sistema combina métodos de lanzamiento de alta eficiencia energética con propulsión pasiva continua, permitiendo alcanzar trayectorias hiperbólicas sostenidas y velocidades elevadas sin recurrir a grandes cantidades de propelente químico. El enfoque prioriza la escalabilidad, la reutilización de infraestructura y la reducción del coste energético por kilogramo colocado en órbita.

## Marco conecptual

[![model](https://img.shields.io/badge/ipynb-model-red)](https://colab.research.google.com/drive/1z2EWUpaRVfWeS2A-auSQY0NR4HsEb4ra?usp=sharing)

El proyecto Open Skies: SUNBURST se apoya en la interacción coordinada de tres conceptos fundamentales:

1. Lanzamiento por Centrifugación Acumulada (LCA): método de aceleración mecánica progresiva que permite transferir energía cinética a un carguero sin un consumo significativo de combustible.
2. Constelación Geoestacionaria Triple (CGT): red de satélites de retransmisión diseñada para garantizar la comunicación continua entre las centrifugadoras orbitales y el Control de Misión, así como la sincronización entre los propios sistemas de lanzamiento.
<img src="../docs/GSO_relay.png" alt="" width="100%">

3. Velas solares modulares: superficies reflectantes acoplables, reconfigurables e inclinables, optimizadas para aprovechar la presión de radiación solar como fuente de empuje continuo a largo plazo.
<img src="../docs/image2.png" alt="" width="100%">

La integración de estos tres elementos constituye una arquitectura de transporte espacial orientada a maximizar la eficiencia energética y la capacidad de expansión progresiva del sistema.

## Objetivos del proyecto
- Desarrollar una infraestructura de lanzamiento orbital con consumo mínimo de propelente.
- Validar la viabilidad del LCA como método de transferencia energética entre plataformas orbitales.
- Implementar velas solares modulares capaces de escalar en superficie y rendimiento.
- Reducir el coste marginal por kilogramo colocado en trayectorias interplanetarias.
- Establecer una base tecnológica para misiones de exploración de largo plazo.

## Descripción del sistema

### 1. Catapulta Alpha (plataforma terrestre)
Construir la primera centrifugadora, también conocida como "Catapulta Alpha" en Uruguay.
Catacterísticas principales:
- Sistema eléctrico de alta potencia destinado a alcanzar elevadas velocidades angulares.
- Plataforma de prueba para caracterizar tiempos de aceleración y límites estructurales.
- Capacidad de alojar un carguero reutilizable para ensayos dinámicos.
La Catapulta Alpha funcionará como banco de pruebas y como elemento inicial de transferencia energética hacia el sistema orbital.

### 2. Catapulta Beta (plataforma orbital)
Una centrifugadora idéntica a la Alpha, denominada Catapulta Beta, será lanzada a órbita terrestre baja.
Parámetros iniciales:
- Altura orbital aproximada: 150 km.
- Configuración plegada durante el lanzamiento.
- Despliegue y activación una vez en órbita.
Consideraciones técnicas:
- La rotación de la Beta introducirá perturbaciones orbitales significativas.
- Se integrará un Sistema de Control de Reacción (RCS) destinado exclusivamente a la corrección y estabilización orbital.
- El sistema RCS operará dentro de límites estrictos de empuje, priorizando la eficiencia.
La plataforma contará con un sistema de captura del carguero basado en acoplamiento controlado, asistido por mecanismos electromagnéticos y correcciones de actitud, con el objetivo de preservar el centro de masa del conjunto.

### 3. Ajuste orbital y estabilización
Una vez desplegada la Catapulta Beta, se prevé un lanzamiento adicional destinado a elevarla a una órbita más estable. Esta maniobra se realizará tras la validación inicial de los parámetros de rotación y control.

### 4. Ensayos con carguero vacío

El carguero, inicialmente sin carga útil, será posicionado en la Catapulta Alpha.

Objetivos del ensayo:

- Determinar el tiempo necesario para acumular una velocidad de transferencia objetivo.

- Evaluar pérdidas energéticas y estabilidad dinámica.

- Validar modelos teóricos de acumulación de energía cinética.

### 5. Transferencia Alpha–Beta

Se coordinará una ventana de lanzamiento precisa entre ambas catapultas.

El carguero contará con:

- Superficies aerodinámicas pasivas para estabilización inicial.

- Un tanque reducido de monopropelente destinado únicamente a correcciones de trayectoria.

El monopropelente remanente será transferido a la Catapulta Beta. El tanque vacío será desacoplado y enviado a reentrada controlada para su recuperación mediante rejillas aerodinámicas y paracaídas.

### 6. Prueba lunar

La Catapulta Beta iniciará su rotación para lanzar el carguero en una trayectoria de transferencia lunar.

Objetivo:

- Validar un sobrevuelo lunar como demostración de capacidad interplanetaria inicial.

Tras el sobrevuelo, el carguero será dejado en trayectoria libre, previendo un impacto lunar o una órbita de escape según los parámetros finales.

### 7. Escalado del sistema

Se lanzarán misiones adicionales destinadas a:

- Elevar progresivamente la órbita de la Catapulta Beta.

- Investigar tecnologías que permitan aumentar la velocidad angular máxima de la Catapulta Alpha.

En caso de limitaciones estructurales o energéticas, se integrará una vela solar inicial al carguero para complementar la energía aportada por la centrifugación.

### Velas solares modulares

Todas las cargas futuras incorporarán sistemas de velas solares:

- Acoplables y desacoplables.

- Reconfigurables en geometría y orientación.

- Optimizadas para maximizar el empuje fotónico según la distancia al Sol y la masa total del conjunto.

Este enfoque permitirá alcanzar mayores distancias con cargas más pesadas, manteniendo un consumo energético mínimo tras la fase inicial de lanzamiento.

Open Skies: SUNBURST propone una infraestructura de transporte orbital y propulsión pasiva basada en principios físicos conservadores, orientada a la eficiencia energética, la reutilización y la escalabilidad. El sistema no persigue soluciones de corto plazo, sino la construcción progresiva de una plataforma tecnológica capaz de sostener misiones interplanetarias de largo alcance con un coste marginal decreciente.

El proyecto sienta las bases para una nueva forma de concebir el acceso al espacio y la exploración más allá de la órbita terrestre.