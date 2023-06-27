# LAB

Link naar website:
https://doortjedh.github.io/LAB/

How to:

Thema toevoegen:
1. Maak een nieuwe pagina aan met de naam naamthema.html
2. Kopieer en plak hierin de code van een andere thema pagina
3. Kopieer de volgende code;

            <div class="grid-item-thema">
                <h2>Thema 1</h2>
                <!--Pas hierboven de titel van het thema aan-->
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
                    et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
                    aliquip ex ea commodo consequat.</p>
                <!--Pas hierboven de beschrijving van het thema aan-->
                <a href="thema1.html">
                    <!--Vul hier de juiste link van de thema pagina in-->
                    <div class="text-button-div-thema">
                        <p class="text-button-text">BEKIJK PROJECTEN</p>
                        <img src="img/arrow-right-top.svg" class="text-button-arrow">
                    </div>
                </a>
            </div>

4. Plaats de code in de index.html voor de comment "Voeg voor deze comment de code voor een nieuw thema in"
5. Verander de titel en tekst naar de juiste content
6. Pas de link aan naar de pagina van het thema
7. Sla op

Project toevoegen
1. Maak een nieuwe pagina aan met de naam naamproject.html
2. Kopieer en plak hierin de code van een andere project pagina
3. Voeg de thumbnail van het project toe aan de map img
4. Kopieer de volgende code en plaats deze in themanaam.html voor de comment "Voeg voor deze comment de code voor een nieuw project in";

             <div class="grid-item">
                <div class="project-thumbnail project1">
                </div>
                <div class="project-content-wrapper">
                    <p class="project-titel">Homo Fermentis</p>
                    <!--Vul hierboven de juiste titel in van het project-->
                    <a href="https://github.com/Doortjedh/LAB/tree/main/doortje">
                        <!--Vul hierboven de juiste link in naar het project-->
                        <div class="project-link-div">
                            <img src="img/arrow-right-top.svg">
                        </div>
                    </a>
                </div>
            </div>

5. Verander het nummer van de class met de naam "project1" naar het juiste nummer
6. Verander de titel naar de juiste content in de themanaam.html\
7. Pas de link aan naar de pagina van het project
8. Kopieer de volgende code en plaats deze in style.css onderaan de pagina;

            .project1 {
                background-image: url('img/afbeeldingnaam.png');
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
            }

9. Verander de class van het project naar het juiste nummer
10. Verander de thumbnail van het project in de style.css bij de comment "voeg hierboven de juiste thumbnail in voor het project"
11. Sla op

<!--Continue @Timo--!>