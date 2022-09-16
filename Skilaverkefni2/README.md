# FORR3CG - Skilaverkefni 2 (15%)

- **Verkefnið er einstaklingsverkefni.** Ef tveir eða fleiri nemendur skila sömu lausnunum er gefið 0 (núll) fyrir þær lausnir.
- **Ef kóði er tekinn af netinu** (eða öðrum álíka stöðum) skal taka það fram, benda á hvaðan hann kemur og skrifa skýringar (e. comment) við hverja línu kóðans. Sé það ekki gert verður gefið 0 (núll) fyrir verkefnið í heild.
- **Ekki er heimilt** að nota tilbúnar lausnir fyrir listaklasann eins og t.d. std::vector.

## Verkefnalýsing

Jarðskjálftar hafa verið tíðir á landinu að [undanförnu](https://www.vedur.is/skjalftar-og-eldgos/jardskjalftar/#view=table) (eins og oft áður) og hefur þú því ákveðið að skrifa forrit sem heldur utan um upplýsingar um jarðskjálfta.

Þær upplýsingar sem geyma þarf um hvern jarðskjálfta eru númer (id), textalýsing á staðsetningu hans, stærð hans á [Richterskvarðanum](https://is.wikipedia.org/wiki/Jarðskjálftakvarðar#Richterskvarðinn) og hversu djúpt í jarðskorpunni hann var mælt í kílómetrum. Dæmi um skráningu:

Hvað er skráð | Dæmi um skráningu | Mælieining
--- | --- | ---
Númer | 315 | 
Staðsetning | 10,3 km. NA af Grímsey. | 
Stærð | 3,1 | M<sub>L</sub>
Dýpi | 1,4 | km.

Þú þarft því að skrifa klasa sem inniheldur upplýsingar um einn jarðskjálfta. Útfærðu smiði, getters, setters og prenta fall. Það þarf að vera hægt að bera saman tvo jarðskjálfta þannig að þú þarft að útfæra samanburðarvirkjana (`==`, `!=`, `<`, `>`, `<=` og `>=`). Samanburðurinn byggir fyrst á stærð skjálftans og síðan dýpt hans. 

Skrifaðu svo annan klasa (listaklasa) sem heldur utan um upplýsingar um marga jarðskjálfta. Þessi klasi á að nota kviklegt fylki (e. dynamic array) til að geyma mörg tilvika af jarðskjálfta klasanum (**ATH.** þarf ekki að vera raðað). Upphafsstærð fylkisins skal vera fjögur stök og skal það svo stækka um átta stök í hvert sinn sem það þarf að stækka. Passa þarf upp á að endurnýta laus stök ef jarðskjálfta hefur verið eytt úr listanum. Skrifaðu smiði og eyði (e. destructor) eftir þörfum.

Það þarf að vera hægt að:

- Skrá jarðskjálfta í listann (bæði setja inn tilvik af jarðskjálftaklasanum og líka með því að setja inn upplýsingar um jarðskjálfta).
- Eyða jarðskjálfta úr listanum eftir númeri (id) hans.
- Uppfæra stærð jarðskjálfta út frá númeri (id) hans.
- Skrifa alla jarðskjálftana á skjá.
- Skrifa einn ákveðinn jarðskjálfta á skjá eftir númeri (id) hans.

Skrifaðu svo forrit sem sýnir notkun klasanna (ekki gleyma að sýna virkni samanburðarvikjanna), skráðu að lágmarki fimm jarðskjálfta í listann. Ekki þarf að huga neitt að villuprófunum. Ekki þarf að bregðast við tvískráningum. Öll gögn skal harðkóða.

Mundu að skipta klösunum upp í .h og .cpp skrár.

Skilið svo öllum skránum (ættu að vera tvær .h skrár og þrjár .cpp skrár) á Innu.
