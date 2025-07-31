# SGBDR-IA: Sistema de Gestión de Bases de Datos Relacional Integrado con Inteligencia Artificial

Este proyecto tiene como propósito la construcción de un Sistema de Gestión de Bases de Datos Relacional (SGBDR) fuertemente acoplado con redes neuronales artificiales, orientado a la medición de eficiencia en operaciones DML (Data Manipulation Language) que incluyen el manejo de imágenes. Se busca integrar mecanismos de inteligencia artificial dentro del núcleo de procesamiento de datos para optimizar consultas, clasificar imágenes y proporcionar una interfaz intuitiva para usuarios y desarrolladores.

## Características principales

- 📦 Gestión relacional completa con soporte SQL.
- 🧠 Clasificación automática de imágenes usando redes neuronales.
- 📊 Evaluación de eficiencia en operaciones DML con datos visuales.
- 🛠️ Integración de modelos de IA entrenados para tareas de reconocimiento.
- 🖼️ Almacenamiento y recuperación de imágenes dentro del sistema relacional.
- 💻 Interfaz CLI para administración y consultas híbridas.

## Tecnologías utilizadas

- **Lenguaje base:** Java
- **Gestor de dependencias:** Maven
- **Base de datos:** PostgreSQL
- **IA y clasificación:** Redes neuronales entrenadas (TensorFlow/Keras)
- **Otras herramientas:** JDBC, JUnit, Git, GitHub

## Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/HaroldAvila24/SGBDR-IA.git
   cd SGBDR-IA
2. Compilar el proyecto:
    mvn clean install

3. Configurar la base de datos PostgreSQL con los scripts proporcionados en el directorio /sql.

4. Ejecutar el sistema
## Uso
- Para insertar una imagen con su clasificación automática:

INSERT INTO imagenes VALUES ('ruta de imagen');

El sistema identificará automáticamente la clase de la imagen y la almacenará junto con sus metadatos.

- Para realizar una consulta con IA:

SELECT * FROM imagenes WHERE clase_predicha = 'ruta de imagen';

Estructura del repositorio:

SGBDR-IA/
├── src/                      # Código fuente del sistema
│   └── main/java/           # Módulos Java principales
├── models/                  # Modelos de redes neuronales
├── sql/                     # Scripts de base de datos
├── docs/                    # Documentación técnica
├── pom.xml                  # Archivo de configuración de Maven
└── README.md                # Este archivo

Contribuciones: 
Este proyecto fue desarrollado como parte de un trabajo de grado en la Universidad de Nariño. Si deseas contribuir, por favor crea un fork, realiza tus cambios y envía un pull request.

Autores:

- Mg. Héctor Andrés Mora Paz

- Yeison Alfredo Micolta Rodríguez

- Yesenia Castro Arboleda

- Harold Stiven Avila Araujo

Año: 2025
Universidad: Universidad de Nariño
País: Colombia

Licencia
Este proyecto está licenciado bajo la Licencia MIT.
