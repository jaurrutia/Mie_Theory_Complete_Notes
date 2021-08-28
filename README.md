# Notas de la solución de Mie

La solución de Mie, también conocida como teoría, resuelve el problema de absorción de luz por una esfera de tamaño y material arbitrario al ser iluminada por una onda plana. Gustav Mie publica su artículo [[1](1)] en 1908 y en éste resuelve la ecuación de Helmholtz y resuelve los campos electromagnéticos (EMs) esparcidos por la esfera, así como los campos EM dentro de ella.

Como parte de un seminarios dedicado a la solución de Mie, basado en el libro de Bohren y Huffman [[2](2)], se crearon diversas notas por los participantes del seminario, en donde se comenta y da detalle del procedimiento matemático necesario. La propósito de este repositorio es el compilar las notas de cada participante y generar una referencia en español sobre el tema.

---
## Presunto temario

1. Conceptos de electromagnetismo (Isabel y Lalo)
2. Teoría general de esparcimiento (Jonathan)
  - Reredactar teorema óptico (Jonathan)
3. Armónicos esféricos vectoriales (Jonathan y Eduardo)
  - Agregar sección sobre los tres armónicos esféricos vectoriales (Eduardo)
4. Esparcimiento y absorción de una esfera
  - Redactar a partir de las notas de Jonathan (Eduardo)
  - Límite cuasiestático (Jonatha - Por escribir)
5. Casos particulares

# Secciones avanzadas
1. Teoría de Mie extendida (Jonathan)
  - Meter texto de Lalo con el formato anterior

# Apéndices
1. **A**: Teorema óptico de van de Hust


---

## Tareas pendientes

1. Procedimientos faltantes
    1. Matriz de esparcimiento de Mie
        - [ ] Cálculo del coeficiente A_{e1\ell} de la onda plana (Dice Eduardo Vivero que ya lo tiene resulto, falta pasarlo a LaTeX)
        - [ ] Cálculo de su relación de ortogonalidad de \tau_\ell\pm\pi_\ell
        - [ ] Cálculo del sistema de ecuaciones para determinar a los coeficitnes a_{\ell}, b_{\ell}, c_{\ell} y d_{\ell}
    2. Sección transversal de extinción, absorción y esparcimiento
        - [x] C_{ext} y C_{sca} en términos de los coeficientes de Mie a_\ell y b_\ell
    3. Límite de partícula pequeña
        - [ ] Comparar que el caso dinámico y el estático coinciden (falta rotar un sistema pues una polarización es en el eje x mientras que la otra es en el eje z)

2. Ejemplos y diagramas
    - [ ] Homogenizar comandos en LaTeX (Librería _Physics_)
    - Homogenizar las gráficas ya producidas
        - [ ] Suspensión coloidal de oro (experimento)
        - [ ] Suspensión coloidal de plata (experimento)
        - [ ] Partícula de agua (cambiar a \lambda o a \hbar\omega)
    - [ ] Diagrama para explicar la determinación de los parámetros de Stokes
    - [ ] Diagrama para explicar el teorema óptico

3. Estilo y redacción
    - [ ] Gramática y ortografía
    - [ ] Introducción a cada sección
    - [ ] Citas para teoría de Mie extendida (transferencia de momento)

## Referencias
- [1] [G. Mie, "Beiträge zur Optik trüber Medien, speziell kolloidaler Metallösungen," _Ann. Phys._ 330, 377–445 (1908).](https://onlinelibrary.wiley.com/doi/epdf/10.1002/andp.19083300302)
- [2] [C.F. Bohren y D. R. Huffman. _Absorption and scattering of light by small particles._ John Wiley & Sons, 1908.](https://books.google.com.mx/books/about/Absorption_and_Scattering_of_Light_by_Sm.html?id=ib3EMXXIRXUC&redir_esc=y)
