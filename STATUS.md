# STATUS.md  
Status Classification and Operational State  
HormigasAIS Ecosystem

Status: Normative Classification Document  
Scope: Repositories, Forks, Nodes, Implementations, UX Layers  
Effective Date: 2026  
Governing Reference: GOVERNANCE.md  

---

## 1. Propósito y Naturaleza del Documento

Este documento define el **sistema oficial de estados operativos** del ecosistema HormigasAIS.

Su propósito es establecer una **clasificación clara, verificable y no ambigua** del estado técnico, experimental y operativo de repositorios, forks, nodos, capas UX e implementaciones asociadas al ecosistema.

Este documento es **normativo**, no descriptivo.  
Complementa y se encuentra **subordinado jerárquicamente** a `GOVERNANCE.md`.

---

## 2. Principio Fundamental

El **estado (STATUS)** de un repositorio o componente:

- **No confiere autoridad**
- **No implica gobernanza**
- **No presume legitimidad institucional**
- **No sustituye el modelo de gobernanza**

El estado **describe condición operativa**, no jerarquía de poder.

---

## 3. Clasificación Oficial de Estados

### 3.1 🧪 Experimental

**Definición:**

Un componente clasificado como *Experimental* se encuentra en fase de exploración, prueba, investigación o validación conceptual.

**Características:**

- Código o diseño inestable o incompleto
- Cambios frecuentes y no garantizados
- Puede romper compatibilidad sin previo aviso
- No apto para uso productivo crítico
- Puede ser abandonado, archivado o redefinido

**Implicaciones:**

- No representa al ecosistema HormigasAIS
- No constituye un nodo
- No genera compromisos de soporte
- No tiene garantías de continuidad

---

### 3.2 🌐 Edge (Borde Operativo)

**Definición:**

Un componente *Edge* opera en el **borde del ecosistema**, generalmente cercano a la fuente de interacción, datos o experiencia humana.

Puede incluir:

- Edge Computing
- UX distribuido
- Nodos experimentales con identidad funcional
- Implementaciones locales, móviles o soberanas

**Características:**

- Alta autonomía operativa
- Diseño orientado a resiliencia y contexto local
- Puede combinarse con infraestructura central o nube
- Alta carga creativa y técnica

**Implicaciones:**

- Edge **no equivale a autoridad**
- Edge **no equivale a nodo oficial**
- Edge **no implica alineación automática**
- Requiere validación explícita para escalar de estado

---

### 3.3 🏛️ Stable (Estable)

**Definición:**

Un componente *Stable* ha alcanzado un nivel de madurez técnica, documental y operativa suficiente para uso sostenido.

**Características:**

- Interfaces definidas
- Compatibilidad documentada
- Cambios controlados
- Uso recomendado según alcance definido

**Implicaciones:**

- *Stable* **no implica gobernanza**
- *Stable* **no otorga representación**
- La autoridad sigue residiendo exclusivamente en `GOVERNANCE.md`

---

## 4. Relación entre STATUS, Forks y Repositorios

Para evitar interpretaciones erróneas:

- Un **fork puede ser Experimental, Edge o Stable**
- Un **fork nunca hereda autoridad**
- Un **fork nunca se convierte en repositorio normativo**
- El estado no altera su naturaleza derivada

Todo fork está **sujeto al mismo marco de gobernanza**.

---

## 5. Declaración de Estado por Repositorio

Cada repositorio del ecosistema **DEBE** declarar explícitamente su estado mediante:

- Archivo `STATUS.md`, o
- Sección visible en `README.md`

Ejemplo:

> **Estado:** Experimental / Edge / Stable  
> **Clasificación conforme a:** STATUS.md del ecosistema HormigasAIS

La ausencia de declaración **no implica estabilidad ni legitimidad**.

---

## 6. Cambios de Estado

Los cambios de estado:

- **No son automáticos**
- **No se infieren por actividad**
- **No se basan en popularidad o forks**

Requieren:

- Revisión técnica
- Alineación documental
- Validación conforme a `GOVERNANCE.md`

---

## 7. Prelación Normativa

En caso de conflicto:

1. `GOVERNANCE.md` prevalece
2. `STATUS.md` define condición operativa
3. `README.md` es informativo

---

## 8. Declaración Final

HormigasAIS reconoce el valor de:

- La experimentación
- El borde
- La estabilidad

Pero rechaza la ambigüedad.

El estado aclara.  
La gobernanza delimita.  
La colonia permanece.

---

## 9. English Version — Mirror Clause

This document defines the **official operational status classification system** of the HormigasAIS ecosystem.

Status describes **operational condition**, not authority.

Experimental explores.  
Edge adapts.  
Stable sustains.

Authority remains governed exclusively by `GOVERNANCE.md`.

---

© 2026 Cristhiam Leonardo Hernández Quiñonez (CLHQ)  
All rights reserved where applicable.
