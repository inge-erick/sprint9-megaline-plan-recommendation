# Sprint 9 - Megaline Plan Recommendation

## 📌 Descripción
Proyecto de clasificación en el que se desarrolla un modelo para predecir cuál de los nuevos planes de la compañía Megaline (Smart o Ultra) debe recomendarse a un cliente.  
El objetivo es alcanzar una exactitud mínima del **75%**, probando distintos modelos y optimizando hiperparámetros.

---

## 📂 Dataset
Archivo: `users_behavior.csv`  

Cada fila representa el comportamiento mensual de un cliente, con las siguientes variables:  
- `calls`: número de llamadas  
- `minutes`: duración total de las llamadas en minutos  
- `messages`: número de SMS enviados  
- `mb_used`: tráfico de internet en MB  
- `is_ultra`: plan contratado (1 = Ultra, 0 = Smart)  

---

## 🛠️ Tecnologías usadas
- Python  
- Pandas / NumPy  
- Scikit-learn (DecisionTree, RandomForest, LogisticRegression)  
- Matplotlib  

---

## 🚀 Metodología
1. Exploración inicial de los datos.  
2. División del dataset en **entrenamiento, validación y prueba**.  
3. Entrenamiento de distintos modelos:  
   - Árbol de decisión  
   - Bosque aleatorio  
   - Regresión logística  
4. Ajuste de hiperparámetros y comparación de resultados.  
5. Evaluación final con el conjunto de prueba.  
6. Prueba de cordura para validar el modelo.  

---

## 📊 Resultados
- Mejor modelo: **Random Forest Classifier**  
- Exactitud en conjunto de prueba: **0.XX** (ajustar con tu valor real)  
- El modelo supera el umbral de calidad de **0.75**.  

---

## ▶️ Cómo ejecutar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/inge-erick/sprint9-megaline-plan-recommendation.git
