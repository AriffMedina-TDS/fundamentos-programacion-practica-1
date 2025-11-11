# 📘 Fundamentos de Programación - Práctica 1

## 👨‍💻 Información del Estudiante

- **Nombre:** Ariff Iazid Medina Gómez
- **Matrícula:** SW2509006
- **Grupo:** C
- **Cuatrimestre:** Primer Cuatrimestre
- **Carrera:** TSU en Desarrollo e Innovación de Software
- **Profesor:** Jorge Javier Pedrozo Romero

---

## 📋 Descripción del Proyecto

En este repo comparto mi solución a la práctica de **Fundamentos de Programación**. Usé JavaScript para crear funciones que resuelven problemas de álgebra básica, como parte del camino para llegar a trabajar con operaciones de matrices más complejas.

## 🎯 Objetivos Alcanzados

- ✅ Dominar variables y tipos de datos en JavaScript
- ✅ Implementar estructuras condicionales
- ✅ Utilizar bucles y funciones
- ✅ Manipular arrays unidimensionales
- ✅ Trabajar con arrays bidimensionales (matrices)
- ✅ Aplicar control de versiones con Git y GitHub

---

## 📊 Progreso de Ejercicios

### Sección 1: Variables y Tipos de Datos (10 pts)
- [x] 1.1 Mi Información (2 pts) ✅
- [x] 1.2 Operaciones Básicas (3 pts) ✅
- [x] 1.3 Área de Rectángulo (2 pts) ✅
- [x] 1.4 Conversión Celsius a Fahrenheit (3 pts) ✅

**Puntos obtenidos: 10/10**

### Sección 2: Condicionales (15 pts)
- [x] 2.1 Par o Impar (3 pts) ✅
- [x] 2.2 Evaluar Nota (4 pts) ✅
- [x] 2.3 Mayor de Tres (4 pts) ✅
- [x] 2.4 Clasificar Edad (4 pts) ✅

**Puntos obtenidos: 15/15**

### Sección 3: Funciones y Bucles (20 pts)
- [x] 3.1 Factorial (5 pts) ✅
- [x] 3.2 Suma Hasta N (4 pts) ✅
- [x] 3.3 Tabla de Multiplicar (5 pts) ✅
- [x] 3.4 Números Pares (6 pts) ✅

**Puntos obtenidos: 20/20**

### Sección 4: Arrays (25 pts)
- [x] 4.1 Suma de Array (4 pts) ✅
- [x] 4.2 Promedio de Array (5 pts) ✅
- [x] 4.3 Encontrar Máximo (6 pts) ✅
- [x] 4.4 Filtrar Mayores (5 pts) ✅
- [x] 4.5 Invertir Array (5 pts) ✅

**Puntos obtenidos: 25/25**

### Sección 5: Arrays Bidimensionales - Matrices (30 pts)
- [x] 5.1 Crear Matriz (6 pts) ✅
- [x] 5.2 Suma de Matriz (6 pts) ✅
- [x] 5.3 Obtener Fila (5 pts) ✅
- [x] 5.4 Obtener Columna (7 pts) ✅
- [x] 5.5 Transponer Matriz (6 pts) ✅

**Puntos obtenidos: 30/30**

---

## 📈 Calificación Final

```
┌────────────────────────────────────────┐
│  REPORTE DE CALIFICACIÓN               │
├────────────────────────────────────────┤
│  Puntos obtenidos: 100/100             │
│  Porcentaje: 100%                      │
│  🎓 Calificación: A - Excelente        │
└────────────────────────────────────────┘
```

[![Tests y Calificación Automática](https://github.com/AriffMedina-TSW/fundamentos-programacion-practica-1/actions/workflows/test.yml/badge.svg)](https://github.com/AriffMedina-TSW/fundamentos-programacion-practica-1/actions/workflows/test.yml)

---

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- Git

### Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/fundamentos-programacion-practica-1.git
cd fundamentos-programacion-practica-1
```

### Instalar dependencias
```bash
npm install
```

### Ejecutar tests
```bash
npm test
```

### Ejecutar tests en modo watch
```bash
npm run test:watch
```

### Ver cobertura de código
```bash
npm run test:coverage
```

---

## 📁 Estructura del Proyecto

```
fundamentos-programacion-practica-1/
│
├── ejercicios.js           # ⭐ Archivo principal con mis soluciones
├── ejercicios.test.js      # Tests automatizados (no modificar)
├── package.json            # Configuración del proyecto
├── README.md               # Este archivo
├── GUIA_ESTUDIANTES.md     # Guía de referencia
├── GUIA_INSTRUCTOR.md      # Guía del profesor
│
└── .github/
    └── workflows/
        └── test.yml        # Configuración de GitHub Actions
```

---

## 💡 Aprendizajes Clave

### Lo que más me costó
- *Ejercicios 5.2 (Lógica)* : Implementar la lógica usando estructuras de control anidadas para recorrer la matriz.
- *Ejercicio 5.1 (Sintaxis)* : Me costó identificar los errores de sintaxis que hubieron en mi código en las primeras pruebas.

### Lo que más me gustó
- **Generación de matrices**: Crear arreglos bidimensionales me hizo abrir la mente a nuevas formas de resolver problemas.
- **Generación de commits en terminal**: No conocía esta manera de enviar los commits directamente desde el propio código.

### Técnicas aplicadas
- Uso de `estructuras anidadas` para recorrer matrices.
- Métodos como `.max` para determinar el máximo valor.
- Creación de mis commits con `git add .`.
- Testeo constante para verificar errores.

---

## 🔧 Ejemplos de Código

### Función Favorita: filtrarMayores
```javascript
function filtrarMayores(numeros, limite) {
  const mayores = [];
  for (let i = 0; i < numeros.length; i++) {
    if (numeros[i] > limite) { // Si el número es mayor al límite se agrega
      mayores.push(numeros[i]);
    }
  }
  return mayores;
}
```

**Por qué me gusta:** Me gustó porque usa tanto ciclos y condicionales para elegir los números mayores al seleccionado.

---

## 📚 Recursos Utilizados

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [JavaScript.info](https://es.javascript.info/)
- [Stack Overflow](https://stackoverflow.com)
- Guía del estudiante incluida en el repositorio

---

## 🎯 Próximos Pasos

Este proyecto me prepara para:
- ⚙️ Optimizar algoritmos matemáticos y de procesamiento numérico
- 🧠 Implementación de algoritmos de encriptación
- 📈 Analizar grandes volúmenes de datos (data science)
- 🌐 Aplicar álgebra lineal en visión por computadora y aprendizaje automático

---

## 📝 Historial de Commits

```bash
# Ver mi historial completo
git log --oneline --graph --decorate
```

**Commits destacados:**
- `Generar array inverso usando for en Ejercicio 4.5`
- `Sumar elementos usando indices en Ejercicio 4.1`
- `Resolución con For en Ejercicio 3.1`
- `Generar matriz transpuesta recorriendo filas y columnas en Ejercicio 5.5`
- `Determinar clasificación de edad con condicionales en Ejercicio 2.4`
- `Usar condicionales para devolver el mayor en Ejercicio 2.3`

---

## 🤝 Agradecimientos

- **Profesor Jorge Javier Pedrozo Romero** por la estructura del curso y la práctica
- **Compañeros del Grupo C** por el apoyo mutuo
- **Tecnológico de Software** por la formación integral

---

## 📧 Contacto

- **Email Institucional:** ariff.medina@tecdesoftware.edu.mx
- **GitHub:** [AriffMedina-TSW](https://github.com/AriffMedina-TSW)

---

## 📄 Licencia

Este proyecto es parte de las actividades académicas del **Tecnológico de Software** y está bajo la licencia MIT.

---

<div align="center">

**⭐ Si te gustó este proyecto, dale una estrella ⭐**

Hecho con 💙 por Ariff Medina - 2025

</div>
