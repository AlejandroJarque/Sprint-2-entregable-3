# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 4 correctas de 6 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio_eur | precio_usd
+nom_producte | precio_eur | precio_usd
 Disco duro SATA3 1TB | 86.99 | 86.99
 Memoria RAM DDR4 8GB | 120.00 | 120.00
 Disco SSD 1 TB | 150.99 | 150.99
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Error
- **Descripción**: 'NoneType' object is not iterable

