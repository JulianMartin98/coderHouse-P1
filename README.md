<div align="center">
  <h1 align="center">  # CoderHouse - Pre-Entrega Proyecto Final </h1> <a name="inicio"></a>
</div>

<div>
  <h2>  Julián Antonio Martín - Comisión: 68735 </h2> <a name="inicio"></a>
</div>

## 📃 Indice 📃
* [Introducción](#inicio)
* [ Defectos Detectados ](#defectos_detec)
* [1 - Defectos Visuales](#defecto_vis)
* [2 - Defectos de Contenido](#defecto_cont)
* [3 - Reporte de Pruebas](#reporte)
* [4 - Conclusiones del Reporte](#conclusiones_rep)
* [5 - Stress-Test](#stress_test)
* [6 - Tecnologías Utilizadas](#tecnologias)



## ✏ Introducción ✏ <a name="inicio"></a>

#### ▫ **Error:** Es una equivocación humana, normalmente en el análisis o desarrollo del software. Por ejemplo, un programador comete un error al escribir una fórmula incorrecta para calcular un descuento. Este error puede derivar en un problema en el código.
#### ▫ **Defecto:** Es la manifestación del error en el software. Si el error no se detecta y corrige en la fase de desarrollo, se convierte en un defecto. Por ejemplo, debido al error en la fórmula, la aplicación calcula mal el descuento, provocando una diferencia en los precios finales.
#### ▫ **Fallo:** Es la manifestación visible del defecto cuando el software se ejecuta, afectando la experiencia del usuario. Por ejemplo, cuando el usuario intenta aplicar el descuento, observa que el monto es incorrecto debido a la fórmula mal programada.

  ### 📚 Clasificación de Defectos y Criticidad 📚
Los defectos en software pueden clasificarse en distintas categorías según su naturaleza y el impacto en el sistema. Además, la criticidad y urgencia de cada defecto son elementos clave en su clasificación y resolución, ya que determinan la prioridad de atención en el reporte.

## 📋 Tipos de Defectos 📋
  ### 1. Defectos Visuales:

#### Afectan la apariencia o usabilidad del sistema, como diferencias entre el diseño planificado y el implementado.
**Ejemplo:** Un botón de "Enviar" aparece desalineado o con un color incorrecto.

  ### 2. Defectos en Componentes:

#### Relacionados con el mal funcionamiento de elementos específicos del sistema, que no cumplen con la funcionalidad esperada.
**Ejemplo:** Al ingresar un nombre en el campo "Usuario", el sistema no lo registra correctamente.

  ### 3. Defectos de Contenido:

Son errores en la información mostrada que no están relacionados con la funcionalidad o el diseño, sino con el contenido.
**Ejemplo:** La sección de "Política de Privacidad" contiene fechas o referencias incorrectas.

  ### 4. Defectos Disruptivos:

#### Los más graves, ya que afectan la funcionalidad general, impidiendo que el sistema opere correctamente.
**Ejemplo:** Un cambio en el sistema provoca que la pantalla principal no cargue, dejando al usuario sin acceso.
## 💡 Importancia de la Criticidad y Urgencia 💡
**Criticidad:** Indica el impacto potencial del defecto en el sistema, ayudando a identificar la gravedad del daño.

**Ejemplo:** Un defecto crítico puede bloquear el acceso de los usuarios a funciones clave.

**Urgencia:** Define la rapidez con la que debe solucionarse el defecto para evitar problemas mayores.

---

## ❌❗ Defectos Detectados ❗❌   <a name="defectos_detec"></a>

  ✅ A continuación se detallara los defectos detectados en la web seleccionada (https://petstore.octoperf.com/actions/Catalog.action), acompañados de una imagen o gift de forma ilustrativa (según corresponda) para mas detalles e indicaciones para replicar dicho defecto mencionado.

---

### ❌ Defectos Visuales ❌   <a name="defecto_vis"></a>
  ❎ Diseño y contenido desproporcionado. La imagen central no ocupa toda la pantalla, no cuenta con un footer pegado al pie de página. Se observan bordes grises tanto por los lados como por debajo de la imagen central.
  
  ❎ El cuadro de búsqueda tiene un diseño deficiente. El campo de entrada es muy pequeño y desproporcionado con respecto al botón "Search", lo que puede afectar la experiencia del usuario.

  ❎Los colores de fuente utilizados en el footer (Azul Oscuro) se pierden y dificultan tanto al usuario como al product Owner la lectura del mismo.

<p align="center"><img src="https://github.com/user-attachments/assets/d09da927-2f6f-49de-ac20-87778294f89b" width="50%"/></p>

----


----

### ❌ Defectos en Contenido ❌   <a name="defecto_cont"></a>
  ❎ La frase en la barra azul "Elevate you load-testing with OctoPerf!" tiene un error gramatical en inglés. Debería decir "Elevate your load-testing with OctoPerf!.
  
  ❎ Las imagenes utilizadas en las descripciones de perros no coincide con la raza que se ha seleccionado.

  
  <p align="center"><img src="https://github.com/user-attachments/assets/cf9c92e5-cfa6-4515-8914-89679ba70e41" width="50%"/></p>
  <p align="center"><img src="https://github.com/user-attachments/assets/8c13dc08-4341-4285-a977-38a39690ee19" width="50%"/></p>
  <p align="center"><img src="https://github.com/user-attachments/assets/25735aa6-6e5f-4376-8fce-78abf3f88890" width="50%"/></p>

---

  <h2 align="center"> 🧪📈  Reporte de Pruebas 📈🧪  </h2> <a name="reporte"></a>


  <div align="center">

  ###  Casos de Prueba Ejecutados 

| ID   | Nombre                                                              | Prioridad | Estado   |
|------|---------------------------------------------------------------------|-----------|----------|
| C-01 | Búsqueda de producto válido                                         | Alta      | Exitoso  |
| C-02 | Navegar por categorías                                              | Media     | Exitoso  |
| C-03 | Registro de usuario                                                 | Alta      | Exitoso  |
| C-04 | Login con datos válidos                                             | Alta      | Exitoso  |
| C-05 | Agregar producto al carrito                                         | Alta      | Exitoso  |
| C-06 | Búsqueda de producto / mascota inexistente                          | Media     | Exitoso  |
| C-07 | Registro con campos vacíos                                          | Alta      | Fallido  |
| C-08 | Login con datos inválidos / vacíos                                  | Alta      | Fallido  |
| C-09 | Búsqueda con caracteres especiales (/*-+%,etc)                      | Alta      | Fallido  |
| C-10 | Modificar cantidad en carrito con caracteres inválidos              | Alta      | Fallido  |
| C-11 | Modificar cantidad en carrito                                       | Alta      | Fallido  |
| C-12 | Completar compra                                                    | Alta      | Fallido  |





### 🚨 Defectos Encontrados 🚨  

| ID   | Nombre o Título                                                                 | Tipo Defecto  | Criticidad |
|------|----------------------------------------------------------------------------------|---------------|------------|
| 001  | Las imágenes utilizadas en las descripciones no coinciden con la mascota real   | Visual        | Baja       |
| 002  | El registro no informa al usuario en caso de error o campo vacío                | Componente    | Alta       |
| 003  | Se permite completar compra con datos falsos                                    | Disruptivos   | Alta       |

</div>

<p></p>

## <p> ✍ Conclusiones del Reporte ✍ </p>    <a name="conclusiones_rep"></a>
El 60% de las pruebas fueron positivas, para ejecutar las pruebas se utilizó el material teórico y lo
aprendido en clase por CoderHouse.
Se reportan 3 bugs de distintos tipos (visual, componente y disruptivos) siendo el ultimo uno de los mas
importantes y con una criticidad muy alta.



---

<h2 align="center">🧪📈 Pruebas de Stress 📈🧪</h2> <a name="stress_test"></a>


## ✏ Introducción

Las pruebas de estrés se aplican para evaluar la estabilidad de un sistema bajo condiciones extremas. Estas pruebas ayudan a identificar el punto de fallo del sistema al sobrecargarlo con solicitudes más allá de su capacidad habitual.

Se realizan en momentos de alta demanda o en eventos especiales, como el **Black Friday** o **transmisiones masivas**, para garantizar que el sistema pueda manejar picos sin fallar. Esto permite ajustar la infraestructura y prever posibles mejoras en la capacidad del sistema.

---

## 🎯 Objetivos 🎯

A continuación, se realizarán **4 pruebas no funcionales** con **Lighthouse**, tanto en modo **Desktop (Escritorio)** como **Mobile**, obteniendo un promedio de resultados entre ambas modalidades.

- **Sitio probado:** [https://petstore.octoperf.com/actions/Catalog.action](https://petstore.octoperf.com/actions/Catalog.action)  
- **Herramienta utilizada:** [Google Lighthouse](https://es.semrush.com/blog/como-utilizar-google-lighthouse/)  
- **Dispositivo:** Mobile y Desktop

---

### 🔍 Tipos de Pruebas 🔍

1. **Performance**  
   Mide la velocidad de carga y respuesta del sitio, evaluando aspectos como el tiempo de renderizado y la carga de recursos.

2. **Accessibility**  
   Evalúa qué tan usable es el sitio para personas con discapacidades, considerando elementos como contraste, etiquetas y navegación con teclado.

3. **Best Practices**  
   Revisa si el sitio sigue recomendaciones de desarrollo web moderno, como el uso seguro de APIs y la ausencia de errores de JavaScript.

4. **SEO**  
   Analiza si la página está optimizada para motores de búsqueda, verificando el uso adecuado de etiquetas, metadatos y estructura del contenido.

  A Continuacion se mostrarán dos imagenes utilizadas en los 4 casos de prueba tanto como en mobile, como en deskopt (escritorio).

  <p align="center"><img src="https://github.com/user-attachments/assets/07e45671-7fa6-47bc-947d-b4259e2918ad" width="50%"/></p>
  <p align="center"><img src="https://github.com/user-attachments/assets/5bffdd5e-e704-40ac-b62a-5ae9df0dab2e" width="50%"/></p>



## <p> ✍ Conclusiones de las Stress-Test ✍ </p>    <a name="stress_test"></a>

## Conclusión MOBILE: En esta versión del sitio evaluado, el rendimiento (Performance) es excelente con un 98%,
pero hay debilidades importantes en Accesibilidad (53%) y SEO (50%), lo cual puede afectar la usabilidad y visibilidad
en buscadores. Las Buenas Prácticas (82%) están en un nivel aceptable, aunque aún hay margen de mejora. En
general, el sitio es rápido, pero necesita ajustes técnicos y de accesibilidad para ofrecer una mejor experiencia
integral.

## Conclusión DESKOPT: En la versión de Deskopt (Escritorio), el sitio muestra un rendimiento (Performance)
sobresaliente (99,75%) y buenas prácticas (Best-Practices) sólidas (89%), lo que indica una base técnica eficiente. Sin
embargo, la accesibilidad (Accessibility) (53%) y el SEO (50%) siguen siendo bajos, lo que puede limitar la experiencia
de usuarios con discapacidades y reducir la visibilidad en motores de búsq



---

## Tecnologías Utilizadas 🛠️  <a name="tecnologias"></a>

<div align="center">
    <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
    <img src="https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white" />
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
    <img src="https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white" />
    <img src="https://img.shields.io/badge/Lighthouse-F44B21?style=for-the-badge&logo=Lighthouse&logoColor=white" />
    <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" />
    <img src="https://github.com/JulianMartin98/coderHouse-P1/blob/main/CoderHouseV2.png" height="28"/>
</div>


-----



