# 🎮 Sistema de Recomendación Steam (Deep Learning)
Este proyecto implementa un motor de recomendación basado en Redes Neuronales para predecir qué juegos le gustarán a un usuario en función de sus horas de vuelo en Steam.

## 🧠 Metodología: Filtrado Colaborativo Neuronal
En lugar de usar reglas simples, usamos **Embeddings**. El modelo asigna un vector matemático a cada usuario y a cada juego. Si los vectores apuntan en direcciones similares, el sistema recomienda ese juego.

## 🛠️ Instalación y Uso
1. **Entorno:** Desarrollado en Python 3.13.
2. **Instalación:** `pip install -r requirements.txt --break-system-packages`
3. **Ejecución:** Abrir `recomendacion.ipynb` y ejecutar todas las celdas.

## 📈 Resultados del Modelo
El sistema fue entrenado con 200,000 interacciones. Logramos una reducción constante del error (MSE), lo que significa que las recomendaciones son estadísticamente confiables.