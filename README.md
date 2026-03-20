# 🏦 Apache Fineract Customization - Savings & Loan Optimization
> **Backend Java Development | Financial Systems | Performance Tuning**

Este proyecto detalla mi colaboración técnica en el ecosistema de **Apache Fineract**, enfocada en la optimización de procesos críticos de carga masiva de datos y resolución de incidencias en el módulo de ahorros.

---

## 🚀 Tecnologías y Herramientas
* **Lenguaje:** Java 17 / Java 21 (Modern Java Features)
* **Framework:** Spring Boot, JPA / Hibernate
* **Build Tool:** Gradle
* **Gestión & QA:** Jira, Scrum Methodology
* **Documentación de API:** Swagger / Postman (Caja negra)

---

## 🛠️ Desafíos Técnicos y Soluciones

### 1. Optimización de Carga Masiva (Batch Processing)
**Problema:** Latencia alta en la carga masiva de ahorros, créditos y depósitos recurrentes.
**Solución:** Rediseño y optimización de **DTOs** y servicios de la API para reducir el overhead de serialización. Implementación de mejoras en la lógica de persistencia para manejar grandes volúmenes de datos financieros de forma eficiente.

### 2. Resolución de Incidencias en Ahorros (Accruals)
**Problema:** Errores en el cálculo de devengos (accruals) y post-intereses en cuentas de ahorro.
**Solución:** Debugging profundo y ajuste de la lógica de negocio utilizando **JPA/Hibernate**, asegurando la integridad de los datos financieros según las reglas de negocio del sistema.

### 3. Documentación y Calidad (QA)
* Ejecución de **pruebas de caja negra** para asegurar la estabilidad de los nuevos endpoints.
* Documentación técnica detallada en **Swagger** para facilitar el consumo de la API por otros módulos.
* Gestión del ciclo de vida del software mediante el flujo de trabajo de **Jira**.

---

## 🏗️ Arquitectura
El proyecto sigue una arquitectura de microservicios robusta, diseñada para ser escalable y modular, facilitando la integración de nuevos productos financieros.

---

## 💻 Cómo ejecutar el proyecto (Local)

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/danielales2541/nombre-del-repo.git](https://github.com/danielales2541/nombre-del-repo.git)
