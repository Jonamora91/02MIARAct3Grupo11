# Generar archivo latex visualizando el DEBUG
jupyter nbconvert --debug --to=latex Actividad\ 3.ipynb

# Generar archivo latex
jupyter nbconvert --to=latex Actividad\ 3.ipynb

# Generar PDF a partir de un archivo .tex
xelatex Actividad\ 3.tex

# Generar PDF directamente desde el notebook
jupyter nbconvert --to=pdf Actividad\ 3.ipynb


##
\renewcommand{\contentsname}{Contenido}
\begin{document}

    % Portada
    \begin{titlepage}
        \centering
        \newgeometry{margin=0cm}
        % Ajustar la imagen para que ocupe todo el ancho y alto de la página
        \begin{tikzpicture}[remember picture,overlay]
            \node at (current page.center) {\includegraphics[width=\paperwidth,height=\paperheight,keepaspectratio]{resources/02MIAR_Actividad3.png}};
        \end{tikzpicture}

    \end{titlepage}

    % Generar tabla de contenido
    \tableofcontents
    \clearpage

    % Numeración de páginas en arábigo
    \pagenumbering{arabic}
    \setcounter{page}{1} 

    % Comienzo del contenido

