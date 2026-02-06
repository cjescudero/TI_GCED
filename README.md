# TI_GCED

Material de apoyo de la asignatura **Teoría de la Información (TI)** del **Grado de Ciencia e Ingeniería de Datos (GCED)** de la **Facultad de Informática (FIC)** de la **Universidade da Coruña (UDC)**.

Recursos visuales en HTML (estáticos e interactivos) sobre **periodicidad espectral** y **aliasing**.

## Contenido

- **`aliasing.html`**: diagrama SVG sobre la **periodicidad espectral en tiempo discreto** y las equivalencias \(F\), \(f = F/F_s\) y \(\omega = 2\pi f\).  
  Abrir: [`aliasing.html`](aliasing.html)

- **`aliasing_animacion.html`**: animación interactiva en `canvas` para visualizar el **aliasing al muestrear**, controlando el cociente \(F_s / F_{max}\).  
  Abrir: [`aliasing_animacion.html`](aliasing_animacion.html)

- **`circunferencia.html`**: diagrama sobre **periodicidad en la circunferencia unidad** para frecuencia normalizada \(f\) (período 1) y frecuencia angular \(\omega\) (período \(2\pi\)).  
  Abrir: [`circunferencia.html`](circunferencia.html)

## Cómo verlo

### Opción A: abrir directamente

Haz doble clic en cualquiera de los HTML y ábrelo en tu navegador.

### Opción B: servidor local (recomendado)

Algunas configuraciones del navegador restringen ciertas cargas locales; si te ocurre, levanta un servidor en la carpeta del repo:

```bash
python3 -m http.server 8000
```

Luego abre en el navegador:

- `http://localhost:8000/aliasing.html`
- `http://localhost:8000/aliasing_animacion.html`
- `http://localhost:8000/circunferencia.html`

## Notas

- No hay dependencias de build: es **HTML + CSS + JS** “a pelo”.
- Se usan tipografías de **Google Fonts** (requiere conexión a Internet para cargarlas).

