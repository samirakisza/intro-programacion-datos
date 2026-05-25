# 📊 Introducción a la Programación Orientada a Datos
### Tecnicatura Universitaria en Análisis de Datos e Inteligencia Artificial con Orientación en Ciencias Sociales
**Docentes:** Dra. Vanesa Meinardi · Dr. Valentín Basel · Lic. Ana Lucía Sola  
**Unidad 7 · Clase 8**

---

## ¿Qué es este repositorio?

Este repositorio es el espacio de trabajo colaborativo de la clase.
Acá vas a encontrar el notebook de práctica, las consignas y los aportes de todos tus compañeros.

Cada alumno va a tener su **propia copia** de este repositorio (llamada **fork**) donde va a trabajar.
Al final de la clase, vamos a poder ver en el repositorio original todos los cambios que hizo cada uno.

---

## 🧭 Flujo de trabajo de la clase

```
Repositorio del docente (este)
        │
        │  fork → copiás el repo a tu cuenta
        ▼
Tu fork en GitHub (tu-usuario/intro-programacion-datos)
        │
        │  clone → descargás el repo a tu computadora
        ▼
Tu computadora (o Colab)
        │
        │  add + commit + push → subís tus cambios a tu fork
        ▼
Tu fork actualizado en GitHub
```

### ¿Cuál es la diferencia entre fork y clonar?

| | Fork | Clonar |
|---|---|---|
| **¿Qué hace?** | Copia el repo en tu cuenta de GitHub | Descarga el repo a tu computadora |
| **¿Dónde queda?** | En la nube, en tu cuenta | En tu máquina local (o Colab) |
| **¿Para qué sirve?** | Para tener tu propia versión del proyecto | Para trabajar con los archivos localmente |
| **¿Es necesario?** | Sí, primero siempre se hace fork | Después del fork, se clona el fork |

> 💡 **Regla práctica:** primero fork (en GitHub), después clone (en tu compu o Colab).  
> Siempre clonás TU fork, no el repositorio original.

---

## 🔄 ¿Qué es un commit?

Un commit es una **foto del estado de tu proyecto** en un momento determinado.
Cada vez que hacés un commit estás diciendo: *"quiero guardar cómo está el proyecto ahora mismo"*.

Cada commit tiene:
- Un **mensaje** que describís vos: `"Agrego mis datos al análisis"`
- La **fecha y hora** en que lo hiciste
- Tu **nombre** como autor
- Un **código único** que lo identifica para siempre

El historial de commits es como un diario del proyecto: podés ver exactamente qué cambió, cuándo y quién lo hizo.

---

## 🍴 ¿Qué es un fork y para qué usamos uno acá?

Cuando hacés fork de este repositorio, GitHub crea una copia exacta en tu cuenta.
A partir de ese momento, tu fork y el repositorio original son independientes:
- Lo que cambiás en tu fork **no afecta** el repo del docente
- Lo que el docente agrega al repo original **no llega automáticamente** a tu fork (hay que hacer `git pull` para traerlo)

**¿Por qué usamos fork y no simplemente descargamos el archivo?**  
Porque el fork mantiene la conexión con el original. Eso permite:
- Ver todos los forks de la clase desde el repo del docente
- Comparar el trabajo de cada uno
- En proyectos reales: proponer cambios al proyecto original con un *Pull Request*

---

## 🚀 Cómo empezar — paso a paso

### Paso 1 — Hacé fork de este repositorio
1. Hacé clic en el botón **Fork** (arriba a la derecha de esta página)
2. Confirmá — el repo aparece copiado en tu cuenta como `tu-usuario/intro-programacion-datos`

### Paso 2 — Abrí el notebook en Colab
1. En **tu fork**, hacé clic sobre el archivo `analisis_social.ipynb`
2. Arriba del notebook aparece el botón **"Open in Colab"** — hacé clic ahí
3. El notebook se abre en Google Colab listo para ejecutar

### Paso 3 — Completá la consigna
Leé las instrucciones dentro del notebook y completá las celdas marcadas con 🏋️.

### Paso 4 — Guardá los cambios en tu fork
Cuando termines, desde Colab:
1. `Archivo` → `Guardar una copia en GitHub`
2. Seleccioná **tu fork** como destino
3. Escribí un mensaje de commit: `"Completo análisis — [tu nombre]"`
4. Confirmá

### Paso 5 — Verificá en GitHub
Entrá a tu fork en GitHub y confirmá que el archivo se actualizó.
Fijate en la pestaña **Commits** — tu cambio tiene que aparecer ahí.

---

## 📁 Estructura del repositorio

```
intro-programacion-datos/
│
├── README.md                  ← este archivo
├── analisis_social.ipynb      ← el notebook de práctica
└── aportes/                   ← acá van a ir los aportes de cada alumno
    └── LEEME.md
```

---

## 👀 Ver el trabajo de todos

Una vez que cada alumno haya hecho su fork y subido sus cambios, el docente puede ver todos los forks desde:  
`github.com/usuario-docente/intro-programacion-datos/network/members`

Desde ahí se puede acceder al fork de cada alumno y ver qué cambios hizo.
