# QA-Automation-Course

**README.md - QA Automation Code**

**English Version:**

## QA Automation Code using Selenium and TestNG

This repository contains automated test scripts written in Java for web application testing using Selenium and TestNG. The tests are designed to verify the functionality of a demo website for user login.

### Prerequisites

Before running the test scripts, ensure that you have the following components set up:

1. **Java Development Kit (JDK):** Make sure you have Java installed on your machine. You can download it from [here](https://www.oracle.com/java/technologies/javase-downloads.html).

2. **WebDriver:** This project uses ChromeDriver as the WebDriver for Selenium. Download the appropriate ChromeDriver executable based on your operating system from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads). Make sure to set the `webdriver.chrome.driver` system property in the code to point to the location of the downloaded ChromeDriver executable.

### Getting Started

1. Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/yourusername/QA-Automation-Selenium-TestNG.git
   ```

2. Open the project in your preferred Java IDE.

3. Set the correct path to the `chromedriver.exe` file in the `setUp()` method of the `Tests` class.

4. Run the tests:
   - Test `pruebaUno` demonstrates a less efficient way of interacting with web elements using basic Selenium commands.
   - Test `pruebaDos` demonstrates a more efficient approach using Page Object Model (POM) design pattern.

5. After running the tests, the browser window will automatically close.

### Structure

The project structure is as follows:

- `testsJava` package:
  - `Tests` class: Contains test methods.
  - `helpers` package: Contains utility classes for test automation.
  - `pages` package: Contains page classes using the Page Object Model pattern.

### Contributors

- [Guido Aranda](https://github.com/GuidiUZ)

---

**Versión en Español:**

## Código de Automatización de QA utilizando Selenium y TestNG

Este repositorio contiene scripts de pruebas automatizadas escritos en Java para la prueba de aplicaciones web utilizando Selenium y TestNG. Las pruebas están diseñadas para verificar la funcionalidad de un sitio web de demostración para inicio de sesión de usuarios.

### Requisitos Previos

Antes de ejecutar los scripts de prueba, asegúrate de tener configurados los siguientes componentes:

1. **Java Development Kit (JDK):** Asegúrate de tener Java instalado en tu máquina. Puedes descargarlo desde [aquí](https://www.oracle.com/java/technologies/javase-downloads.html).

2. **WebDriver:** Este proyecto utiliza ChromeDriver como el WebDriver para Selenium. Descarga el ejecutable de ChromeDriver correspondiente a tu sistema operativo desde [aquí](https://sites.google.com/a/chromium.org/chromedriver/downloads). Asegúrate de configurar la propiedad del sistema `webdriver.chrome.driver` en el código para que apunte a la ubicación del ejecutable de ChromeDriver descargado.

### Empezando

1. Clona este repositorio en tu máquina local usando el siguiente comando:
   ```
   git clone https://github.com/tunombreusuario/QA-Automation-Selenium-TestNG.git
   ```

2. Abre el proyecto en tu IDE Java preferido.

3. Configura la ruta correcta al archivo `chromedriver.exe` en el método `setUp()` de la clase `Tests`.

4. Ejecuta las pruebas:
   - La prueba `pruebaUno` demuestra una manera menos eficiente de interactuar con elementos web usando comandos básicos de Selenium.
   - La prueba `pruebaDos` demuestra un enfoque más eficiente utilizando el patrón de diseño Page Object Model (POM).

5. Después de ejecutar las pruebas, la ventana del navegador se cerrará automáticamente.

### Estructura

La estructura del proyecto es la siguiente:

- Paquete `testsJava`:
  - Clase `Tests`: Contiene los métodos de prueba.
  - Paquete `helpers`: Contiene clases de utilidad para la automatización de pruebas.
  - Paquete `pages`: Contiene clases de página utilizando el patrón Page Object Model.

### Colaboradores

- [Guido Aranda](https://github.com/GuidiUZ)
