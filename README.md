Automatización QA - Flujos desaucedemo.com
📄 Descripción General del Proyecto
Este repositorio contiene la Pre-Entrega del curso de Automatización QA, cuyo enfoque principal es la aplicación práctica de los conocimientos adquiridos. El proyecto se centra en la automatización de las interacciones esenciales en el sitio web de comercio electrónico de prueba https://www.saucedemo.com.

El objetivo es establecer una base sólida para el testing automatizado, cubriendo desde el acceso al sistema hasta la gestión básica del carrito de compras, utilizando las mejores prácticas con Python y Selenium.

🚀 Funcionalidades Automatizadas (Casos de Prueba)
Se han cubierto los siguientes escenarios de usuario:

Módulo	Escenario de prueba	Objetivo de la Validación
Acceso	Acceso al Sistema	Verificar el inicio de sesión exitosa con credenciales estándar.
Inventario	Validación de Interfaz	Comprobar el título de la página y la presencia de productos y elementos clave (filtros, menú).
Carrito	Interacción con Productos	Agregue un producto, valide el incremento del contador del carrito y confirme su presencia en la vista del carrito.
🛠️ Tecnologías y Herramientas
Tecnología	Rol en el Proyecto
Pitón	Lenguaje de programación principal para la escritura de los tests .
Controlador web de Selenium	Herramienta para la interacción y automatización de las acciones del navegador.
Pytest	Framework de pruebas unitarias utilizadas para la ejecución estructurada de los casos de prueba.
Administrador de WebDriver	Gestión automática de los drivers del navegador (ej. ChromeDriver).
Pytest-HTML	Generación de informes detallados en formato HTML.
Git y GitHub	Sistema de control de versiones y hosting del código fuente.
📁 Estructura del Repositorio
La organización del proyecto se adhiere a una estructura modular para facilitar la escalabilidad y el mantenimiento:

preentrega-rodriguezjorge/ 
├── test/ 
│     ├── test_login.py         # Pruebas relacionadas con el Login. 
│     ├── test_inventory.py     # Pruebas de Inventario y Elementos. 
│     └── test_productos.py     # Pruebas de Carrito y Flujo de Productos.
│ 
├── utils.py                # Funciones Login (Inicialización de Chrome/Driver). 
├── conftest.py             # Hooks de Pytest, fixtures. 
├── report.html             # Reporte final generado por pytest. 
├── README.md               # Describe las funcionalidades del programa. 
├── run_tests.py            # Archivo main para la ejecución de los tests. 
└── requirements.txt        # Listado de dependencias del proyecto.
⚙️ Configuración e instalación

Clonar el Repositorio
    git clone https://github.com/ABurgos86/Preentrega-BurgosCarlosAriel.git

    cd preentrega-BurgosCarlosAriel

Instalar dependencias

Asegúrese de tener Python instalado. Luego, instale las bibliotecas necesarias:

pip install selenium
pip install pytest
pip install webdriver-manager
pip install pytest-html

(Alternativamente, puedes usar pip install -r requisitos.txt si se genera el archivo).
