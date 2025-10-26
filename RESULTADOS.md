# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 22 correctas de 24 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.21 ms
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

⏱ Tiempo: 0.22 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.22 ms
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

## ✅ Query 18: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.25 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
 codigo | nombre | codigo fabricante | nombre fabricante
-1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
-2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
-3.00 | Disco SSD 1 TB | 4.00 | Samsung
-4.00 | GeForce GTX 1050Ti | 7.00 | Gigabyte
-5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
 6.00 | Monitor 24 LED Full HD | 1.00 | Asus
 7.00 | Monitor 27 LED Full HD | 1.00 | Asus
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
+4.00 | GeForce GTX 1050Ti | 7.00 | Gigabyte
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
 8.00 | Portátil Yoga 520 | 2.00 | Lenovo
 9.00 | Portátil Ideapd 320 | 2.00 | Lenovo
-10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
-11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
+3.00 | Disco SSD 1 TB | 4.00 | Samsung
+1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 24: Error
- **Descripción**: 'NoneType' object is not iterable

