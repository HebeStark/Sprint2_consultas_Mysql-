# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 25 correctas de 32 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
 nombre | precio_eur | precio_usd
-Disco duro SATA3 1TB | 86.99 | 86.99
-Memoria RAM DDR4 8GB | 120.00 | 120.00
-Disco SSD 1 TB | 150.99 | 150.99
-GeForce GTX 1050Ti | 185.00 | 185.00
-GeForce GTX 1080 Xtreme | 755.00 | 755.00
-Monitor 24 LED Full HD | 202.00 | 202.00
-Monitor 27 LED Full HD | 245.99 | 245.99
-Portátil Yoga 520 | 559.00 | 559.00
-Portátil Ideapd 320 | 444.00 | 444.00
-Impresora HP Deskjet 3720 | 59.99 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00 | 180.00
+Disco duro SATA3 1TB | 86.99 | precio_usd
+Memoria RAM DDR4 8GB | 120.00 | precio_usd
+Disco SSD 1 TB | 150.99 | precio_usd
+GeForce GTX 1050Ti | 185.00 | precio_usd
+GeForce GTX 1080 Xtreme | 755.00 | precio_usd
+Monitor 24 LED Full HD | 202.00 | precio_usd
+Monitor 27 LED Full HD | 245.99 | precio_usd
+Portátil Yoga 520 | 559.00 | precio_usd
+Portátil Ideapd 320 | 444.00 | precio_usd
+Impresora HP Deskjet 3720 | 59.99 | precio_usd
+Impresora HP Laserjet Pro M26nw | 180.00 | precio_usd
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nom del producte | euros | dòlars
+nombre del producto | euros | dolares
 Disco duro SATA3 1TB | 86.99 | 95.69
 Memoria RAM DDR4 8GB | 120.00 | 132.00
 Disco SSD 1 TB | 150.99 | 166.09
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.30 ms
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

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio truncado
+nombre | precio
 Disco duro SATA3 1TB | 86.00
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 150.00
```

⏱ Tiempo: 0.39 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.31 ms
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

## ✅ Query 18: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
 nombre | precio | nombre del fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate
+Disco SSD 1 TB | 150.99 | Samsung
+GeForce GTX 1050Ti | 185.00 | Gigabyte
+GeForce GTX 1080 Xtreme | 755.00 | Crucial
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Memoria RAM DDR4 8GB | 120.00 | Crucial
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
-Memoria RAM DDR4 8GB | 120.00 | Crucial
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Portátil Ideapd 320 | 444.00 | Lenovo
 Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Disco SSD 1 TB | 150.99 | Samsung
-Disco duro SATA3 1TB | 86.99 | Seagate
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo | nombre | codigo fabricante | nombre fabricante
-1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
-2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
-3.00 | Disco SSD 1 TB | 4.00 | Samsung
-4.00 | GeForce GTX 1050Ti | 7.00 | Gigabyte
-5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
-6.00 | Monitor 24 LED Full HD | 1.00 | Asus
-7.00 | Monitor 27 LED Full HD | 1.00 | Asus
-8.00 | Portátil Yoga 520 | 2.00 | Lenovo
-9.00 | Portátil Ideapd 320 | 2.00 | Lenovo
-10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
-11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
+nombre | precio | codigo fabricante | nombre fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate | Seagate
+Memoria RAM DDR4 8GB | 120.00 | Crucial | Crucial
+Disco SSD 1 TB | 150.99 | Samsung | Samsung
+GeForce GTX 1050Ti | 185.00 | Gigabyte | Gigabyte
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | Crucial
+Monitor 24 LED Full HD | 202.00 | Asus | Asus
+Monitor 27 LED Full HD | 245.99 | Asus | Asus
+Portátil Yoga 520 | 559.00 | Lenovo | Lenovo
+Portátil Ideapd 320 | 444.00 | Lenovo | Lenovo
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | Hewlett-Packard
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | Hewlett-Packard
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricant
+nombre | precio | fabricante
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 27: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 28: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 29: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ✅ Query 30: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 31: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 32: Error
- **Descripción**: 'NoneType' object is not iterable

