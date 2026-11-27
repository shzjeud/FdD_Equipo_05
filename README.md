# MINEGUARD · Equipo 05

<p align="center"><img src="Recursos/Imágenes/banner.png" alt="MINEGUARD" width="800"></p>

<p align="center"><strong>Sistema portátil de monitoreo ambiental para mejorar la seguridad en minería subterránea</strong></p>

<p align="center">
<img src="https://img.shields.io/badge/estado-en%20desarrollo-yellow" alt="Estado">
<img src="https://img.shields.io/badge/curso-Fundamentos%20de%20Dise%C3%B1o-blue" alt="Curso">
<img src="https://img.shields.io/badge/ODS-3%20%7C%208%20%7C%209-2ea44f" alt="ODS">
</p>

## Sobre el proyecto

**MINEGUARD** es un prototipo portátil para monitorear condiciones ambientales que pueden afectar la seguridad y la salud de los trabajadores en labores de minería subterránea. La propuesta busca entregar información local y comprensible sobre la calidad del aire, la presencia de gases y otras condiciones de riesgo.

El proyecto integra diseño electrónico, mecánico y de software, desde la investigación de la problemática y el estado de la tecnología hasta la definición de exigencias, el diseño conceptual y la documentación técnica.

> **Importante:** MINEGUARD es un prototipo académico. No reemplaza equipos certificados ni los procedimientos oficiales de seguridad minera. Antes de un uso real requiere calibración, validación en campo, pruebas de resistencia y revisión normativa.

## Problemática

La ventilación deficiente, la acumulación de gases y el material particulado pueden generar riesgos agudos y enfermedades ocupacionales en la minería subterránea. El informe técnico identifica la necesidad de contar con información ambiental oportuna en el punto de trabajo, especialmente donde los recursos de monitoreo son limitados.

La propuesta es una herramienta complementaria para visualizar y comunicar variables ambientales. Su uso, precio y canal de implementación deben validarse con pequeños mineros, responsables de seguridad y comités de vigilancia.

## Objetivos de Desarrollo Sostenible

### ODS 3 · Salud y bienestar

Contribuye a prevenir enfermedades y riesgos asociados a gases, contaminación del aire y condiciones ambientales peligrosas. **Meta 3.9:** reducir las enfermedades y muertes producidas por productos químicos peligrosos y la contaminación.

### ODS 8 · Trabajo decente y crecimiento económico

Promueve entornos laborales más seguros mediante información ambiental para prevenir riesgos ocupacionales. **Meta 8.8:** proteger los derechos laborales y promover ambientes de trabajo seguros.

### ODS 9 · Industria, innovación e infraestructura

Integra sensores, comunicación inalámbrica, procesamiento de datos y diseño mecánico para responder a una necesidad de seguridad industrial. **Meta 9.4:** modernizar la infraestructura con tecnologías eficientes y limpias.

## Arquitectura del prototipo

- Sensores MQ-4 y MQ-7 para detección de gases.
- Sensor DHT11 para temperatura y humedad.
- Sensor SW-420 para vibración.
- Arduino Nano como unidad de control.
- Pantalla LCD, LED y buzzer para alertas locales.
- XBee S2C para comunicación inalámbrica y SIM800C para comunicación celular.
- Alimentación con BMS, fusible y rieles independientes de 5 V.
- Carcasa diseñada en Onshape, con ingreso de aire, soportes internos y acceso a batería.

La autonomía estimada es de **4,1 a 6,8 horas**, por debajo de la meta de 8 horas. Esta es una mejora pendiente del prototipo.

## Metodología y resultados

1. Identificación y delimitación de la problemática.
2. Caracterización de usuarios, actores y necesidades.
3. Revisión de productos comerciales, patentes, artículos y tesis.
4. Lista de exigencias y estructura de funciones.
5. Generación y evaluación de conceptos con matrices morfológicas y de Pugh.
6. Desarrollo de los dominios electrónico, mecánico, energético, de control e interfaz.
7. Documentación del prototipo, planos, esquemas y recomendaciones de validación.

El concepto seleccionado obtuvo **2,70 sobre 4** en la matriz de Pugh. El diseño mecánico contempla una carcasa de aproximadamente **220 × 130 × 67 mm**.

## Estructura del repositorio

```text
.
├── Fundamentos de diseño/
│   ├── Entregables/
│   ├── Presentaciones de Proyecto/
│   └── Talleres/
├── Proyecto/
│   ├── Módulo Electrónico/
│   ├── Módulo Mecánico/
│   └── Módulo Software/
├── Recursos/
│   ├── Artículos científicos/
│   ├── Imágenes/
│   ├── Normas/
│   ├── Patentes/
│   ├── Productos comerciales/
│   └── Tesis de apoyo/
└── README.md
```

## Integrantes

| Integrante | Carrera |
|---|---|
| José Fernando Chávez Lozano | Ingeniería Informática |
| Richard Aaron Soriano Cordova | Ingeniería Informática |
| Amador Antonio Jara Castañeda | Ingeniería Industrial |
| José Gonzalo Saldaña Rodriguez | Ingeniería Industrial |
| Willian Chuyma Vargas | Ingeniería Industrial |

## Próximos pasos

- Calibrar MQ-4 y MQ-7 con gases de referencia.
- Implementar y documentar el firmware y sus pruebas.
- Mejorar la autonomía hasta alcanzar 8 horas.
- Completar el ruteo de la placa y verificar conexiones.
- Fabricar las piezas y validar ensamblaje y resistencia mecánica.
- Validar la propuesta con usuarios y revisar requisitos de certificación.

## Documentación

- [Informe técnico del proyecto](Fundamentos%20de%20dise%C3%B1o/Presentaciones%20de%20Proyecto/Informe%20t%C3%A9cnico%20del%20proyecto.md)
- [Entregables](Fundamentos%20de%20dise%C3%B1o/Entregables/)
- [Talleres](Fundamentos%20de%20dise%C3%B1o/Talleres/)
- [Proyecto](Proyecto/)
- [Recursos](Recursos/)

## Fuente

README actualizado a partir del [Informe técnico del proyecto](https://docs.google.com/document/d/1l9tRPn6Qk1oJSVGrcFGP6qKJbPwjnJntbNSGrZ6dly4/edit?usp=sharing).
