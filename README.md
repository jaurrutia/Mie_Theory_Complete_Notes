# Notas de la solución de Mie

La solución de Mie, también conoida como teoría, resuelve el problema de absroción de luz por una esfera de tamaño y material arbitrario al ser iluminada por una onda plana. Gustav Mie publica su artículo en 1908 [[1][1]] y en éste resuelve la ecuación de Helmholtz y resuleve los campos elecrtromagnéticos (EMs) esparcidos por la esfera, así como los campos Em dentro de ella.

Como parte de un seminarios dedicado a la solución de Mie, basado en [[2][2]], se crearon diversas notas por los participantes del seminario, en donde se comenta y da detalle del procedimiento matemático necesario. La propósito de este repositorio es el compilar las notas de cada participante y generar una referencia en español sobre el tema.

---

## Temas desarrollados en las notas de los participantes

### Jonathan
1. Partícula arbitraria
    - [x] Condiciones a la frontera por conservación de la energía
    - [x] Matriz de amplitiud de esparcimiento (general)
    - [x] Comportamiento asintótico de un campo eléctrico consideran sólo e dipolo eléctrico
    - [x] Parámetros de Stokes
    - [x] Sección transversal de extinción, absorción y esparcimiento (generales)
    - [x] Teorema óptico
    - [x] Extinción por una placa delgada (coeficientes de amplitud con un índice de refracción efectivo)
    - [x] Coeficiente de extinción
    - [ ] Diagramas o figuras propios

2. Partícula esférica
    - [x] Armónicos vectoriales (generales)
    - [ ] Escribir el vector piloto no como constante, sino como el radio-vector \vec{r} (lo tengo en las notas de mi tesis, ntp)
    - [x] Solucion completa de la función generadora de los armónicos esféricos vectoriales
    - [x] Todas las relaciones de ortogonalidad (con desarrollo) de los armónicos esféricos vectoriales
    - [x] Cálculo del coeficiente B_{o1\ell} de la onda plana
    - [ ] Cálculo del coeficiente A_{e1\ell} de la onda plana
    - [x] Deficinición de \tau_{\ell}  y \pi_{\ell}
    - [ ] Cálculo de su relación de ortogonalidad
    - [ ] Cálculo del sistema de ecuaciones para determinar a los coeficitnes a_{\ell}, b_{\ell}, c_{\ell} y d_{\ell}
    - [ ] Solución del sistema de ecuaciones (aunque Amauri también cree que este paso es irrelevante)
    - [x] Cálculo explícito de la matriz de esparcimiento de Mie
    - [x] Diagramas o figuras propios (incluye gif de los modos normales)

3. Esfera
    - [x] Caso estático del campo eléctico cuando incide una onda plana sobre una esfera (partícula pequeña)
    - [x] Caso dinámico de al considerar un fuente oscilante (y sólo la contribución dipolar, igual que en 1)
    - [x] Aproximación empleando la solución de Medie
    - [ ] Comparar que el caso dinámico y el esttico coinciden (falta rotar un sistema pues una polarización es en el eje x mientras que la otra es en el eje z)
    - [x] diagramas propios (que hay que mejorar)

4. Proyecto EVOO
    - [x] mediciones experimentales con NPs de oro y plata que comparan la sección de extinción, esparcimiento y absorciín de partículas pequeñas empleando la solución de Mie
    - [ ] Desarrollo teórico de las secciones transversales en términos de los coeficientes de mie

### Amauri
1. Coeficiente de esparcimiento
    - [x] Presentación de los armónicos esféricos vectoriales
    - [x] Forma explícita de las condiciones a la frontera de una esfera del campo incidente, el campo dentro de la partícula y el campo esparcido en térmonos de los armónicos esféricos vectoriales
    - [ ] Cálculo del sistema de ecuaciones para determinar a los coeficitnes a_{\ell}, b_{\ell}, c_{\ell} y d_{\ell}

2. Ripple Structure
    - [x] Explicación de la C_{ext} de una gota de agua
    - [x] Análisis de a_{\ell} y b_{\ell}
    - [x] Discusión del esparcimiento de Rayleigh
    - [ ] Diagramas propios

3. Authors template (Springer)
    - [x] Matriz de amplitiud de esparcimiento (general)
    - [x] Algunas relaciones de ortogonalidad (con desarrollo) de los armónicos esféricos vectoriales
    - [x] Cálculo del coeficiente B_{o1\ell} de la onda plana
    - [ ] Cálculo del coeficiente A_{e1\ell} de la onda plana
    - [x] Explición del significado de los diagramas de mie
    - [x] Cita de Mie sobre sus diagramas, dado que nadie hace la discución (Si gustas, yo leí el artículo original para entender las gráficas y lo podemos ttraducir nosotros, cómo ves?)
    - [ ]Diagramas propios
    - [ ]**Hay problemas de compilación**

## Referencias
[1] 1. G. Mie, "Beiträge zur Optik trüber Medien, speziell kolloidaler Metallösungen," _Ann. Phys._ 330, 377–445 (1908).
[2] C.F. Bohren y D. R. Huffman. _Absorption and scattering of light by small particles._ John Wiley & Sons, 1908.
