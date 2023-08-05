#    Media queries

Este es un trabajo un poco artesanal para un novato como yo, por eso hay que estar atentos a los porcentajes, esas molestas barras de dezplazamiento lateral le sacan ese lindo toque.
	
	
	
	
	
	
	* Media query para pantallas de 320px de ancho (celulares y formatos similares) */
    @media (max-width: 320px) {
      body {
        margin-top: 200px;
        margin-left: 10px;
        margin-right: 10px;
    
      }
    
      header {
        position: absolute;
        width: 100%;
        margin-left: -20px;
        background-color: #2f0b84;
        z-index: 999;
        height: 170px;
        justify-content: center;
        align-items: center;
      }
    
      main {
    
        margin-left: -10px;
        margin-right: -10px;
        margin-top: 200px;
        margin-bottom: 40px;
    
      }
    
    
    }
    
    
    /* Media query para pantallas con ancho entre 321px y 900px (celulares y formatos similares) */
    @media (min-width: 321px) and (max-width: 900px) {
      body {
        margin-top: 20px;
      }
    
      header {
        position: absolute;
        width: 100%;
        margin-left: -20px;
        background-color: blue;
        z-index: 999;
        height: 170px;
        justify-content: center;
        align-items: center;
      }
    
      main {
        margin-left: 20px;
        margin-right: 20px;
        margin-top: 200px;
        /*para que suba el main*/
        margin-bottom: 40px;
        /*para que baje main*/
      }
    
    }
