# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 15 correctas de 18 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.39 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 11: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo_fabricante
-1.00
+codigo
+6.00
+7.00
+8.00
+9.00
+10.00
+11.00
+3.00
 1.00
 2.00
-2.00
-3.00
-3.00
+5.00
 4.00
-5.00
-6.00
-6.00
-7.00
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 12: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,12 @@
-codigo_fabricante
+codigo
+6.00
+7.00
+8.00
+9.00
+10.00
+11.00
+3.00
 1.00
 2.00
-3.00
+5.00
 4.00
-5.00
-6.00
-7.00
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY,codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 18: Error
- **Descripción**: 'NoneType' object is not iterable

