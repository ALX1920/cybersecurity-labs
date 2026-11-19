# DVWA – SQL Injection Lab

Laboratorio educativo realizado con **DVWA (Damn Vulnerable Web Application)** para estudiar la vulnerabilidad **SQL Injection** dentro de un entorno controlado.  
Este proyecto forma parte de mi aprendizaje en ciberseguridad y pruebas de penetración.

---

## Objetivo del proyecto

- Comprender cómo funciona una inyección SQL en una aplicación vulnerable.
- Analizar el impacto de entradas no validadas.
- Documentar el entorno, el proceso y los resultados.
- Practicar documentación técnica estilo pentest.
- Separar correctamente el entorno víctima (DVWA) del entorno atacante (Kali Linux).

---

## Entorno del laboratorio

### **Máquina víctima (DVWA)**

- Ubuntu Server
- Apache2
- PHP
- MariaDB
- DVWA instalado manualmente
- Red interna NAT / Host-Only

### **Máquina atacante (Kali Linux)**

- Kali Linux
- Herramientas de análisis (Nmap, Burp Suite, etc.)
- Navegador web para interactuar con DVWA

---

## Estructura del laboratorio

> Estructura prevista; las carpetas se irán creando conforme se agregue la evidencia.

```
dvwa-sql-injection/
│
├── README.md
│
├── documentacion/
│   ├── reporte.md
│   ├── entorno.md
│   └── notas.md
│
├── capturas/
│   ├── sql_injection_1.png
│   ├── sql_injection_2.png
│   └── niveles_seguridad.png
│
└── analisis/
    ├── vulnerabilidad_sql.md
    └── mitigaciones.md
```

---

## Actividades realizadas

- Instalación y configuración de DVWA.
- Inicialización de la base de datos desde la interfaz web.
- Ajuste del nivel de seguridad a **Low** para fines educativos.
- Análisis del módulo **SQL Injection**.
- Observación del comportamiento de la aplicación ante entradas manipuladas.
- Documentación del impacto y del flujo de datos expuestos.

---

## Lecciones aprendidas

- Importancia de validar entradas del usuario.
- Riesgos de construir consultas SQL inseguras.
- Diferencias entre niveles de seguridad en DVWA.
- Cómo documentar un laboratorio de forma profesional.

---

## Nota ética

Este laboratorio se realizó **exclusivamente con fines educativos** en un entorno controlado.  
Nunca debe aplicarse este conocimiento en sistemas reales sin autorización explícita.
