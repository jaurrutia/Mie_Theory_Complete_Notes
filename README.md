# Mie Theory Notes - Notas de teoría de Mie
A student-edited text in spanish on Mie Theory with computational examples
- Jonathan A. Urrutia-Anguiano
- Isabel Y. Rojas-Martinez
- Eduardo Enrique Viveros-Armas

**Project status: Draft**

## Abot this project
The Mie Theory is the solution to the problem of light scattering and absorption by an arbitrary spherical particle developed by Gustav Mie in 1908 [[1](1)]. Physics students at the [Science Faculty](http://www.fciencias.unam.mx/), [National Autonomous University of Mexico](http://english.unam.mx/) participated in a Mie Theory Seminar organized by the [Nanoplasmonics Group](http://sistemas.fciencias.unam.mx/~coronado/index.php), which was  mainly based on the book written by [Bohren & Hoffman](2). As a byproduct of this seminar, some students started their own notes, as well as some computational programs, and shared them with the rest of the participants. **We want to revisit this notes and codes to write a student-edited book in spanish** due to the lack of material of this topic in this language.

#### Writting tools
Draft directory: [Draft_Teoria_de_Mie_LaTeX](/Draft_Teoria_de_Mie_LaTeX)

 We use a standard LaTeX distrubution. In order to homogenize the mathematical notation and the bibiography we employ:
- The [Physics package](http://mirrors.ibiblio.org/CTAN/macros/latex/contrib/physics/physics.pdf)
- [biblatex](https://www.ctan.org/pkg/biblatex)

#### Coding tools: Wolfram Language & Jupyter Lab
Codes directory: [Mathematica_Mie_JupyerNotebooks](/Mathematica_Mie_JupyerNotebooks)

A common language used by the collaborators of this project is the Wolfram Language. To make the content of the developed codes accessible to anyone, even without a Wolfram Language License, we recently started using the Wolfram Language in the Jupyter Lab notebooks.

If you are interested in this implementation please visit
- [Wolfram Script](https://reference.wolfram.com/language/workflow/InstallWolframScript.html), to run a Wolfram Engine from terminal eventhough a Kernel is available
- [Install the Wolfram Engine](https://support.wolfram.com/46072), Installation of the Wolfram Engine in Linux
- [Wolfram Language for Jupyter](https://github.com/WolframResearch/WolframLanguageForJupyter), a Wolfram Research project
- [Mathematica for poor Undergrads](https://www.davecwright.org/post/mathematica_jupyter/), an installation guide
- [How to install and configurate Wolfram Engine, SetReplace and Jupyter in 4 steps](https://www.youtube.com/watch?v=C9B88AI5DMY&t), video in spanish

Note that you need Jupyter Lab installed beforehand.

![Dipolar resonanse](/Mathematica_Mie_JupyterNotebooks/0-Calculos/1-Gifs/Ne11/Ne11_crop.gif )

---
## For the collaborators (In spanish)

### Temario tentativo y división de tareas
En esta sección se resumena de manera somera las tareas de cada colaboradores en las distintas secciones del borrador.

##### Sección 1: Teoría de Mie y aproximaciones
1. Conceptos de electromagnetismo (Isabel y Eduardo)
2. Teoría general de esparcimiento (Jonathan)
  - Reredactar teorema óptico (Jonathan)
3. Armónicos esféricos vectoriales (Jonathan y Eduardo)
  - Agregar sección sobre los tres armónicos esféricos vectoriales (Eduardo)
4. Esparcimiento y absorción de una esfera
  - Redactar a partir de las notas de Jonathan (Eduardo)
  - Límite cuasiestático (Jonatha - Por escribir)
5. Casos particulares

##### Sección 2: Temas avanzados
1. Teoría de Mie extendida (Jonathan)
  - Meter texto de Lalo con el formato anterior

##### Apéndices
1. **A**: Teorema óptico de van de Hust

### Tareas pendientes

Labores faltantes sin asignación para la escritura del borrador

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
  - [x] Homogenizar comandos en LaTeX (Librería _Physics_)
  - [ ] Homogenizar las gráficas ya producidas
      - [ ] Suspensión coloidal de oro (experimento)
      - [ ] Suspensión coloidal de plata (experimento)
      - [ ] Partícula de agua (cambiar a \lambda o a \hbar\omega)
  - [ ] Diagrama para explicar la determinación de los parámetros de Stokes
  - [ ] Diagrama para explicar el teorema óptico


3. Estilo y redacción
    - [ ] Introducción a cada sección
    - [ ] Citas para teoría de Mie extendida (transferencia de momento)

---
## References
- [1] [G. Mie, "Beiträge zur Optik trüber Medien, speziell kolloidaler Metallösungen," _Ann. Phys._ 330, 377–445 (1908).](https://onlinelibrary.wiley.com/doi/epdf/10.1002/andp.19083300302)
- [2] [C.F. Bohren and D. R. Huffman. _Absorption and scattering of light by small particles._ John Wiley & Sons, 1908.](https://books.google.com.mx/books/about/Absorption_and_Scattering_of_Light_by_Sm.html?id=ib3EMXXIRXUC&redir_esc=y)
