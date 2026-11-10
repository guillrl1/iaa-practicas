# Inteligencia Artificial Avanzada

Este repositorio contiene la implementación de la práctica sobre **Inferencia Condicional en distribuciones discretas binarias**. El objetivo principal es el procesamiento de tablas de probabilidad para realizar selección de variables, marginalización y cálculo de probabilidades condicionales.

---

## 🎓 Información Académica
* **Institución:** Universidad de La Laguna (ULL)
* **Grado:** Ingeniería Informática
* **Asignatura:** Inteligencia Artificial Avanzada (IAA)

## 👥 Autores
| Nombre | Correo Electrónico |
| :--- | :--- |
| **Guillermo López Concepción** | [alu0101620459@ull.edu.es](mailto:alu0101620459@ull.edu.es) |
| **Marco Aguiar Álvarez** | [alu0101620961@ull.edu.es](mailto:alu0101620961@ull.edu.es) |

---

## 📂 Proyecto: Inferencia Condicional
El programa permite trabajar con distribuciones de probabilidad multivariables representadas mediante máscaras binarias.

### Funcionalidades implementadas:
1.  **Carga de datos:** Lectura de archivos CSV con formato `máscara,probabilidad`.
2.  **Normalización:** Asegura que la suma de todas las probabilidades sea $1.0$.
3.  **Selección de Variables:**
    * **Variables Condicionadas ($X_C$):** Fijación de valores observados (evidencia).
    * **Variables de Interés ($X_I$):** Definición de las variables sobre las que se desea calcular la distribución.
    * **Marginalización:** Eliminación automática de las variables no seleccionadas.

### Ejecución

```bash
g++ -o inferencia main.cc
./bin/inferencia #para ejecutar el programa
```

tambien puede usar el comando `make` para compilar:

```bash
make
./bin/inferencia
```

Si quiere ejecutar con variables aleatorias, ejecute el programa e indique el numero de variables N que desea
```bash
./bin/inferencia 4 # Por defecto el programa usara un N = 3 si no detecta ni numero de variables ni archivo
```


## Contenido

- [`P01`](./P01)
- [`proyecto-pln`](./proyecto-pln)
