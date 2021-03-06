# okfnLocal
* [video](https://youtu.be/1o2NTBnw1rE)
repository for work I did matching [okfn/publicbodies](https://github.com/okfn/publicbodies) with Wikidata 
   * okfn/publicbodies/issues/116 [Updating and organizing contact data for public bodies in Sweden ](https://github.com/okfn/publicbodies/issues/116)
* [data/se.csv](https://github.com/okfn/publicbodies/blob/master/data/se.csv) is matched 
  * first version of matched file [public-se-csv.csv](https://github.com/salgo60/okfnLocal/blob/main/public-se-csv.csv)
  * added more fields from Wikidata to the file if you would like to link Wikidata /Wikipedia
    * WD svWikipedia url
    * WD Qnumber
    * WD Lsv = Wikidata Swedish Label
    * WD Len = Wikidata English Label
    * WD Dsv =. Wikidata Swedish Description
    * WD Den =. Wikidata English Description
    * WD e-postadress = Wikidata email [Property:P968](https://www.wikidata.org/wiki/Property:P968)
* WD telefonnummer = Wikidata phonenr [Property:P1329](https://www.wikidata.org/wiki/Property:P1329)
* WD organisationsnummer = Wikidata Swedish Orgnumber  - [Property:P6460](https://www.wikidata.org/wiki/Property:P6460) 
## See also
* Handlingar.se was [mentioned on Wikidata weekly](https://www.wikidata.org/wiki/Wikidata:Status_updates/2021_06_14)
* Needs feedback how you will handle identifiera for organisations see [Wikidata:Property_proposal/Handlingar.se](https://www.wikidata.org/wiki/Wikidata:Property_proposal/Handlingar.se)
  * **UPDATE** [no Wikidata property was created](https://www.wikidata.org/wiki/Wikidata:Property_proposal/Handlingar.se)
# Feedback 2021-06-14  on [data/se.csv](https://github.com/okfn/publicbodies/blob/master/data/se.csv)
Below of issues/questions. If easier for you we can report them as [GITHUB issues see example](https://github.com/salgo60/okfnLocal/issues?q=)
* 2021-06-14 1) you need unique identifiers for your items its much easier to track changes, report weeoea and we can have you as a Wikidata property
  * Maybe use the Wikidata Qnumber as an unique identifier?
* 2021-06-14 1-1) looks like you duplicate items maybe we should have a "same as" e.g. "se/region-gotland" and "se/region-gotland-(landsting)" 
* 2021-06-14 1-2) one way forward could be to use a free empty version of Wikidata called [Wikibase](https://wikiba.se/)  
you can set up an instance with 5 clicks on [WBstack](https://www.wbstack.com) you need a password for doing that that 

* 2021-06-14 2) Datainspektionen has changed name see Wikidata [Q1172261](https://www.wikidata.org/wiki/Q1172261)

* 2021-06-14 3) Wikidata match **not found** for below - I guess can be added to Wikidata if we want
  * 2021-06-14 3-1) "Forskningsr??det F Milj?? Arella N??ringar Och Samh"
    * 2021-06-14 3-1-1) "se/forskningsradet-f-miljo-arella-naringar-och-samh"
  * 2021-06-14 3-2) "Hyres Och Arrenden??mnden" 
    * 2021-06-14 3-2-1) "se/hyres-och-arrendenamnden-i-goteborg"
    * 2021-06-14 3-2-2) "se/hyres-och-arrendenamnden-i-jonkoping"
    * 2021-06-14 3-2-3) "se/hyres-och-arrendenamnden-i-linkoping"
    * 2021-06-14 3-2-4) "se/hyres-och-arrendenamnden-i-stockholm"
    * 2021-06-14 3-2-5) "se/hyres-och-arrendenamnden-i-sundsvall"
    * 2021-06-14 3-2-6) "se/hyres-och-arrendenamnden-i-umea"
    * 2021-06-14 3-2-7) "se/hyres-och-arrendenamnden-i-vasteras"
    * 2021-06-14 3-2-8) "se/hyres-och-arrendenamnen-i-malmo"
  * 2021-06-14 3-3) "se/forvaltningsratten-i-malmo-och-migrationsdomstol"

  * 2021-06-14 3-4) "K??rnavfallsfondens Styrelse"
  * 2021-06-14 3-5) "se/ersattningsnamnden" - >"Ers??ttningsn??mnden"
  * 2021-06-14 3-6) "Landstinget S??rmland"
  * 2021-06-14 3-7) "Landstinget V??stmanland"
  * 2021-06-14 3-8) "Region Gotland (landsting)" , "Region Halland (landsting)",
  * 2021-06-14 3-9) "Regionala Etikpr??vningsn??mnden I G??teborg", "Regionala Etikpr??vningsn??mnden I Link??ping"
  * 2021-06-14 3-9-1) Looks they dont exist see [Etikpr??vningsn??mnd](https://sv.wikipedia.org/wiki/Etikpr%C3%B6vningsn%C3%A4mnd)  substituted by [Etikpr??vningsmyndigheten](https://sv.wikipedia.org/wiki/Etikpr%C3%B6vningsmyndigheten)
  * 2021-06-14 3-10) "Postverkets Avvecklingsorganisation"
  * 2021-06-14 3-11) "K??rnavfallsfondens Styrelse"

* 2021-06-14 4) "Malm?? H??gskola"  -> "Malm?? Universitet" see [Wikidata](https://www.wikidata.org/wiki/Q977781) 
* 2021-06-14 5) "Malm?? stad" I guess a better name is "Malm?? kommun" see https://sv.wikipedia.org/wiki/Malm%C3%B6_kommun
* 2021-06-14 6) "Myndigheten f??r Internationella Adoptionsfr??gor" --> new name [MFoF](https://www.bvadopt.se/Adoption-Aktuellt-MIA-har-bytt-namn-till-MFoF_DXNI-862974_) - [WD Q10591748](https://www.wikidata.org/wiki/Q10591748)
* 2021-06-14 7) "Revisorsn??mnden" is called "Revisorsinspektionen" see https://sv.wikipedia.org/wiki/Revisorsinspektionen
* 2021-06-14 8) "se/sveriges-meteorologiska-o-hydrologiska-institut" maybe should be called "Sveriges meteorologiska och hydrologiska institut" or "SMHI"
* 2021-06-14 9) "trollhattans-stad" maybe better name "Trollh??ttans kommun" see https://sv.wikipedia.org/wiki/Trollh%C3%A4ttans_kommun
* 2021-06-14 10) "solna-stad" maybe add alias "solna kommun" see Wikidata https://www.wikidata.org/wiki/Q109010
* 2021-06-14 11) se/stockholms-lans-landsting I guess better name "Region Stockholm" see https://www.wikidata.org/wiki/Q3233188
* 2021-06-14 12) "V??sterbottens l??ns landsting" --> "Region V??sterbotten" see https://sv.wikipedia.org/wiki/Region_V%C3%A4sterbotten
* "Landstinget S??rmland" --> I guess [Q3232072](https://www.wikidata.org/wiki/Q3232072)
* "Landstinget V??stmanland" --> I guess [Q3232214](https://www.wikidata.org/wiki/Q3232214)
