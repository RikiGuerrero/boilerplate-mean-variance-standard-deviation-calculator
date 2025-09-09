# 📊 Calculadora de Varianza, Desviación Estándar y Media

Este proyecto es una **calculadora de estadísticas** en Python que convierte una lista de 9 números en una matriz 3x3 y calcula:

- Media
- Varianza
- Desviación estándar
- Máximo
- Mínimo
- Suma

Calcula estos valores **por filas, columnas y de forma global**.  
Proyecto desarrollado como parte del currículo de **Python de freeCodeCamp**.

---

## ⚡ Funcionalidades

- ✅ Convierte una lista de 9 números en matriz 3x3.  
- ✅ Calcula estadísticas a lo largo de filas, columnas y matriz completa.  
- ✅ Devuelve resultados en un **diccionario con listas de Python**.  
- ✅ Maneja errores si la lista tiene menos de 9 elementos.  

---

## 🛠 Tecnologías

- Python 3  
- NumPy

---

## 💻 Uso

```python
from mean_var_std import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
print(result)
```

### Salida esperada:

```json
{
  "mean": [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  "variance": [[6.0, 6.0, 6.0], [0.666..., 0.666..., 0.666...], 6.666...],
  "standard deviation": [[2.449..., 2.449..., 2.449...], [0.816..., 0.816..., 0.816...], 2.581...],
  "max": [[6, 7, 8], [2, 5, 8], 8],
  "min": [[0, 1, 2], [0, 3, 6], 0],
  "sum": [[9, 12, 15], [3, 12, 21], 36]
}
```

---

## 🧪 Pruebas Unitarias

Para ejecutar las pruebas:

```bash
python3 -m unittest test_module.py
```

---

## 👨‍💻 Autor

**Ricardo Guerrero**

GitHub: https://github.com/RikiGuerrero

Proyecto realizado como parte del currículo de Python en freeCodeCamp.

---

## 📄 Licencia

Este proyecto es open source y puede usarse libremente.
