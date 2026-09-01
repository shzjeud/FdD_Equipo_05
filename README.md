# Equipo 05 - Fundamentos de Diseño
### Carrera de Ingeniería Informática / Industrial  
**Universidad Peruana Cayetano Heredia**

---

## 🌍 Descripción del Equipo 
Somos el **Equipo 05** del curso **Fundamentos de Diseño 2026-2**, conformado por estudiantes de la carrera de Ingeniería Informática e Ingeniería Industrial.  
Nuestro objetivo es aplicar la metodología de diseño para analizar problemáticas actuales y plantear, posteriormente, soluciones innovadoras que contribuyan al bienestar social, la seguridad, la sostenibilidad y el desarrollo tecnológico.  

Hemos decidido enfocar nuestro trabajo en cuatro **Objetivos de Desarrollo Sostenible (ODS)** que consideramos estrechamente conectados entre sí: la salud y seguridad de las personas están relacionadas con las condiciones laborales, la infraestructura y la tecnología disponibles, aspectos que también pueden verse afectados por los factores ambientales y la crisis climática.

### 🏥 ODS 3: Salud y Bienestar - ODS PRINCIPAL
Buscamos aportar a la mejora de la salud y el bienestar de las personas. Nos interesan especialmente los aspectos relacionados con la prevención de riesgos y la protección de la salud, especialmente en contextos donde existen condiciones de trabajo de mayor riesgo.

**Meta 3.9:** Reducir sustancialmente el número de muertes y enfermedades producidas por productos químicos peligrosos y por la contaminación del aire, el agua y el suelo.

![imagealt](https://github.com/shzjeud/FdD_Equipo_05/blob/de07b7e19ca35142dcb288dbffc9019dedbeffaa/Recursos/Im%C3%A1genes/ODS3.png)

### 💼 ODS 8: Trabajo Decente y Crecimiento Económico
Buscamos contribuir a la promoción de condiciones laborales seguras y adecuadas para los trabajadores. Consideramos especialmente importante la prevención de riesgos y la protección de la seguridad y salud de las personas en actividades laborales de alto riesgo.

**Meta 8.8:** Proteger los derechos laborales y promover entornos de trabajo seguros y protegidos para todos los trabajadores.

![image alt](https://github.com/shzjeud/FdD_Equipo_05/blob/5aac54a223f357881af25cd516a804c3455e33b8/Recursos/Im%C3%A1genes/ods_8_480x219.jpg)

### 🏭 ODS 9: Industria, Innovación e Infraestructura
Como estudiantes de ingeniería, este objetivo es el eje de nuestra formación. Nos interesa analizar cómo la infraestructura y los procesos industriales pueden influir en la seguridad, eficiencia y sostenibilidad de las actividades productivas, especialmente en contextos donde existen condiciones de trabajo de mayor riesgo.

**Meta 9.4:** Modernizar la infraestructura y reconvertir las industrias para que sean sostenibles, utilizando los recursos con mayor eficiencia y promoviendo tecnologías y procesos más limpios.

![image alt](https://github.com/shzjeud/FdD_Equipo_05/blob/273c053b20773f26b74f3c701b3ca76277854212/Recursos/Im%C3%A1genes/sdg_9_480x219.jpg)

### 🌱 ODS 13: Acción por el Clima
Nos interesa analizar cómo los factores ambientales y los riesgos relacionados con el clima pueden afectar a las actividades productivas y a las comunidades, especialmente aquellas que presentan una mayor vulnerabilidad.

**Meta 13.1:** Fortalecer la resiliencia y la capacidad de adaptación a los riesgos relacionados con el clima y los desastres naturales.

![image alt](https://github.com/shzjeud/FdD_Equipo_05/blob/317b4c5c54d70a2dd73ef13b7b7ca652cf475707/Recursos/Im%C3%A1genes/ODS13-480x219.jpg)

### ⚠️ Nuestra problemática a abordar

Nuestro equipo abordará la seguridad y salud ocupacional de los trabajadores en actividades de minería subterránea en el Perú, delimitando nuestra problemática a la exposición a condiciones ambientales potencialmente peligrosas en el interior de las labores mineras, particularmente aquellas relacionadas con la calidad del aire, la presencia de gases y material particulado.

La relevancia de esta problemática se evidencia en las estadísticas de enfermedades ocupacionales del sector minero peruano. Durante el periodo 2011-2020 se registraron 37 899 casos de enfermedades ocupacionales, de los cuales 35 891 (90,74 %) correspondieron a hipoacusia y 1 875 (4,94 %) a neumoconiosis. Asimismo, los agentes físicos representaron 38 181 casos (95,09 %) y los agentes químicos 1 954 casos (4,87 %) (Aquino-Canchari et al., 2022).

La problemática también comprende riesgos agudos asociados a la atmósfera de las labores subterráneas. El Reglamento de Seguridad y Salud Ocupacional en Minería establece medidas específicas para las labores donde existe liberación de gases, incluyendo la ventilación forzada para mantener sus concentraciones por debajo de los límites de exposición ocupacional. Asimismo, contempla medidas de protección frente al monóxido de carbono en determinadas operaciones subterráneas (Ministerio de Energía y Minas [MINEM], 2026).

Esta situación continúa siendo relevante desde el punto de vista de la seguridad minera. En la mediana y gran minería, Osinergmin reportó que hasta junio de 2026 se habían registrado 13 accidentes mortales con 15 víctimas mortales, aunque el índice de accidentabilidad mantiene una tendencia a la baja (Osinergmin, 2026).

Por ello, nos enfocaremos en comprender cómo las condiciones ambientales presentes en las labores de minería subterránea pueden afectar la seguridad, salud y bienestar de los trabajadores, considerando particularmente la calidad del aire, la exposición a gases y material particulado, así como las condiciones de ventilación. En esta etapa no planteamos una solución específica, sino que buscamos caracterizar y comprender la problemática que abordaremos durante el curso.

  ![image alt](https://github.com/shzjeud/FdD_Equipo_05/blob/055571affc67ab7f94f40f03502cb7202018bbff/Recursos/Im%C3%A1genes/R.jpg) 
  
# Estado de la tecnología / Antecedentes

---

## 📚 TESIS

### Tesis — Asencio Puma (2026)

• **Introducción:** La investigación aborda los riesgos asociados a la **acumulación de gases y la deficiente calidad del aire** en minería subterránea, proponiendo un sistema de monitoreo ambiental mediante sensores inteligentes de **O₂ y CO** para mejorar la seguridad de los trabajadores.

• **Metodología:** Se realizó un estudio **cuantitativo y cuasiexperimental** en una operación de pequeña minería subterránea en Trujillo. Primero se estableció una línea base mediante mediciones manuales durante tres meses en la bocamina, galería inicial y frente de avance. Posteriormente, se implementaron sensores fijos de O₂ y CO conectados mediante **LoRaWAN**, con registros automáticos cada cinco minutos y generación de alertas.

• **Resultados:** Durante el monitoreo inicial, el **22 % de las mediciones de O₂** se encontró por debajo del límite de 19,5 %, mientras que el **18 % de los registros de CO** superó las 25 ppm. Después de implementar el sistema, se obtuvo monitoreo continuo y alertas automáticas, registrándose reducciones de **62 % a 72 % en las alarmas de O₂** y de **60 % a 66 % en las de CO**.

• **Conclusión:** El sistema demostró ser **técnicamente viable y económicamente accesible** para la pequeña minería, permitiendo reemplazar el monitoreo manual y ocasional por un sistema continuo de detección y alerta. Este antecedente permite identificar una solución que integra **detección de gases y material particulado, monitoreo remoto y generación de alertas**, evidenciando las tecnologías empleadas para la supervisión de condiciones ambientales en minería subterránea.

---

## 📄 ARTÍCULOS ACADÉMICOS

---

## 📜 PATENTES

### CN220667645U — Dispositivo electrónico de monitorización de seguridad en minas subterráneas

La patente propone un dispositivo para el **monitoreo de seguridad en minas subterráneas de carbón**, integrando sensores de **metano, monóxido de carbono, polvo y humo** para supervisar continuamente la calidad del aire. El sistema incorpora además ventiladores, una cámara de monitoreo, comunicación inalámbrica y una alarma sonora, permitiendo transmitir los datos a un terminal externo y generar alertas ante condiciones peligrosas. De esta manera, presenta una solución tecnológica basada en la **detección de contaminantes, monitoreo remoto y generación de alertas** frente a riesgos ambientales en labores subterráneas. Este antecedente permite identificar tecnologías y métodos de detección y alerta ya desarrollados que serán considerados posteriormente al establecer las exigencias de nuestra propuesta **(Wang et al., 2024)**.

---

## 🛒 PRODUCTOS COMERCIALES

---

## 🎥 PROYECTOS Y PROTOTIPOS

---

## 🔎 OBJETIVO DE LA REVISIÓN

La revisión de **tesis, patentes, productos comerciales y proyectos existentes** permitirá conocer las tecnologías disponibles, identificar soluciones ya desarrolladas y reconocer posibles **limitaciones y oportunidades de mejora** que serán consideradas en las siguientes etapas del diseño.

---

## 📸 Fotografía del Equipo  
<p align="center">
<img width="1408" height="768" alt="imagen_alumnos_IA" src="./Recursos/Imágenes/equipo.png">
  <em>Figura 1. Fotografía del equipo 05</em>
</p>

---

## 👥 Integrantes del Equipo  

| Foto | Nombre | Rol | Intereses | Correo institucional |
|------|--------|-----|-----------|----------------------|
| <img src="/Recursos/Imágenes/Soriano.png" width="90"/> | Richard Aaron Soriano Cordova | Líder del equipo | Innovación social, sostenibilidad | richard.soriano@upch.pe |
| <img src="/Recursos/Imágenes/Gonzalo.png" width="90"/> | Jose Gonzalo Saldaña Rodriguez | Responsable de investigación | Gestión ambiental, desarrollo comunitario | jose.saldana.r@upch.pe |
| <img src="/Recursos/Imágenes/Chuyma.jpeg" width="90"/> | Willian Chuyma Vargas | Diseñador/a | Diseño de prototipos, creatividad aplicada | willian.chuyma@upch.pe |
| <img src="/Recursos/Imágenes/Jara.jpeg" width="90"/> | Amador Antonio Jara Castañeda | Encargado/a de documentación | Comunicación científica, redacción técnica | amador.jara@upch.pe |
| <img src="/Recursos/Imágenes/Chávez Lozano José Fernando.jpeg" width="90"/> | Jose Fernando Chavez Lozano | Programador/a - Modelador/a | Programación, análisis de datos, simulación | jose.chavez.l@upch.pe | 

---

## 📌 Resumen Final   
Este README presenta quiénes somos, qué nos motiva y los ODS en los que queremos enfocar nuestro trabajo durante el curso. Para nosotros, la **Salud y bienestar (ODS 3)**, el **Trabajo Decente y Crecimiento Económico (ODS 8)**, la **Industria, innovación e infraestructura (ODS 9)** y la **Acción por el clima (ODS 13)** están estrechamente relacionados. Consideramos que, desde la ingeniería, podemos analizar problemáticas reales y, posteriormente, plantear soluciones que mejoren la calidad de vida de las personas y, al mismo tiempo, contribuyan al cuidado y sostenibilidad de nuestro entorno.

### 📚 Referencias bibliográficas

Aquino-Canchari, C. R., Huamán-Castillón, K. M., & Jiménez-Mozo, F. (2022). Enfermedades ocupacionales en minería en el Perú, 2011-2020. Revista de la Asociación Española de Especialistas en Medicina del Trabajo, 31(3), 275–282. https://scielo.isciii.es/scielo.php?script=sci_arttext&pid=S3020-11602022000300004

Asencio Puma, F. (2026). Implementación de un sistema de monitoreo ambiental con sensores inteligentes para mejorar la seguridad en pequeña minería subterránea, Trujillo 2024 [Tesis de licenciatura, Universidad Católica de Santa María]. Repositorio Institucional de la Universidad Católica de Santa María. https://hdl.handle.net/20.500.12920/16760

Ministerio de Energía y Minas. (2026). Reglamento de Seguridad y Salud Ocupacional en Minería (Ed. 2026). Gobierno del Perú. https://www.gob.pe/institucion/minem/informes-publicaciones/5631689-reglamento-de-seguridad-y-salud-ocupacional-en-mineria-ed-2026

Organismo Supervisor de la Inversión en Energía y Minería. (2026). Boletín estadístico de accidentes mortales en la mediana y gran minería. https://rendiciondecuentas.osinergmin.gob.pe/mineria-boletin-accidentes-mortales

Pacto Mundial de Naciones Unidas. (s. f.). ODS: Objetivos de Desarrollo Sostenible. https://www.pactomundial.org/que-puedes-hacer-tu/ods/

Wang, Z., Yang, L., & Yu, T. (2024). Underground coal mine safety electronic monitoring device (Patent No. CN220667645U). China National Intellectual Property Administration. https://patents.google.com/patent/CN220667645U/en

