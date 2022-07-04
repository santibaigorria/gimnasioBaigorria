Utilidades:
-Paleta de colores:
    -#881717 (Header)
    -#E7ECEF (Main)
    -#6c757d (Titulos)
    -#272932 (Footer)
    -#d1d7da (Detalles)

.seccionGym{
    background-color: #E7ECEF;
 
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
}

        /* MEDIA QUERIES SECCION GYM
    @media screen and (min-width: 320px){
        .seccionGym{
            display: flex;
            flex-direction: column;
        }

        .seccionGym__foto{
            width: auto;
            max-height: 200px;
        }
    }

    @media screen and (min-width: 600px){
        .seccionGym__contenedor{
            display: flex;
            flex-direction: row;
            overflow-x: scroll;
        }
    }

    @media screen and (min-width: 1024px){
        .seccionGym__titulo{
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .seccionGym__contenedor{
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: repeat(2, 1fr);

            overflow-x: hidden;
        }
    } */

.seccionGym__titulo{
    background-color: #6c757d;
    color: white;

    padding-top: 5px;
    padding-bottom: 7px;

    text-align: center;

    grid-column: 1/5;
}

.seccionGym__contenedor{
    /* background-color: rgb(209, 209, 209); */

    padding-top: 6%;
    padding-bottom: 6%;
}

    /* Futuro carrusel de fotos */
.seccionGym__foto{
    width: 90%;
    padding: 10px;

    display: flex;
    justify-self: center;
}

    /* -----------Seccion Nosotros----------- */
.seccionNosotros{
    background-color: #E7ECEF;

    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: 35px 1fr;
    column-gap: 10px; ;
}
        /* MEDIA QUERIES SECCION NOSOTROS
    @media screen and (min-width: 320px) {
        .seccionNosotros{
            display: flex;
            flex-direction: column;

            padding: 5px;
        }
        
        .seccionNosotros__titulo, .seccionNosotros__ubicacion{
            padding: 5px;
        }
    }

    @media screen and (min-width: 600px) {
        .seccionNosotros{
            display: flex;
            flex-direction: column;
        }
        
        .seccionNosotros__titulo, .seccionNosotros__ubicacion{
            padding: 10px;
        }
    } 

    @media screen and (min-width: 1024px) {
        .seccionNosotros{
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: 35px 1fr;
            column-gap: 10px; ;
        }
    }*/

.seccionNosotros__titulo, .seccionNosotros__ubicacion{
    background-color:  #6c757d;
    color: white;
    border-radius: 10px;

    text-align: center;
}

.seccionNosotros__titulo{
    grid-column: 1/3;
    grid-row: 1;
}

.seccionNosotros__ubicacion{
    grid-column: 3/5;
    grid-row: 1;
}

.seccionNosotros__descripcion{
    padding: 10px;

    text-align: center;

    grid-column: 1/3;
    grid-row: 2;
}

.seccionNosotros__descripcion--dos{
    padding: 10px;
    display: flex;
    align-items: center;

    text-align: center;

    grid-column: 3/4;
    grid-row: 2;
}

.seccionNosotros__ubicacion--mapa{
    padding: 2%;
    width: 100%;

    display: flex;
    justify-self: center;

    border: 0;

    grid-column: 4/5;
    grid-row: 2;
}
    /* Seccion Actividades */
.seccionActividades{
    background-color: #e7ecef;
    padding: 10px;
}

.seccionActividades__titulo{
    background-color: #6c757d;
    color: white;
    padding: 10px;
    text-align: center;

    border-radius: 10px;
}

.seccionActividades__act a{
    text-decoration: none;
    color: black;
}

.seccionActividades__act a:hover{
    text-decoration:underline;
}