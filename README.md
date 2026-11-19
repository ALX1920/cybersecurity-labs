# Cybersecurity Labs

Repositorio donde documento mi aprendizaje en **ciberseguridad y pruebas de penetración**: comandos, evidencias, capturas y reportes de cada laboratorio que realizo en entornos controlados.

---

## Laboratorios

| Laboratorio | Tema | Estado |
|---|---|---|
| [DVWA – SQL Injection](dvwa-sql-injection/) | Inyección SQL en DVWA (nivel Low) | En progreso |

---

## Entorno general

- **Máquina atacante:** Kali Linux (Nmap, Burp Suite, navegador web).
- **Máquinas víctima:** según el laboratorio (por ejemplo, Ubuntu Server con DVWA).
- **Red:** interna NAT / Host-Only, aislada de Internet y de otros equipos.

---

## Estructura del repositorio

Cada laboratorio vive en su propia carpeta con la misma organización:

```
cybersecurity-labs/
│
├── README.md              ← este índice
│
└── <nombre-del-lab>/
    ├── README.md          ← objetivo, entorno y resumen del lab
    ├── documentacion/     ← reporte, entorno, notas y comandos usados
    ├── capturas/          ← evidencias en imagen
    └── analisis/          ← análisis de la vulnerabilidad y mitigaciones
```

---

## Nota ética

Todo el contenido de este repositorio se realizó **exclusivamente con fines educativos** en entornos propios y controlados.
Nunca debe aplicarse este conocimiento en sistemas reales sin autorización explícita.
