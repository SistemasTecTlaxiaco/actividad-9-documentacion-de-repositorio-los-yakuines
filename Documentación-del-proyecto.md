# Documentación del Proyecto: Academy
## 📝 1. Introducción y Visión del Equipo
Como equipo de desarrollo, hemos consolidado **Academy**, una plataforma integral de gestión académica que fusiona la potencia del desarrollo Full-Stack con la seguridad disruptiva de la tecnología **Blockchain**. Nuestra visión principal fue diseñar un ecosistema donde la administración de información escolar (alumnos, docentes y materias) deje de ser un proceso centralizado y vulnerable, para convertirse en un sistema transparente y auditable.
A través de **Academy**, hemos implementado una solución que utiliza la red **Stellar** para certificar hitos académicos, garantizando que cada registro sea inmutable. Este proyecto representa nuestro compromiso con la innovación tecnológica, aplicando arquitecturas modernas que responden a las demandas actuales de seguridad digital en el sector educativo.
## 🏗️ 2. Arquitectura General del Sistema
Para asegurar un rendimiento óptimo y una escalabilidad real, nuestro equipo diseñó una arquitectura de cuatro capas. Este diseño permite que cada componente trabaje de forma independiente pero perfectamente sincronizada, facilitando el mantenimiento y la auditoría del sistema.


### Descripción detallada de nuestro flujo:
 * **Capa de Presentación (Frontend):** Desarrollada con **React.js**, implementamos una interfaz administrativa basada en módulos. El uso de un **Sidenav** dinámico permite una navegación fluida por el ecosistema de "School Manager", optimizando la experiencia del usuario final.
 * **Capa de Lógica (Backend):** Nuestro servidor en **Node.js** actúa como el núcleo del sistema, gestionando peticiones asíncronas de manera eficiente. Esta capa se encarga de la validación de seguridad y la orquestación entre la base de datos y la blockchain.
 * **Capa de Persistencia (Híbrida):** * **MongoDB:** Actúa como nuestro almacenamiento de alta velocidad para datos operativos y catálogos escolares.
   * **Stellar SDK:** Es el puente que permite a nuestro backend comunicarse con la red de bloques para la firma y envío de transacciones.
 * **Capa Web3 (Smart Contracts):** Implementamos contratos inteligentes en **Soroban**, los cuales se ejecutan en la **Stellar Testnet** para registrar las operaciones críticas de manera inmutable.
## 🛠️ 3. Tecnologías y Estándares Utilizados
Nuestro stack tecnológico fue seleccionado para cumplir con los más altos estándares de desarrollo profesional:
 * **Desarrollo del Cliente:** **React** para una interfaz reactiva y modular.
 * **Entorno del Servidor:** **Node.js**, seleccionado por su excelente manejo de concurrencia y promesas, vital para la integración con APIs de Blockchain.
 * **Almacenamiento:** **MongoDB Atlas** para una gestión de datos flexible y escalable.
 * **Ecosistema Blockchain:** Uso de la red oficial **Stellar Testnet**, **Stellar SDK** para la conectividad y **Soroban** para la lógica de contratos inteligentes.
 * **Documentación de Código:** Nos hemos esforzado por entregar un código auto-documentado. Cada módulo crítico incluye comentarios **inline** y **docstrings** que detallan no solo la función, sino la lógica de seguridad y el manejo de excepciones, facilitando futuras auditorías.
## 📖 4. Guía de Instalación y Replicabilidad
Como equipo, facilitamos el proceso de despliegue para asegurar que el proyecto sea completamente reproducible:
 * **Repositorio Oficial:** https://github.com/SistemasTecTlaxiaco/Academy
 * **Procedimiento Técnico:**
   1. Clonación del repositorio mediante Git.
   2. Instalación de dependencias del servidor y cliente con el comando npm install.
   3. Configuración de variables de entorno (.env) incluyendo el **Contract ID** y las **Secret Keys** de la wallet de prueba.
   4. Despliegue de los Smart Contracts en la red de prueba y ejecución del servidor de desarrollo.
## 📸 5. Evidencias de Ejecución y Validación
En esta sección presentamos los activos visuales que validan el éxito de nuestra integración técnica y el cumplimiento de los objetivos del proyecto:


