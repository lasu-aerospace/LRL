# Proyecto Open Skies: SUNBURST

## Introduccion

Open Skies: SUNBURST es una propuesta tecnica para el desarrollo de una arquitectura de acceso orbital basada en un sistema de lanzamiento quimico de dos etapas, optimizado para insercion eficiente en orbita terrestre baja.

El sistema esta disenado bajo un principio central:

La complejidad debe concentrarse en fases controlables y bien caracterizadas del vuelo, evitando arquitecturas mecanicas de alta incertidumbre.

Dentro de este marco, se incorporan sistemas auxiliares de propulsion pasiva (velas solares) como herramientas de optimizacion orbital de largo plazo, no como mecanismo primario de acceso al espacio.

---

## Marco conceptual

SUNBURST se basa en tres componentes funcionales:

### 1. Lanzamiento quimico de dos etapas

Sistema principal de acceso a orbita:

- Primera etapa: proporciona el delta-v inicial y coloca la carga en una trayectoria suborbital balistica.
- Segunda etapa hipergolica: realiza la insercion orbital mediante encendido cercano al apogeo.

Este esquema prioriza:
- eficiencia energetica en insercion orbital
- reduccion de complejidad estructural
- alta confiabilidad operativa

---

### 2. Control orbital y comunicaciones

Infraestructura de soporte basada en una red de satelites de retransmision, encargada de:

- comunicacion continua con cargas en vuelo
- sincronizacion de operaciones orbitales
- soporte a maniobras de insercion y seguimiento

---

### 3. Propulsion pasiva auxiliar (velas solares)

Las velas solares se integran como un sistema secundario de optimizacion orbital, no como mecanismo de lanzamiento.

Funciones:
- correccion orbital de bajo consumo energetico
- transferencias lentas interorbitales
- extension de misiones de larga duracion

---

## Objetivos del proyecto

- Desarrollar un sistema de acceso orbital quimico viable y escalable
- Optimizar la insercion orbital mediante perfiles de apogeo
- Reducir la complejidad estructural respecto a sistemas no convencionales previos
- Implementar sistemas auxiliares de propulsion pasiva para optimizacion orbital
- Establecer una base tecnologica para misiones interplanetarias progresivas

---

## Arquitectura del sistema

### 1. Primera etapa

Responsable de:

- superar la atmosfera terrestre
- proporcionar el impulso inicial del sistema
- colocar la carga en una trayectoria suborbital controlada

Caracteristicas:
- diseno convencional de alta eficiencia
- enfoque en fiabilidad estructural
- posible uso de lanzadores existentes

---

### 2. Cofia aerodinamica

Estructura de proteccion que encapsula:

- segunda etapa
- sistemas de control
- sistemas auxiliares desplegables

Funciones:
- reduccion de carga aerodinamica
- proteccion termica y estructural
- separacion en baja presion atmosferica

---

### 3. Segunda etapa hipergolica

Elemento central del sistema de insercion orbital.

Caracteristicas:
- propelentes: UDMH / NTO
- sistema: alimentacion por presion (pressure-fed)
- empuje: ~15 kN
- impulso especifico: ~300 s
- tiempo de combustion: ~90 s

Ventajas:
- alta confiabilidad
- ignicion automatica
- baja complejidad mecanica

Funcion:
Completar la transicion de trayectoria suborbital a orbita estable mediante encendido cercano al apogeo.

---

### 4. Perfil de mision

Secuencia nominal:

1. lanzamiento mediante primera etapa
2. trayectoria suborbital ascendente
3. aproximacion al apogeo
4. separacion de cofia
5. estabilizacion de actitud
6. encendido de segunda etapa
7. insercion en orbita terrestre

---

### 5. Sistema de control

Incluye:

- control de actitud previo al encendido
- sistema RCS para correcciones finas
- control vectorial del empuje

Objetivos:
- alineacion precisa del vector de empuje
- minimizacion de perdidas de delta-v
- estabilidad durante insercion orbital

---

### 6. Velas solares (subsistema auxiliar)

Caracteristicas:
- desplegables en orbita
- modulares
- reconfigurables

Funciones:
- correcciones orbitales
- transferencias de baja energia
- extension de misiones

Rol:
Sistema de optimizacion orbital posterior a la insercion.

---

### 7. Ensamblaje orbital

Permite:

- acoplamiento de modulos en orbita
- expansion progresiva de estructuras
- construccion de sistemas de gran escala

---

## Filosofia de diseno

SUNBURST adopta:

- sistemas probados en fases criticas
- reduccion de complejidad mecanica
- modularidad estructural
- separacion entre lanzamiento y optimizacion orbital

La innovacion se centra en la arquitectura, no en la complejidad mecanica.

---

## Conclusiones

SUNBURST define una arquitectura de acceso orbital basada en propulsion quimica optimizada y sistemas auxiliares de asistencia orbital.

El sistema es:
- coherente
- escalable
- tecnicamente viable

Una plataforma evolutiva para exploracion espacial progresiva.