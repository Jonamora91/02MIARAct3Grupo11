# Generar archivo latex visualizando el DEBUG
jupyter nbconvert --debug --to=latex Actividad\ 3.ipynb

# Generar archivo latex
jupyter nbconvert --to=latex Actividad\ 3.ipynb

# Generar PDF a partir de un archivo .tex
xelatex Actividad\ 3.tex

# Generar PDF directamente desde el notebook
jupyter nbconvert --to=pdf Actividad\ 3.ipynb


##
\begin{titlepage}
        % Encabezado de la Institución
        \begin{center}
          \includegraphics[width=0.5\textwidth]{resources/viu.png}\\[2cm]
          \textbf{\Huge Actividad evaluada \#3}\\[1cm]
        \end{center}

        % Detalles del Trabajo
        \begin{center}
          \textbf{\Large 02MIAR}\\[0.5cm]
          \textbf{\large Matemáticas para la Inteligencia Artificial}\\[2cm]
          
          \textbf{\Large Profesor}\\[0.5cm]
          \textbf{\large Dr. Matthieu F.-W. Huber}\\[2cm]
          
          \textbf{\Large Grupo No. 11}\\[1cm]
          \textbf{\large Jonathan Mora}\\
          \textbf{\large Luis Jama Tello}\\
          \textbf{\large Blanca Santos Fernández}\\
          \textbf{\large Laura Betancourt Leal}\\[2cm]
          
          \textbf{\Large Junio 2024}
        \end{center}
    \end{titlepage}
##

##
\pagenumbering{gobble} % Para desactivar numeración en las páginas anteriores
    \textbf{\Large Índice general}\\[0.5cm]
    \contentsline {section}{\numberline {1}Ejercicios acerca del determinante}{1}{section.1}
    \contentsline {subsection}{\numberline {1.1}Desarrollo de Laplace.}{1}{subsection.1.1}
    \contentsline {subsubsection}{\numberline {1.1.1}Deducir de la definición 4 el determinante en dimensión 0, 1 y 2.}{1}{subsubsection.1.1.1}
    \contentsline {paragraph}{Dimensión 0}{1}{section*.2}
    \contentsline {paragraph}{Dimensión 1}{1}{section*.3}
    \contentsline {paragraph}{Dimensión 2}{1}{section*.4}
    \contentsline {subsubsection}{\numberline {1.1.2}A partir de la definición 4, expresar el determinante de una matriz cuadrada recursivamente en función de determinantes la matrices cuadradas de dimensión inferior.}{2}{subsubsection.1.1.2}
    \contentsline {subsubsection}{\numberline {1.1.3}Implementar en Python la definición así obtenida.}{3}{subsubsection.1.1.3}
    \contentsline {subsection}{\numberline {1.2}Ejercicio 2 : Eliminación de Gauss--Jordan.}{6}{subsection.1.2}
    \contentsline {subsubsection}{\numberline {1.2.1}Deducir de la definición 4 el efecto que tiene en el determinante de una matriz sumar a una de sus columnas una combinación lineal de las demás.}{6}{subsubsection.1.2.1}
    \contentsline {subsubsection}{\numberline {1.2.2}A partir de la definición 4, proponer una estrategia para triangularizar una matriz sin cambiar su determinante e implementar en Python una definición alternativa del determinante. Indicación: descomponer similarmente al ejercicio anterior.}{6}{subsubsection.1.2.2}
    \contentsline {subsubsection}{\numberline {1.2.3}Implementar en Python la definición así obtenida}{6}{subsubsection.1.2.3}
    \contentsline {subsection}{\numberline {1.3}Ejercicio 3: Comparación.}{6}{subsection.1.3}
    \contentsline {subsubsection}{\numberline {1.3.1}Obtener la complejidad computacional de cada una de estas dos implementaciones.}{6}{subsubsection.1.3.1}
    \contentsline {subsubsection}{\numberline {1.3.2}Generar matrices aleatoriamente en dimensión \(n ∈\) \{ 2, 3, · · , 9, 10 \} y comparar el tiempo de ejecución de cada una de estas dos implementaciones con la función numpy.linalg.det (la función determinante de la extensión numérica de Python al álgebra lineal). Indicación: se puede utilizar la función numpy.random.rand para generar los coeficientes aleatorios de sus matrices.}{7}{subsubsection.1.3.2}
    \contentsline {section}{\numberline {2}Ejercicios acerca del gradiente}{9}{section.2}
    \contentsline {subsection}{\numberline {2.1}Ejercicio 4 : Método descenso del gradiente}{9}{subsection.2.1}
    \contentsline {subsubsection}{\numberline {2.1.1}Implementar en Python un algoritmo de descenso del gradiente (con un máximo de m = \(10⁵\) iteraciones) a partir de los siguientes argumentos tomados en ese orden:}{9}{subsubsection.2.1.1}
    \contentsline {subsubsection}{\numberline {2.1.2}Calcular formalmente \(\{ 𝑡 ∈ R. 𝑓 ′(𝑡) = 0 \}\) para \(𝑓 : 𝑡 ↦ 3𝑡⁴+4𝑡³−12𝑡²+7\).}{11}{subsubsection.2.1.2}
    \contentsline {subsubsection}{\numberline {2.1.3}Con una tolerancia \(z = 10⁻¹²\) y un valor inicial de \(x = 3\) aplicar su algoritmo con razón \(y = 10⁻¹\), \(10⁻²\), \(10⁻³\) luego hacer lo mismo con \(x = 0\). Interpretar el resultado.}{13}{subsubsection.2.1.3}
    \contentsline {subsubsection}{\numberline {2.1.4}\hyperref [toc0_]{Repetir estos dos últimos apartados con 𝑓 : (𝑠, 𝑡) ↦ 𝑠² + 3𝑠𝑡 + 𝑡³ + 1 y los valores iniciales x = [-1,1], [0,0].}}{17}{subsubsection.2.1.4}
    \clearpage
    \pagenumbering{arabic} % Para activar la numeración en arábigo
    \setcounter{page}{1}   % Para reiniciar la numeración de páginas desde 1

    \newpage

##