# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 17 correctas de 21 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.23 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT 
	producto.nombre,
    producto.precio
FROM producto
ORDER BY precio DESC' at line 10


## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,12 @@
-nombre | precio
-GeForce GTX 1080 Xtreme | 755.00
+nombre | precio | nombre del fabricante
+Disco duro SATA3 1TB | 86.99 | 5.00
+Memoria RAM DDR4 8GB | 120.00 | 6.00
+Disco SSD 1 TB | 150.99 | 4.00
+GeForce GTX 1050Ti | 185.00 | 7.00
+GeForce GTX 1080 Xtreme | 755.00 | 6.00
+Monitor 24 LED Full HD | 202.00 | 1.00
+Monitor 27 LED Full HD | 245.99 | 1.00
+Portátil Yoga 520 | 559.00 | 2.00
+Portátil Ideapd 320 | 444.00 | 2.00
+Impresora HP Deskjet 3720 | 59.99 | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
```

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,12 @@
-nombre
-Portátil Yoga 520
-Portátil Ideapd 320
+nombre | precio | nombre del fabricante
+Disco duro SATA3 1TB | 86.99 | 5.00
+Disco SSD 1 TB | 150.99 | 4.00
+GeForce GTX 1050Ti | 185.00 | 7.00
+GeForce GTX 1080 Xtreme | 755.00 | 6.00
+Impresora HP Deskjet 3720 | 59.99 | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
+Memoria RAM DDR4 8GB | 120.00 | 6.00
+Monitor 24 LED Full HD | 202.00 | 1.00
+Monitor 27 LED Full HD | 245.99 | 1.00
+Portátil Ideapd 320 | 444.00 | 2.00
+Portátil Yoga 520 | 559.00 | 2.00
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 21: Error
- **Descripción**: 'NoneType' object is not iterable

