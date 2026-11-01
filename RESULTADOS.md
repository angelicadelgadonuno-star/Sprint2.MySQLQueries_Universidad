# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 25 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.45 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.58 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, id_profesor,id_grado, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.25 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.21 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY, id_departamento, id_asignatura

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.20 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
 departamento | total
+Educación | 3.00
 Informática | 2.00
 Matemáticas | 2.00
 Economía y Empresa | 2.00
-Educación | 3.00
+Química y Física | 2.00
 Agronomía | 1.00
-Química y Física | 2.00
 Filología | 0.00
 Derecho | 0.00
 Biología y Geología | 0.00
```

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.23 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_grado

---

## ✅ Query 23: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_curso_escolar, PRIMARY

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.20 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY,id_departamento, PRIMARY

---
