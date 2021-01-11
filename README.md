# Informatik-logbog
Logbog til informatik :)


## Makerspace - 3d print

- Vi skulle downloade fusion, og lave 3 simple figurer.

- Ved at bruge lasercut kan vi cutte vores figurer til x antal lag.
- I makerspace kunne vi så downloade vores figurer til et minisd kort hvorefter at vi sat den til at printe i 3d printeren.


![3dPrint](Images/3dprint.png)



## Tello drone

##### Analyse af drone

- Vi skulle lave en analyse af tello dronen
- Blokdiagrammer, flowcharts og i en 3-lags model med præsentationslaget, logiklaget og datalaget

![3lagsmodel](Images/89A0D06F-A4E3-4679-95AF-C02072A1B22E.jpeg)

##### Drone kontroller

- Startede med at opstille brainstorm, flowchart og blokdiagram
- Vi satte en jobliste op og begyndte at skrive koden
- Vi satte en arduino med et joystick op
- Efter satte vi et breadboard op med en knap
- Koden blev skrevet i c++ i Arduino IDE'en, denne kode ville tage imod inputs fra knappen og joysticket og give os et input
- Dette input ville vi så senere kunne bruge til at styre dronen

![Arduino](Images/Arduino.png)


- Nu skrev vi kode i python(pycharm), som kunne tage imod et serial print fra c++(arduino) og give os et output i python 
- Vi satte en brugerundersøgelse op for vores controller
- Til denne brugerundersøgelse brugte vi 
[Gestalt lovene](http://informatik-gym.dk/glossary/gestaltlove/)

Gestalt lovene er en række love opstilliet til interraktiondesign. 
Disse love beskriver hvordan at vi opfatter elementer i et design.
Lovene er altså med til at gøre det nemmere for brugeren at forstå og bruge it-systemerne.

- Til vores kontroller havde vi valgt at gøre det modsatte af gestalt lovene
- f.eks. til punkt 1(Nærhed) valgte at sige at vi ville sætte vores joystick og knap så langt fra hinanden på et stort stykke træ


- Vi skrev python koden færdig, så den tog vores output fra vores joystick og ændrede intervallet
- Efter at vi så connectede til en tello drone via. wifi, kunne vi så give den kommandoer

![Python](Images/Kode.png)

Vi nåede dog ikke at blive færdig med emnet og vores kontroller pga. corona, da vi skal blive hjemme og at det ikke er muligt at arbejde med den digitalt.
Det vi manglede at lave til vores kontroller var:

  1. Finpuds kode, så at dronen var mere stabil
  2. Selve kontrolleren, atlså det stykke træ hvor at vi ville sætte vores joystick og knapper på
  3. Brugerundersøgelse

## Privathed, sikkerhed og passwords

- Vi så "Snowden", en film der handler om Edward Snowden og overvågning

- Vi læste om [sikkerhed på nettet](https://informatik.systime.dk/?id=528) og snakkede om det på klassen

Bla. snakkede vi om hashing hvorpå at dit password bliver hashet så at man ikke kan knække password så nemt.
Der er også programmer som lastpass, som laver og gemmer passwords så at de er MEGET sværere at knække og på den måde er man mere sikker.

