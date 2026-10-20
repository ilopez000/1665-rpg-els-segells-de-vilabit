# Els Segells de Vilabit

Videojoc RPG en **català i castellà** per aprendre el **RA2 · Tecnologies habilitadores digitals (THD)** del mòdul **1665 Digitalització aplicada als sectors productius** (CFGS, PratFP).

L'alumne recorre el poble de Vilabit, parla amb els veïns, llegeix les 11 fitxes de les THD i els cartells de teoria, i supera una prova per cada criteri d'avaluació (CA 2.1 a 2.7) per aconseguir set segells. Al final s'enfronta a en Fum, un venedor de «tecnologia miraculosa», en un debat. En acabar, descarrega un **informe PDF** amb el seu desempeny.

## Com es juga

- A la portada es tria l'idioma (Català / Castellano); durant la partida, el botó ES/CA de la barra superior el canvia. La partida i l'informe PDF segueixen l'idioma triat.
- Fletxes o WASD per moure's, Espai per parlar i mirar objectes.
- C obre el Còdex; Q, les missions (i el botó de l'informe PDF en acabar).
- En mòbil apareixen una creu de direccions i el botó A.
- La partida es desa al navegador de cada alumne.

## Tècnic

- Un sol fitxer `index.html`: HTML, CSS i JavaScript sense dependències de compilació.
- El PDF es genera amb jsPDF 2.5.1 (cdnjs) i les fonts són de Google Fonts: cal connexió a Internet.
- Desplegament: Cloudflare Pages, sense ordre de compilació i amb el directori arrel com a sortida.
