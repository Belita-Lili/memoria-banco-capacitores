# memoria-banco-capacitores
# Calculadora de Banco de Capacitores

Este es un proyecto de una calculadora en línea que permite determinar la capacitancia necesaria para compensar el factor de potencia en un sistema eléctrico. La herramienta es útil para ingenieros, técnicos y estudiantes que trabajan con circuitos eléctricos y necesitan calcular bancos de capacitores.
<img width="1585" height="757" alt="image" src="https://github.com/user-attachments/assets/b24af395-2220-40bb-9b77-39b8b8380323" />

---

## Características

- **Cálculo de kVAR necesarios:** Determina la potencia reactiva necesaria para mejorar el factor de potencia.
- **Cálculo de capacitancia:** Calcula la capacitancia en microfaradios (µF) requerida para la compensación.
- **Interfaz sencilla:** Diseño intuitivo y fácil de usar.
- **Validación de entradas:** Asegura que los valores ingresados sean válidos y estén dentro de rangos razonables.
- **Responsivo:** Funciona en dispositivos móviles y de escritorio.

---

## Cómo usar

1. **Ingresa los valores requeridos:**
   - **Potencia (kW):** La potencia activa del sistema.
   - **Factor de potencia actual:** El factor de potencia actual del sistema (valor entre 0 y 1).
   - **Factor de potencia deseado:** El factor de potencia que deseas alcanzar (valor entre 0 y 1).
   - **Voltaje (V):** El voltaje del sistema.

2. **Haz clic en "Calcular":**
   - La calculadora determinará la potencia reactiva (kVAR) necesaria y la capacitancia (µF) requerida.

3. **Resultados:**
   - Los resultados se mostrarán en la sección inferior.

4. **Reiniciar:**
   - Si deseas realizar otro cálculo, haz clic en "Reset" para limpiar los campos.

---

## Fórmulas utilizadas

### Cálculo de kVAR necesarios:
kVAR = P x (tan(cos^{-1}(FP_actual)) - tan(cos^{-1}(FP_deseado)))
Donde:
- P  = Potencia activa (kW).
- FP_actual = Factor de potencia actual.
- FP_deseado = Factor de potencia deseado.

### Cálculo de capacitancia:
C = (kVAR x 10^6)/(2 pi f V^2)
Donde:
- C = Capacitancia (µF).
- f = Frecuencia (60 Hz).
- V = Voltaje (V).

---

## Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari, etc.).
- Conexión a Internet (si se accede en línea).

---

## Instalación

Este proyecto no requiere instalación. Simplemente abre el archivo `index.html` en tu navegador para usar la calculadora.

Si deseas clonar el repositorio:

```bash
git clone https://github.com/tuusuario/calculadora-capacitores.git
cd calculadora-capacitores
```

---

## Contribuir

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu feature o corrección: `git checkout -b nombre-de-tu-feature`.
3. Realiza tus cambios y haz commit: `git commit -m 'Añade nueva funcionalidad'`.
4. Sube tus cambios: `git push origin nombre-de-tu-feature`.
5. Abre un Pull Request.

---

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE). Siéntete libre de usarlo, modificarlo y distribuirlo.

---


## Enlaces útiles

- [Documentación sobre factor de potencia](https://es.wikipedia.org/wiki/Factor_de_potencia)
---
