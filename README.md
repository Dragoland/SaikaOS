# **SaikaOS**

**Autor:** [Dragoland](https://github.com/Dragoland)  
**Empresa:** SaikaNET Studio (Próximamente)  
**Fecha de Conceptualización:** Enero, 2026  
**Estado del Documento:** Planificación  
**Filosofía Central:** *"Las computadoras son creyentes y los usuarios, sus dioses."*  
**Lema del Sistema:** *"Fluye con tu trabajo."*

---

## **Tabla de Contenidos**
1.  [¿Qué es SaikaOS?](#1-qué-es-saikaos)
2.  [Filosofía y Visión](#2-filosofía-y-visión)
3.  [Arquitectura y Base Técnica](#3-arquitectura-y-base-técnica)
4.  [Características Principales](#4-características-principales)
5.  [Componentes Clave Incluidos](#5-componentes-clave-incluidos)
6.  [Estado Actual y Obtención](#6-estado-actual-y-obtención)
7.  [Contribuir y Soporte](#7-contribuir-y-soporte)
8.  [Licencia](#8-licencia)

---

## **1. ¿Qué es SaikaOS?**

SaikaOS es una distribución GNU/Linux **rolling-release** de propósito general, y el corazón tangible del **Project Saika**. No es un "fork" independiente; es una **curación y capa de integración** construida sobre la sólida base de Arch Linux.

Su objetivo es ofrecer una experiencia coherente, moderna y lista para usar, que combine el poder y la actualización continua de Arch con la innovación y la integración profunda de los componentes nativos del ecosistema Saika.

## **2. Filosofía y Visión**

Creemos en un sistema operativo que:
*   **Se Adapta al Contexto:** Siente, sugiere y se ajusta a tu flujo de trabajo.
*   **Prioriza la Coherencia:** Ofrece una experiencia unificada desde el kernel hasta la interfaz.
*   **Empodera con Claridad:** Da control total al usuario, pero presentado de forma organizada y accesible.
*   **Valora la Eficiencia:** Es rápido, ligero en recursos y visualmente fluido.
*   **Integra, No Aísla:** Combina lo mejor del software de código abierto con herramientas nativas diseñadas para trabajar en armonía.

## **3. Arquitectura y Base Técnica**

*   **Fundamento:** Basado en **Arch Linux**. Utilizamos los repositorios oficiales de Arch como fuente principal para el 95% del software, garantizando actualizaciones rápidas y una base masivamente probada.
*   **Capa Saika:** Añadimos nuestros propios repositorios (`saika-core`, `saika-extra`) que contienen:
    *   El entorno de escritorio **SaikaDesktop (SDE)**.
    *   Las aplicaciones nativas de **Saika Suite**.
    *   El gestor de sesiones **SDKO**.
    *   Temas, kernels optimizados y configuraciones específicas.
*   **Filosofía de Mantenimiento:** "Arch, con amor y cohesión". Nos enfocamos en mantener nuestra capa de integración y polimento, no en reempaquetar todo el ecosistema de Arch.

## **4. Características Principales**

1.  **Experiencia de Escritorio Adaptable:** Incluye por defecto **SaikaDesktop (SDE)**, con sus tres modos fluidos (Ola/Ventana, Corriente/Mosaico, Toque/Táctil).
2.  **Configuración Opinada y Lista para Usar:** Viene preconfigurado con SDE, controladores esenciales, codecs multimedia y herramientas de desarrollo clave, siguiendo las mejores prácticas de seguridad y usabilidad de Saika.
3.  **Instalador Gráfico Propio (En desarrollo):** Un instalador moderno e intuitivo que simplifica el proceso de instalación de Arch sin esconder opciones avanzadas para usuarios expertos.
4.  **Kernel Saika (Opcional):** Ofrecemos un kernel Linux compilado con parches para mejorar la capacidad de respuesta interactiva (`linux-zen` como base) y soporte para hardware moderno.

## **5. Componentes Clave Incluidos**

SaikaOS integra de forma nativa los siguientes componentes del Project Saika:
*   **SDE (SaikaDesktop Environment):** El entorno de escritorio dinámico y contextual.
*   **SDKO (Saika Display Kiosk & Orchestrator):** El gestor de inicio de sesión y orquestador de perfiles.
*   **Saika Suite (En desarrollo):** Aplicaciones nativas como el Centro de Control KAI y el gestor de archivos RYU.

## **6. Estado Actual y Obtención**

*   **Estado:** SaikaOS se encuentra actualmente en **fase de planificación y desarrollo temprano**. Seguimos la hoja de ruta definida en el documento general del Project Saika.
*   **ISO y Paquetes:** Las imágenes ISO instalables y los paquetes individuales estarán disponibles públicamente una vez que se alcancen los hitos de la Fase 3 de desarrollo. El código será abierto desde las primeras etapas en la organización [SaikaNET Studio](https://github.com/SaikaNET-Studio).

## **7. Contribuir y Soporte**

*   **Desarrollo:** Apreciamos cualquier contribución. El desarrollo se realizará abiertamente en GitHub/GitLab. Se publicarán guías de contribución una vez que los repositorios estén activos.
*   **Comunidad:** Planeamos construir una comunidad inclusiva en foros y salas de chat (Matrix/Discord) para soporte, discusiones y feedback.
*   **Soporte:** Inicialmente, el soporte será comunitario. SaikaNET Studio explorará ofrecer soporte profesional en el futuro.

## **8. Licencia**

SaikaOS es y siempre será **software de código abierto**. Los componentes específicos de Saika se publicarán bajo licencias GPL, LGPL u otras licencias libres apropiadas. El software base de Arch Linux y los repositorios oficiales mantienen sus respectivas licencias.

---
**SaikaOS** es más que una distribución; es la materialización de una visión para una computación más fluida, personal e inteligente. El camino es largo, pero cada paso se da sobre los hombros de gigantes y con la pasión de una comunidad que cree en un futuro mejor para el escritorio Linux.

**"Fluye con tu trabajo."**
