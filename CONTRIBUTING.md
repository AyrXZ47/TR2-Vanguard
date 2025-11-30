# Protocolo de Contribución - Proyecto TR-2 "Vanguard"

## Doctrina de Ingeniería
Este no es un proyecto escolar. Es una misión de certificación de ingeniería.
1. **Fiabilidad sobre Creatividad:** Si no puedes justificarlo con números, no entra en el diseño.
2. **Documentación Viva:** El código y los planos deben coincidir con el TDR (Technical Design Report).
3. **Cero Ambigüedad:** No asumas dimensiones. Consulta la "Tabla de Especificaciones Maestras".

## Flujo de Trabajo (Git Flow)
* **Rama `main`:** Sagrada. Solo código/diseños probados y funcionales.
* **Ramas de Feature:** Usa el formato `categoria/descripcion`.
    * Ejemplo: `avionica/sensor-presion`, `simulacion/ajuste-aletas`.
* **Commits:** Claros y descriptivos.
    * Mal: "cambios", "arreglo".
    * Bien: "feat: Actualizar geometría de aletas en OpenRocket a perfil trapezoidal".

## Estándares
* **Simulaciones:** Archivos `.ork` deben tener la versión de OpenRocket en el nombre si hay conflicto.
* **Documentación:** LaTeX debe compilar sin errores antes de hacer push.
