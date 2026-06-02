# Guía de Diseño y Estética: HY Ingeniería

Este documento establece las directrices visuales, colores, tipografía y elementos clave de diseño para la landing page de **HY Ingeniería S.A.U.**, basadas fielmente en la identidad y estética de su perfil corporativo.

---

## 🎨 Paleta de Colores

El diseño del PDF utiliza una combinación de tonos industriales y corporativos muy equilibrada, combinando contrastes de azul profundo con detalles metalizados (ocre/cobre) y fondos limpios y cálidos.

| Tipo de Color | Nombre del Color | Código Hexadecimal | Uso en la Web |
| :--- | :--- | :--- | :--- |
| **Principal Oscuro** | Azul Marino / Azul Pizarra | `#0F2027` / `#132237` | Fondos de secciones principales (Hero, Footer), encabezados de alta jerarquía, y contenedores de llamados a la acción (CTA). |
| **Acento Metálico** | Ocre Cobrizo / Bronce | `#B38867` / `#C5A080` | Números destacados de métricas, líneas de división, bordes superiores de tarjetas, y estados *hover*. |
| **Acento Secundario** | Rojo Industrial | `#D9383A` | Detalles en el logo, marcadores de mapas o pequeños elementos de alerta visual. |
| **Fondo Claro** | Crema muy Claro / Blanco Roto | `#FAF8F5` / `#F7F5F2` | Fondo principal para las secciones claras de lectura. Evita el uso de blanco puro (`#FFFFFF`) para generar calidez. |
| **Texto Oscuro** | Gris Carbón / Azul de Texto | `#1A252F` / `#2C3E50` | Color para el cuerpo del texto en secciones claras. |
| **Texto Claro** | Blanco Nieve | `#F8FAFC` | Color para el cuerpo del texto sobre fondo azul oscuro. |

---

## font-family: Tipografía

La tipografía debe balancear la precisión técnica de la ingeniería con el prestigio corporativo:

### 1. Títulos y Encabezados (Sans-Serif Geométrica)
*   **Fuentes Recomendadas**: `Inter`, `Roboto`, o `Outfit` (vía Google Fonts).
*   **Peso**: Negrita / Bold (`600` o `700`).
*   **Estilo**: Letras limpias, ligeramente espaciadas para subtítulos técnicos en mayúsculas (`text-transform: uppercase; letter-spacing: 0.1em;`).

### 2. Cuerpo de Texto (Sans-Serif Legible)
*   **Fuentes Recomendadas**: `Inter` o `Open Sans`.
*   **Peso**: Fino / Regular (`300` o `400`).
*   **Tamaño**: `1rem` (16px) a `1.125rem` (18px) para una lectura fluida en escritorio.

### 3. Declaraciones y Citas (Serif Elegante)
*   **Fuentes Recomendadas**: `Georgia` o `Playfair Display` (en cursiva / italic).
*   **Uso**: Citas clave que sintetizan la propuesta de valor de la empresa.
    *   *Ejemplo*: *"Made & Serviced in NOA Mining Belt."*
    *   *Ejemplo*: *"La calidad FRP no se ve a simple vista. Se demuestra en el proceso, no en el resultado."*

---

## 📐 Layout y Estructura Visual (Estilo UI)

Para emular la maquetación del PDF corporativo, la web debe seguir estas pautas estructurales:

### 1. Líneas Divisorias Finas (Separator Rules)
*   Usa bordes o divisores horizontales muy delgados (1px o 2px) en color **Ocre Cobrizo (`#B38867`)**.
*   Colócalos al inicio de cada sección principal o directamente debajo del identificador numérico de la sección (ej. debajo de `01 - TESIS`).

### 2. Tarjetas con Borde Superior (Card Design)
*   Las tarjetas de servicios y productos deben tener:
    *   Un fondo de color blanco o crema muy suave (`#FFFFFF` o `#FAF8F5`).
    *   Un borde superior grueso (3px o 4px) de color **Ocre Cobrizo (`#B38867`)**.
    *   Un título claro en color **Azul Marino (`#0F2027`)** alineado a la izquierda.
    *   Un texto descriptivo corto con viñetas estilizadas en ocre.

### 3. Bloques de Contraste Oscuro
*   Para destacar elementos muy importantes (como la sección "Qué Nos Diferencia"), crea un bloque contenedor con fondo **Azul Marino Oscuro (`#0F2027`)**.
*   El texto interior debe ser blanco y los datos técnicos destacados deben ir en **Ocre Cobrizo (`#B38867`)**.

### 4. Números Gigantes (Visual Metrics)
*   Las estadísticas clave de la empresa deben presentarse de manera imponente:
    *   Tamaño de fuente grande (ej. `4rem` o `64px`).
    *   Color del número en **Azul Marino** u **Ocre**.
    *   Una pequeña línea divisoria de cobre justo debajo.
    *   La descripción corta en mayúsculas, tamaño pequeño (`0.85rem`) y en tono gris oscuro.

---

## 📸 Lineamiento de Imágenes y Elementos Gráficos
*   **Imágenes Reales**: Priorizar fotos reales del sitio minero, la planta de Campo Quijano, y los tanques gigantes en proceso de izaje o transporte, tal como aparecen en el PDF. Evitar ilustraciones abstractas en 3D o imágenes vectoriales genéricas de "tecnología".
*   **Mapa de Servicio del NOA**: El mapa debe ser minimalista (estilo blueprint o trazado simple) mostrando la ubicación central de la planta (Campo Quijano) y líneas radiales que conecten con los salares (Olaroz-Cauchari, Rincón, Centenario-Ratones, Hombre Muerto) dentro de un radio de servicio etiquetado como `≤ 500 km`.
