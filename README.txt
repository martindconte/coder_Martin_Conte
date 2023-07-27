*** COMPILACION SASS ***

***********************************************************************************
*                                                                                 *      
*                       sass --watch scss/main.scss css/style.css                 *       
*                                                                                 *      
***********************************************************************************

*** CARPETA BASE *** 

_colors.scss --> Colores utilizados
_fonts.scss --> Fuentes Utilizadas. Se utilizaron desde Google fonts
_normalize --> Inicializacion de Pagina (RESET)

*** COMPONENTES ***

_button.scss --> Creacion de extend Boton y reutilizacion de clases
_tipografias --> Creacion de tipos de tipografias a utilizar. Creacion de extendes y clases reutilizables

*** LAYOUTS *** --> Reutilizables

_footers.scss --> scss del footer comun a todas las paginas
_grid.scss --> creaion de GRIDS
_mixin.scss --> creacion de mixins

*** UTILITIES ***

_variables.scss --> maps de fuentes tipografias y tamaños de letra. Definicion de breakpoint

Breakpoint	        Class infix     Dimensions
Extra small 	        None	        <576px
Small	                sm	        ≥576px
Medium	                md              ≥768px
Large	                lg              ≥992px
Extra large	        xl              ≥1200px
Extra extra large	xxl	        ≥1400px

*** VENDORS ***

_bootstrap --> scss aplicado a bootstrap (slide de imagenes  en index, header y plantilla de datos en pagina signatureGibson)

*** VIEWS ***

Estructuracin de archivos scss que se aplican a cada pagina y media query