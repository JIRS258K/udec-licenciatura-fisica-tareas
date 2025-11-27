# Certamen 1 — Mecánica Clásica II

Certamen 1 del curso **Mecánica Clásica II** (UdeC).  
Incluye dos problemas: uno sobre bases coordenadas en un sistema general en ℝ³ y otro sobre una cadena de
péndulos acoplados y su límite continuo.

---

# Problema 1 — Bases coordenadas y parámetro de arco

En este problema se trabaja con un sistema de coordenadas generalizadas en ℝ³ y sus vectores base
$\vec e_i = \partial \vec x / \partial x^i$.

## Enfoque

- Se interpreta geométricamente cada $x^i$ como una **línea coordenada** y a $\vec e_i$ como su vector tangente.
- Se introduce el elemento de línea $ds^2 = g_{ij}\,dx^i dx^j$ y la métrica $g_{ij} = \vec e_i \cdot \vec e_j$.
- A lo largo de una línea coordenada $x^i$ se muestra que el parámetro natural es la longitud de arco $s_i$,
  y que el vector unitario $\hat e_i$ coincide con $d\vec x/ds_i$.  
  Es decir, los vectores base unitarios están parametrizados por la longitud natural de sus líneas coordenad

---

# Problema 2 — Cadena de péndulos y límite continuo

Aquí se estudia una cadena de péndulos de masa $m$ acoplados por resortes de constante $k$, separados una
distancia $h$ y de longitud $r$.

## Enfoque

- Se escriben las ecuaciones de movimiento discretas para el desplazamiento horizontal $q_i(t)$ en el régimen
  de oscilaciones pequeñas, incluyendo el término restaurador debido a la gravedad.
- Se construye el **Lagrangiano discreto** y luego se toma el límite al continuo, identificando:
  - la densidad lineal de masa $\lambda = m/h$,
  - la tensión efectiva $T = \lim_{h\to 0} kh$.
- En el continuo se obtiene un campo $q(t,x)$ que obedece una ecuación tipo **Klein–Gordon 1+1D**, con velocidad
  de propagación $v_p = \sqrt{T/\lambda}$ y frecuencia propia $\omega_0 = \sqrt{g/r}$.
- Se deriva la densidad lagrangiana $\mathcal{L}(q, q_t, q_x)$ y las ecuaciones de campo mediante el principio de
  mínima acción.

---

## Archivos

- `certamen1.tex` — Desarrollo completo en LaTeX.
- `certamen1.pdf` — Versión compilada del certamen.
- `UdeC_azul_centrado.png` — Logo usado en la portada.
- `p1/` — Imágenes utilizadas en las figuras del Problema 1.
- `p2/` — Imágenes utilizadas en las figuras del Problema 2.
