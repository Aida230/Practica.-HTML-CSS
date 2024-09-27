"# Practica.-HTML-CSS"


en la pagina codepen tienes ejemplos y opciones de escoger codigo para utilizarlo
Flexbox:
Es para alinear los elementos
Logo de ataque a los titanes
stiky es posicion fija
el flex funciona con el concepto de padre hijo o conteiners e items (div es el contenedor por ejemplo y los otros div son los items)
el div no tiene valor semantico y se comporta como bloque
display: flex; convierte los elementos de un mismo contenedor en posicion horizontal eso me vale para el proyecto, y puedes mover las cajas donde quieras. propiedades
justify-content:left o center o right ese justo lo necesitio
justify_content: space-between te los separa entre ellos pegandolo haca afuera totalmente y puedes controlar mejor los padding
el border-box te asegura que todo ocupe la marca que tu le das y os valores se ajustan a eso

flex-direction: column es para alinearlo en vertical
felx-wrap: no-wrap; es que siempre van a estar en la misma linea y el wrap si haces la pantalla mas pequeña los elementos pasan a la parte de abajo

si es de un solo eje utilizamos flex pero para muchos elementos es mejor que  no
display:flex; 
justify-end te manda una caja a la parte final de la pagina al corner derecho
recomendacion tener todas las imagenes al 100 de ancho


si pones controls o autoplay en un vdeio te lo empieza a reproducir

a las imagenes siempre hay que ponerle un ancho relativo o un withd que se adapte
iframe es para añadir pedazos de otras web como por ejemplo para google maps o videos de youtube


MOVILE FIRST:
- El diseño responsable es un concepto que pretender adaptar todo el contenido en cualquier dispositivo

web.dev pagina para hacer cursos y estudiar cosas!!!!

MEDIA QUERIES cuando quieres modificar tus estilos dependiendo del dispositivo

type @media screen, print {..} 

@media (prefers-color-schema: light /* esto te dice como tienes el pc cpnfigurad sin modo oscuro o claro*/) {
    :root {
        --bg-color: #FFF;
        --main-text-color: #000;

    }

}



background-repeat: no-repeat; /* esto es para que la imagen no se repita*/
        background-size: contain;/*obliga a mostrar la imagen por completo en el contenedor creado*/
        background-size: cover;/*ocupa todo el espacio sin deformar la imagen*/
