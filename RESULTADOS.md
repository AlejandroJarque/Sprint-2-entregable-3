# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 22 correctas de 24 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.33 ms
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

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.27 ms
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

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,100 @@
 codigo | nombre | codigo fabricante | nombre fabricante
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Asus
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Asus
+9.00 | Portátil Ideapd 320 | 2.00 | Asus
+8.00 | Portátil Yoga 520 | 2.00 | Asus
+7.00 | Monitor 27 LED Full HD | 1.00 | Asus
+6.00 | Monitor 24 LED Full HD | 1.00 | Asus
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Asus
+4.00 | GeForce GTX 1050Ti | 7.00 | Asus
+3.00 | Disco SSD 1 TB | 4.00 | Asus
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Asus
+1.00 | Disco duro SATA3 1TB | 5.00 | Asus
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Lenovo
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Lenovo
+9.00 | Portátil Ideapd 320 | 2.00 | Lenovo
+8.00 | Portátil Yoga 520 | 2.00 | Lenovo
+7.00 | Monitor 27 LED Full HD | 1.00 | Lenovo
+6.00 | Monitor 24 LED Full HD | 1.00 | Lenovo
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Lenovo
+4.00 | GeForce GTX 1050Ti | 7.00 | Lenovo
+3.00 | Disco SSD 1 TB | 4.00 | Lenovo
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Lenovo
+1.00 | Disco duro SATA3 1TB | 5.00 | Lenovo
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
+9.00 | Portátil Ideapd 320 | 2.00 | Hewlett-Packard
+8.00 | Portátil Yoga 520 | 2.00 | Hewlett-Packard
+7.00 | Monitor 27 LED Full HD | 1.00 | Hewlett-Packard
+6.00 | Monitor 24 LED Full HD | 1.00 | Hewlett-Packard
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Hewlett-Packard
+4.00 | GeForce GTX 1050Ti | 7.00 | Hewlett-Packard
+3.00 | Disco SSD 1 TB | 4.00 | Hewlett-Packard
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Hewlett-Packard
+1.00 | Disco duro SATA3 1TB | 5.00 | Hewlett-Packard
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Samsung
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Samsung
+9.00 | Portátil Ideapd 320 | 2.00 | Samsung
+8.00 | Portátil Yoga 520 | 2.00 | Samsung
+7.00 | Monitor 27 LED Full HD | 1.00 | Samsung
+6.00 | Monitor 24 LED Full HD | 1.00 | Samsung
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Samsung
+4.00 | GeForce GTX 1050Ti | 7.00 | Samsung
+3.00 | Disco SSD 1 TB | 4.00 | Samsung
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Samsung
+1.00 | Disco duro SATA3 1TB | 5.00 | Samsung
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Seagate
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Seagate
+9.00 | Portátil Ideapd 320 | 2.00 | Seagate
+8.00 | Portátil Yoga 520 | 2.00 | Seagate
+7.00 | Monitor 27 LED Full HD | 1.00 | Seagate
+6.00 | Monitor 24 LED Full HD | 1.00 | Seagate
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Seagate
+4.00 | GeForce GTX 1050Ti | 7.00 | Seagate
+3.00 | Disco SSD 1 TB | 4.00 | Seagate
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Seagate
 1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Crucial
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Crucial
+9.00 | Portátil Ideapd 320 | 2.00 | Crucial
+8.00 | Portátil Yoga 520 | 2.00 | Crucial
+7.00 | Monitor 27 LED Full HD | 1.00 | Crucial
+6.00 | Monitor 24 LED Full HD | 1.00 | Crucial
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
+4.00 | GeForce GTX 1050Ti | 7.00 | Crucial
+3.00 | Disco SSD 1 TB | 4.00 | Crucial
 2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
-3.00 | Disco SSD 1 TB | 4.00 | Samsung
+1.00 | Disco duro SATA3 1TB | 5.00 | Crucial
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Gigabyte
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Gigabyte
+9.00 | Portátil Ideapd 320 | 2.00 | Gigabyte
+8.00 | Portátil Yoga 520 | 2.00 | Gigabyte
+7.00 | Monitor 27 LED Full HD | 1.00 | Gigabyte
+6.00 | Monitor 24 LED Full HD | 1.00 | Gigabyte
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Gigabyte
 4.00 | GeForce GTX 1050Ti | 7.00 | Gigabyte
-5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
-6.00 | Monitor 24 LED Full HD | 1.00 | Asus
-7.00 | Monitor 27 LED Full HD | 1.00 | Asus
-8.00 | Portátil Yoga 520 | 2.00 | Lenovo
-9.00 | Portátil Ideapd 320 | 2.00 | Lenovo
-10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
-11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
+3.00 | Disco SSD 1 TB | 4.00 | Gigabyte
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Gigabyte
+1.00 | Disco duro SATA3 1TB | 5.00 | Gigabyte
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Huawei
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Huawei
+9.00 | Portátil Ideapd 320 | 2.00 | Huawei
+8.00 | Portátil Yoga 520 | 2.00 | Huawei
+7.00 | Monitor 27 LED Full HD | 1.00 | Huawei
+6.00 | Monitor 24 LED Full HD | 1.00 | Huawei
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Huawei
+4.00 | GeForce GTX 1050Ti | 7.00 | Huawei
+3.00 | Disco SSD 1 TB | 4.00 | Huawei
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Huawei
+1.00 | Disco duro SATA3 1TB | 5.00 | Huawei
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Xiaomi
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Xiaomi
+9.00 | Portátil Ideapd 320 | 2.00 | Xiaomi
+8.00 | Portátil Yoga 520 | 2.00 | Xiaomi
+7.00 | Monitor 27 LED Full HD | 1.00 | Xiaomi
+6.00 | Monitor 24 LED Full HD | 1.00 | Xiaomi
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Xiaomi
+4.00 | GeForce GTX 1050Ti | 7.00 | Xiaomi
+3.00 | Disco SSD 1 TB | 4.00 | Xiaomi
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Xiaomi
+1.00 | Disco duro SATA3 1TB | 5.00 | Xiaomi
```

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
🚨 `JOIN` sin índice. Revisar claves foráneas e índices.

---

## ❌ Query 24: Error
- **Descripción**: 'NoneType' object is not iterable

