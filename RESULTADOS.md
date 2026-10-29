# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 2 correctas de 5 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 3: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-id | nombre | apellido1 | apellido2 | fecha_nacimiento
-7.00 | Ismael | Strosin | Turcotte | 1999-05-24
-22.00 | Antonio | Domínguez | Guerrero | 1999-02-11
+id | nombre | apellido1 | apellido2
+7.00 | Ismael | Strosin | Turcotte
+22.00 | Antonio | Domínguez | Guerrero
```

⏱ Tiempo: 0.20 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | apellido1 | apellido2 | nif
-Antonio | Fahey | Considine | 10485008K
-Guillermo | Ruecker | Upton | 85869555K
+nombre | apellido1 | apellido2
+Antonio | Fahey | Considine
+Guillermo | Ruecker | Upton
```

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Error
- **Descripción**: 'NoneType' object is not iterable

