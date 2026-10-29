# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 1 correctas de 3 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | apellido1 | apellido2
-Pedro | Heller | Pagac
-Ismael | Strosin | Turcotte
+apellido1 | apellido2 | nombre
+Heller | Pagac | Pedro
+Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 3: Error
- **Descripción**: 'NoneType' object is not iterable

