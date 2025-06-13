# Plataforma Avanzada para Generación Automática de Diagramas UML  
**Tech Solutions**  
*Patrones de Software - Mag. Patrick Cuadros*  

---

## Integrantes  
- Alexis Martínez Vargas (2019063638)  
- Juan Pérez Vizcarra (2019063636)  
- Jhon Ticona Chambi (2018062232)  

---

## 1. Introducción  
### Propósito  
Desarrollar una plataforma robusta basada en **Clean Architecture** que permita:  
- Generación y gestión de diagramas UML desde múltiples fuentes
- Colaboración en tiempo real entre equipos de desarrollo
- Mantenimiento de versiones e historial de cambios
- Implementación de principios SOLID y patrones de diseño

### Alcance  
- **Incluye**:  
  - Backend con Clean Architecture (dominio, aplicación, infraestructura)
  - Frontend en React con arquitectura modular
  - Sistema de autenticación y gestión de permisos
  - API RESTful para integración con herramientas externas
- **Excluye**: 
  - Herramientas de modelado 3D
  - Generación de código a partir de diagramas
  - Integración con sistemas de control de versiones externos

---

## 2. Arquitectura del Sistema  

### Arquitectura del Proyecto

![Clean Architecture](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*0R0r00uF1RyRFxkxo3HVDg.png)
*Figura: Arquitectura Clean implementada en el proyecto*

### Vista de Casos de Uso  
**Diagramas clave**:  
- Generación de UML desde código  
- Colaboración en tiempo real  

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.005.png)  
*Figura: Módulo de Gestión de Diagramas UML*  

---

### Vista de Caso de uso

Diagrama de Caso de Uso del Módulo Iniciar Sesión incluyendo la acción de validar Usuario*

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.002.png)

---

Diagrama de Caso de Uso del Modulo Gestionar Usuario

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.003.png)

---

Diagrama de Caso de Uso del Módulo Gestionar Colaboración

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.004.png)

---

Diagrama de Caso de Uso del Módulo Gestionar Diagramas UML

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.005.png)

---


## Vista Lógica

### Diagrama de Subsistemas (paquetes)


![](documentos/media/fd04/diagrama%20subsistema.png)

---

### Diagrama de Secuencia 
#### Diagrama de secuencia de colaboración 

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.007.png)

---

#### Diagrama de secuencia de generación  de UML

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.008.png)

---

#### Diagrama de secuencia de autenticación 

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.009.png)

---

#### Diagrama de secuencia de versiona miento 

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.010.png)

---

#### Diagrama de secuencia de Comentarios

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.011.png)

---


### Diagrama de Clases

![](documentos/media/fd04/diagrama%20de%20clases.png)

---

### Diagrama de Base de datos

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.014.png)

---

### Diagrama de arquitectura software

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.015.png)

---

### Diagrama de arquitectura del sistema

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.016.png)

---

### Diagrama de despliegue

![](documentos/media/Aspose.Words.ea08ac6b-91ce-4764-8b65-5ae6d44cb683.022.png)
