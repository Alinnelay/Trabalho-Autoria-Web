# Trabalho-Autoria-Web
Trabalho usando html no Vscode. O objetivo do trabalho é praticar os conhecimentos passados em aula. O trabalho data-se de criar uma pagina web com as seleções da copa do mundo feminina 2023, onde ao clicar em uma das bandeiras abra outra página com as suas jogadoras convocadas. Em meu trabalho as bandeiras escolhidas foram: Brasil e Colômbia.
<!DOCTYPE html>
<html>
    <head>
        <style>
            #logo{
                text-align: center;
            }
            #tabela{
                text-align: center;
            }
            h1{
                font-size: 2.0rem;
                text-align: center;
                color: orangered;
            }
            h2{
                font-size: 1.5rem;
                text-align: justify;
                color: blue;
            }
            h3{
                font-size: 1.2rem;
                text-align: center;
                color: palevioletred;
            }
        </style> 

        <title> Copa do Mundo Feminina 2023 </title>
        
    </head>

    <!-- As bandeiras que abrem outra pagina são as do Brasil e Colombia -->

    <body>
        <div id="logo">
            <img src="img/logo.png.png" alt="Copa do mundo 2023" title="Logo da Copa do Mundo Feminina 2023" width="50%" height="50%">
        </div>

        <hr/>

        <div id="tabela">
            <figure>
                <h3> Tabela de Jogos </h3>
                <img src="img/tabela_fifa.png.png" alt="tabela da fifa" title="Tabela de jogos">
                <figcaption> Calendário da Copa do Mundo 2023 </figcaption>

                <h3> Tabela de grupos </h3>
                <img src="img/tabela_grupos.png" alt="Tabela de grupos" title="Grupos Copa do Mundo 2023">
                <figcaption> Tabela de Grupos Copa do Mundo 2023</figcaption>
            </figure>
        </div>

        <hr/>

        <h1> Seleções Convocadas </h1>
        
        <div id="GrupA">
            <h2> Grupo A </h2>
            <img src="img/GrupA/nova-zelandia.png.png" alt="Nova Zelandia" title="Seleção da Nova Zelândia"> 
            <img src="img/GrupA/noruega.png" alt="Noruega" title="Seleção da Noruega">
            <img src="img/GrupA/filipinas.png" alt="Filipinas" title="Seleção da Filipinas"> 
            <img src="img/GrupA/suica (1).jpg" alt="Suíça" title="Seleção da Suíça" width="300px" height="150px">
        </div>

        <div>
            <h2> Grupo B </h2>
            <img src="img/GrupB/Australie.png" alt="Austrália" title="Seleção da Austrália" width="300px" height="150px">
            <img src="img/GrupB/Irlande.png" alt="Irlanda" title="Seleção da Irlanda" width="300px" height="150px">
            <img src="img/GrupB/Nigeria.png" alt="Nigéria" title="Seleção da Nigéria" width="300px" height="150px">
            <img src="img/GrupB/Canada.png" alt="Canadá" title="Seleção do Canadá" width="300px" height="150px">
        </div>

        <div>
            <h2> Grupo C </h2>
            <img src="img/GrupC/Espagne.png" alt="Espanha" title="Seleção da Espanha" width="300px" height="150px">
            <img src="img/GrupC/Costa_Rica.png" alt="Costa Rica" title="Seleção da Costa Rica" width="300px" height="150px">
            <img src="img/GrupC/Zambie.png" alt="Zâmbia" title="Seleção da Zâmbia" width="300px" height="150px">
            <img src="img/GrupC/Japon.png" alt="Japão" title="Seleção do Japão" width="300px" height="150px">
        </div>

        <div>
            <h2> Grupo D </h2>
            <img src="img/GrupD/England.png" alt="Inglaterra" title="Seleção da Inglaterra" width="300px" height="150px">
            <img src="img/GrupD/Haiti.png" alt="Haiti" title="Seleção do Haiti" width="300px" height="150px">
            <img src="img/GrupD/Danemark.png" alt="Dinamarca" title="Seleção da Dinamarca" width="300px" height="150px">
            <img src="img/GrupD/Chine.png" alt="China" title="Seleção da China" width="300px" height="150px">
        </div>

        <div>
            <h2> Grupo E </h2>
            <img src="img/GrupE/USA.png" alt="Estados Unidos" title="Seleção dos Estados Unidos" width="300px" height="150px">
            <img src="img/GrupE/Viet_Nam.png" alt="Vietnã" title="Seleção do Vietnã" width="300px" height="150px">
            <img src="img/GrupE/Pays-Bas.png" alt="Países Baixos" title="Seleção dos Países Baixos" width="300px" height="150px">
            <img src="img/GrupE/Portugal.png" alt="Portugal" title="Seleção de Portugal" width="300px" height="150px">
        </div>

        <div>
            <h2> Grupo F </h2>
            <img src="img/GrupF/France.png" alt="França" title="Seleção da França" width="300px" height="150px">
            <img src="img/GrupF/Jamaique.png" alt="Jamaica" title="Seleção da Jamaica" width="300px" height="150px">
            <a href="pagina.html"> <img src="img/GrupF/Bresil.png" alt="Brasil" title="Seleção Brasileira" width="300px" height="150px"> </a>
            <img src="img/GrupF/Panama.png" alt="Panamá" title="Seleção do Panamá" width="300px" height="150px">
        </div>

        <div>
            <h2> Grupo G </h2>
            <img src="img/GrupG/Suede.png" alt="Suécia" title="Seleção da Suécia" width="300px" height="150px">
            <img src="img/GrupG/Afrique_du_Sud.png" alt="Àfrica do Sul" title="Seleção da África do Sul" width="300px" height="150px">
            <img src="img/GrupG/Italie.png" alt="Itália" title="Seleção da Itália" width="300px" height="150px">
            <img src="img/GrupG/Argentine.png" alt="Argentina" title="Seleção Argentina" width="300px" height="150px">
        </div>

        <div>
            <h2> Grupo H </h2>
            <img src="img/GrupH/Allemagne.png" alt="Alemanha" title="Seleção Alemã" width="300px" height="150px">
            <img src="img/GrupH/Maroc.png" alt="Marrocos" title="Seleção Marroquina" width="300px" height="150px">
            <a href="pagina2.html"> <img src="img/GrupH/Colombie.png" alt="Colômbia" title="Seleção Colombiana" width="300px" height="150px"> </a> 
            <img src="img/GrupH/Coree_du_Sud.png" alt="Coréia do Sul" title="Seleção da Coréia do Sul" width="300px" height="150px">
        </div>

        
    </body>
</html>
