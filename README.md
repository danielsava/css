# CSS

Material de referência e consulta.

Fontes:

 - https://developer.mozilla.org/pt-BR/

<br/>

## Cascading Style Sheet

O `cascading` sugere que o CSS obedece uma `hierarquia` na definição de suas estilizações: 
  
    Para um mesmo elemento, podemos ter mais de uma definição de estilização. 
    A definição `mais específica` terá prioridade, autoridade, sobre a `menos específica`. 

<br/>

## Definição: elemento, classes e id


    h1 {
      font-size: 18px; // px, em e rem
    }
    
    .cabecalho {
      font-size: 20px;
    }
    
    #titulo {
      font-size: 25px
    }


<br/>

Para definição de estilo acima temos, à título de exemplo, a seguinte aplicação:

    <h1 class="cabecalho" id="titulo">Título</h1>
    
Em virtude da característica de `cascading` do CSS o texto `Título` terá uma fonte de 25px, pois o `id` é a definição de CSS mais `específica` para este elemento, pois teremos somente 1 elemento na DOM com o `id="titulo"`.
