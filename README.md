# ML para predecir las posibilidades de sufrir una enfermedad cardiaca

## Introducción 📋

**Problema:**
La principal causa de muerte en los países desarrollados se deben a enfermedades cardiovasculares. Las cardiopatías son desde hace 20 años la causa principal de mortalidad en todo el mundo, si bien ahora provocan más muertes que nunca. El pronóstico temprano de las enfermedades cardiovasculares puede ayudar en la toma de decisiones sobre cambios en el estilo de vida en pacientes de alto riesgo y/o a reducir las complicaciones de la enfermedad. Esta investigación tiene como hipótesis inicial la intención de identificar los factores de riesgo más relevantes de la enfermedad cardíaca.

**Fuente:**
El conjunto de datos ha sido recogido por la organización Framingham Heart Study y está disponible públicamente en el sitio web: https://www.framinghamheartstudy.org/ y en https://ocw.mit.edu/courses/15-071-the-analytics-edge-spring-2017/resources/framingham/. Estos datos provienen de un estudio cardiovascular en curso en los residentes de la ciudad de Framingham, Massachusetts. El objetivo de la clasificación es predecir si el paciente tiene un riesgo de enfermedad cardiaca (CHD) en los próximos 10 años (CHD10)
El conjunto de datos proporciona la información de los pacientes e incluye más de 4.000 registros y 15 atributos (factores de riesgo potencial). Existen factores de riesgo tanto demográficos como de hábitos y médicos.

***Atributos:***
##### Demográfico:
* 0 - Sexo: 0-femenino y 1-masculino. (Categórica).
* 1 - Edad: Edad del paciente (años). (Numérica).
* 2 - Educación: [1- Educación Secundaria Obligatoria, 2- Bachillerato, 3-Formación Profesional de grado medio o superior, 4- Universidad]. (Categórica).

##### Hábitos:
* 3 - Fumador Actual: si el paciente es (1) o no (0) fumador actual. (Categórica) .
* 4 - Cigarillos día: la cantidad de cigarrillos que la persona fumó en promedio en un día (puede considerarse continuo ya que uno puede tener cualquier cantidad de cigarrillos, incluso medio cigarrillo). (Numérica).

##### Información sobre el historial médico en el momento del primer examen.:
* 5 - Meds PA: si el paciente tomaba o no medicamentos para la presión arterial en el momento del primer examen. (Categórica).
* 6 - Ictus prev: si el paciente ha tenido o no un ictus previo al momento del primer examen. (Categórica).
* 7 - Hipertensión: si el paciente era o no hipertenso en el momento del primer examen. (Categórica).
* 8 - Diabetes: si el paciente tenía o no diabetes en el momento del primer examen. (Categórica).

##### Información sobre la condición médica actual:
* 9 - Colesterol: nivel de colesterol total en la actualidad (mg/dL). (Numérica).
* 10 - PAS: presión arterial sistólica en la actualidad (mmHg). Se trata de la presión máx que ejerce el corazón al latir. (Numérica).
* 11 - PAD: presión arterial diastólica en la actualidad (mmHg). Se trata de la presión arterial entre latidos. (Numérica).
* 12 - IMC: Índice de Masa Corporal en la actualidad (kg/m2). (Numérica).
* 13 - RC: frecuencia cardíaca en la actualidad (latidos/min). (Numérica).
* 14 - Glucosa: nivel de glucosa en la actualidad (mg/dL). (Numérica).

##### Variable de destino para predecir:
* 15 - CHD10: Se trata de una variable binaria que indica si una persona tiene un riesgo de desarrollar una enfermedad coronaria en los próximos 10 años. Un valor de “1” significa que la persona tiene un riesgo de desarrollar una enfermedad coronaria en los próximos 10 años, mientras que un valor de “0” significa que la persona no tiene un riesgo significativo de sufrirlo. (Categórica).

![Las enfermedades cardiacas son la principal causa de muerte en España](https://www.clikisalud.net/wp-content/uploads/2021/04/enfermedad-cardiaca-vinculo-cancer.jpg)


### Objetivo ✨

La idea principal de este proyecto es utilizar algoritmos de predicción para analizar las probabilidades de sufrir una enfermedad cardiaca con la finalidad de obtener un algoritmo que resulte interesante.



### Pre-requisitos ⚙️

- Python


## Construido con 🛠️

* Python


## Autores ✒️

* Cristina Hidalgo
