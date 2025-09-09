# 📊 Variance, Standard Deviation and Mean Calculator

This project is a **statistics calculator** in Python that converts a list of 9 numbers into a 3x3 matrix and calculates:

- Mean
- Variance
- Standard deviation
- Maximum
- Minimum
- Sum

It calculates these values **by rows, columns and globally**.  
Project developed as part of **freeCodeCamp's Python curriculum**.

---

## ⚡ Features

- ✅ Converts a list of 9 numbers into a 3x3 matrix.  
- ✅ Calculates statistics along rows, columns and entire matrix.  
- ✅ Returns results in a **dictionary with Python lists**.  
- ✅ Handles errors if the list has fewer than 9 elements.  

---

## 🛠 Technologies

- Python 3  
- NumPy

---

## 💻 Usage

```python
from mean_var_std import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
print(result)
```

### Expected output:

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

## 🧪 Unit Tests

To run the tests:

```bash
python3 -m unittest test_module.py
```

---

## 👨‍💻 Author

**Ricardo Guerrero**

GitHub: https://github.com/RikiGuerrero

Project developed as part of freeCodeCamp's Python curriculum.

---

## 📄 License

This project is open source and can be used freely.
