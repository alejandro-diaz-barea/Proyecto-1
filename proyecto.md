# **Proyecto 1: Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente**
![Alt text](image-2.png)
## **PARTE 1 : Modelos de Programación en Entornos Cliente/Servidor**

## **Modelos cliente/servidor más comunes con ejemplos**


### **Modelo Cliente/Servidor de 2 Capas (2-Tier)**

En este modelo el Cliente sirve para la interfaz y presentación y 
el Servidor para la lógica de negocios y datos, como lo es la base de datos.

Este modelo es adecuado para aplicaciones simples donde la lógica se encuentra principalmente en el servidor y el cliente se enfoca en la presentación.

Este tipo de modelo simple es utilizado en la aplicacion de correo electrónico.

### **Modelo Cliente/Servidor de 3 Capas (3-Tier)**

Este modelo agrega una capa intermedia entre el cliente y el servidor.El cliente sigue siendo responsable de la interfaz de usuario y la presentación de datos.La capa intermedia se encarga de la lógica de la aplicació y la validación de datos.El servidor sigue manejando la lógica de negocio y la gestión de datos.

Este modelo es útil para aplicaciones más complejas que requieren una separación clara de responsabilidades.

Este modelo es utiliza en aplicaciones de sistemas de gestión de inventario.

### **Modelo Cliente/Servidor de N Capas (N-Tier)**

Este modelo es una extensión del modelo de 3 capas con múltiples capas intermedias según la complejidad de la aplicación.

El modelo de 3 capas se utiliza en apliaciones empresariales grandes debido a que las capas que se añaden que suelen ser de seguridad pero añaden mayor complejidad para proyectos mas pequeños.

### **Modelo Cliente/Servidor Peer-to-Peer (P2P)**

En este modelo no hay un servidor centralizado, los nodos se comunican directamente entre sí, cada nodo puede actuar como cliente y servidor al mismo tiempo.

Este modelo es utilizado en Redes de intercambio de archivos P2P como BitTorrent.


## **Parte 2 : Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web**

### **Estudio de cómo se ejecuta el código JavaScript en un navegador**

1- Abres el buscador Chrome en su ordenador.

2- Haz clic en Más y luego Configuración.

3- Selecciona Seguridad y privacidad.

4- Haz clic en Configuración de sitios.

5- Haz clic en JavaScript.

6- Seleccione Los sitios pueden usar JavaScript.

###  **Compatibilidad entre navegadores**

Cada buscador puede leer javascript de manera diferente, he buscado en los navegadores mas importantes(Firefox, Explorer, Chrome, Safari y algunos más) y lo más relevante en la forma de interpretar son que :

  
- Las alertas pueden verse diferentes en distintos navegadores ya que cada navegador tiene su propia interfaz y hay objetos o alertas que se realizan con javascript que se pueden ver de otra manera pero realizan la misma función.
- La ejecución de JavaScript depende de la configuración de seguridad y la activación de JavaScript, lo que varía entre navegadores.
- Factores como el navegador, sistema operativo y dispositivo pueden influir en los resultados.

### **Resolución de problemas de compatibilidad en una aplicación web.**

La solución mas efectiva para abordar estos problemas de comptatibilidad en una aplicación web en diferentes pltaformas es la utilización de herramientas de prueba multi-navegador, como Comparium. Comparium tiene una parte gratis muy útil como la opción de realizar pruebas paralelas.

Comparium es una herramienta versátil que funciona en la gran mayoría de plataformas. Su interfaz es intuitiva y tiene funciones adicionales, como pruebas automatizadas y compatibilidad con scripts personalizados de Selenium.

Además simplifica muchas pruebas multi-navegador con capturas que comparan incompatibilidades, por lo que ahorra tiempo y recursos a los dessarrolladores.
## **Parte 3 - Lenguajes de Programación en Entorno Cliente.**

### **Lenguajes de progrmacion en entorno cliente, compración de características y aplicaciones**

La principal diferencia entre JavaScript y TypeScript es su sistema de tipos. JavaScript puede tener errores en tiempo de ejecución, mientras que TypeScript es ayuda a detectar errores durante el desarrollo.

TypeScript ofrece mejores herramientas en entornos de desarrollo y tiene características como interfaces y decoradores. También se es compatible con JavaScript.

En cuanto a sus aplicaciones, JavaScript es ampliamente utilizado en desarrollo web para la creación de sitios web interactivos y dinámicos.Por otro lado, TypeScript es útil en grandes proyectos y en entornos empresariales. Proporciona un mayor control sobre el código y ayuda a evitar errores costosos en aplicaciones complejas.


## **Parte 4 : Características de los Lenguajes de Script. Ventajas y Desventajas:**

#### **Ventajas de la programación en lenguajes de script:**

- Requieren menos código y tiempo para tareas, agilizando el desarrollo.
- Sintaxis más simple ideal para principiantes.
- Adaptables en tipos de datos y estructuras.
- Amplia comunidad y recursos en línea para resolver problemas.
  
#### **Desventajas de la programación en lenguajes de script:**

- Suelen ser más lentos al interpretarse en tiempo de ejecución, no adecuados para aplicaciones de alto rendimiento.
- Problemas de tipo y otros pueden pasar desapercibidos hasta la ejecución.
- Vulnerabilidad a ataques de seguridad si no se manejan adecuadamente.

## **Parte 5 : Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML:**

### **Exploración de tecnologías como CSS y HTML5.**

La primera forma de insertar JavaScript en HTML5 puedes hacerlo utilizando la etiqueta script que devuelve todo el código JavaScript que escribas. Se puede agregar el código JavaScript:

- entre las etiquetas head
- entre las etiquetas body

En general es recomendable cargarlo en el head para que este separado del contenido del archivo html, pero poner en el body puede ayudar a mejorar la velocidad de carga.

La segunda opción es hacer referencia a estos archivos desde adentro de los documentos HTML, igual que a los documentos CSS. Algunos de los beneficios de agregar código JavaScript en archivos separados son:

- El código se ve más limpio
- La legibilidad y el mantenimiento del código es mucho más fácil.
- Los archivos JavaScript en caché mejoran el rendimiento general del sitio web al disminuir el tiempo que tardan las páginas en cargarse.

### **Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras.**
He hecho un ejemplo de como se ejecutario en el head con un código sencillo con un botón que envía el mensaje de hola mundo.

![Alt text](image.png)

![Alt text](image-1.png)
El resultado nos sale una alerta que dice el Hola Mundo.

He hecho otro ejemplo con el mismo código pero desde un archivo externo.
![Alt text](image-3.png)

Aquí está el archivo

![Alt text](image-4.png)

Este es el resultado:

![Alt text](image-5.png)
## **Parte 6 : Herramientas de Programación**

### **Visual Studio Code (VSCode):**

#### Ventajas:

- Potente y personalizable.
- Excelente integración con Git.
- Depuración integrada.
- Gran comunidad de usuarios.
#### Desventajas:

- Requisitos de recursos.
- Curva de aprendizaje.
  
###  **Chrome DevTools:**

#### Ventajas:

- Depuración en tiempo real.
- Facilidad de uso.
- Acceso a información detallada sobre rendimiento.
#### Desventajas:

- Limitado a Chrome.
- Dependencia del navegador.

### **Sublime Text:**

#### Ventajas:

- endimiento rápido.
- Interfaz sencilla.
- Amplia comunidad de usuarios.
#### Desventajas:

- Carece de herramientas de depuración integradas.
- Funcionalidad limitada sin extensiones.

## **BIBLIOGRAFÍA**

### Parte 1:
- [ Enlace de los modelos de 2,3 y n capas ](https://www.ionos.es/digitalguide/servidores/know-how/modelo-cliente-servidor/)
-  [ Enlace del modelo P2P ](https://www.ionos.es/digitalguide/servidores/know-how/que-es-p2p-peer-to-peer/)
### Parte 2:
-  [ Estudio de como ejecutar en el navegador javasript ](https://keepcoding.io/blog/como-ejecutar-el-codigo-de-javascript/)
- [Diferencias entre navegadores cuando se ejecuta javascript](https://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=783:diferencias-de-navegadores-ante-javascript-firefox-explorer-chrome-safari-javascript-en-linea-cu01108e&catid=78&Itemid=206)
- [Resolución de problemas de compatibilidad en una aplicación web ](https://comparium.app/es/blog/cross-browser-compatibility-issues/#:~:text=Problemas%20de%20compatibilidad%20multi%20navegador%20y%20sus%20soluciones,8%20Falta%20de%20Pruebas%20en%20Dispositivos%20Reales%20)

### Parte 3 :
- [ Lenguajes de progrmacion en entorno cliente, compración de características y aplicaciones ](https://appmaster.io/es/blog/javascript-vs-mecanografiado)

### Parte 4:
- [ Características de los Lenguajes de Script. Ventajas y Desventajas: ](https://www.hostgator.mx/blog/scripting/)
### Parte 5:
- [Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras. ](https://www.hostinger.es/tutoriales/insertar-javascript-en-html/#:~:text=Agregar%20JavaScript%20directamente%20a%20un%20archivo%20HTML,-La%20primera%20forma&text=Puedes%20hacerlo%20utilizando%20la%20etiqueta,entre%20las%20etiquetas)

### Parte 6 : 
- [ VSCODE ](https://webdesigncusco.com/ventajas-y-desventajas-de-visual-studio-code-2022/)
- [Chrome devtools](https://blog.ida.cl/desarrollo/conoce-los-principales-aspectos-chrome-devtools/)
- [Sublime text ](https://editorsublimetext.blogspot.com/2020/11/ventajas-y-desventajas-del-editor.html)