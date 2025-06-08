# Porcentaje de trabajos entregados
### 📊 Calculadora de Entregas por Ejercicio

¡Hola! 👋 👩‍🏫 Este cuaderno jupyter con python te permite llevar un control sencillo y visual de las entregas de ejercicios de tus alumnos. Solo tienes que indicar el nombre del ejercicio, cuántos alumnos hay y cuántos entregaron cada ejercicio. ¡Ideal para bootcamps, cursos o talleres! 🧠✨   
En este caso lo uso como teacher assistant en un bootcamp de ciencia de datos y machine learning.

##### 🛠 ¿Qué hace?
✅ Muestra el porcentaje de entregas por cada ejercicio
✅ Calcula el promedio general de entregas
✅ Funciona con cualquier número de ejercicios
✅ Súper fácil de actualizar: solo cambia los números

##### 📥 ¿Cómo lo uso?
Abre el notebook .ipynb en tu editor favorito (VSCode, Jupyter, Google Colab etc.)

En la celda donde aparece esta lista, simplemente actualiza tus datos::

```py
# Formato: ("nombre del ejercicio", total_alumnos, entregados)
ejercicios = [
    ("ejercicio_1", 11, 11),
    ("ejercicio_2", 11, 10),
    ("ejercicio_3", 11, 9),
    ("ejercicio Scraping", 11, 10),
    ("ejercicio API", 11, 10),
    ("Probabilidad", 11, 7)
]
```

#####  Ejecuta la siguiente celda y verás algo así:

```py
📊 Porcentaje de entregas por ejercicio:

- Pandas: 100.0% entregado (11 de 11)
- Visualización: 90.9% entregado (10 de 11)
- SQL: 81.8% entregado (9 de 11)
- Scraping: 90.9% entregado (10 de 11)
- API: 90.9% entregado (10 de 11)
- Probabilidad: 63.6% entregado (7 de 11)

📈 Promedio general de entregas: 86.37%
```


#####  Si quieres después... ¡a graficar! 