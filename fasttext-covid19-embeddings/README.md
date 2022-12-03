
## COVID-19 embeddings trained with fastText

These embeddings were trained using [fastText](https://fasttext.cc/) with the following hyperparameters:

- SkipGram configuration
- Dimension of 100
- Minimum word frequency of 5
- Window size of 5
- Uncased (not distinguishing between uppercase and lowercase words)

Texts amount up to 6 million tokens, which were crawled from the following sources:

- [Agencia SINC](https://www.agenciasinc.es)
- [Agencia Española de Seguridad Alimentaria y Nutricion (AESAN)](https://www.aesan.gob.es)
- [Australian Government Department of Health](https://www.health.gov.au/resources/translated?f%255B0%255D=field_related_conditions_disease%3A9669&f%255B1%255D=field_language%3A2931&utm_source=health.gov.au&utm_medium=redirect&utm_campaign=digital_transformation&utm_content=resources/collections/coronavirus-covid-19-resources-in-hazaragi-azrgy&f%5B0%5D=field_language%3A681)
- [BIMCV-COVID19 project](https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/)
- [Canal Salud (Generalitat de Catalunya)](https://canalsalut.gencat.cat/ca/salut-a-z/c/covid-19/)
- [CIMA (AEMPS)](https://cima.aemps.es)
- [Cochrane](https://www.cochranelibrary.com/es/) and [Cochrane Evidencias COVID-19](https://es.cochrane.org/es/recursos/evidencias-covid-19)
- [Conprueba - Información sobre COVID-19](https://www.conprueba.es/covid-19)
- [Consejería de Salud de la Comunidad de Madrid](https://www.comunidad.madrid/centros/consejeria-sanidad)
- [Consejo Superior de Investigaciones Científicas (CSIC)](https://www.csic.es/es/palabras-clave/coronavirus)
- COVID-19 anonymized clinical records provided in shared tasks prepared by the [Text Mining Unit (Barcelona Supercomputing Center)](https://temu.bsc.es/)
- [Dpto. de Salud del Gobierno Vasco](https://www.euskadi.eus/coronavirus/)
- [European Medicines Agency (EMA)](https://www.ema.europa.eu/en/human-regulatory/overview/public-health-threats/coronavirus-disease-covid-19/covid-19-latest-updates)
- [En familia](https://enfamilia.aeped.es/search/content/covid-19)
- [Escuela de Salud de Murcia](https://www.escueladesaludmurcia.es), [Murcia Salud](http://www.murciasalud.es/pagina.php?id=473704&idsec=6694#) y [Preguntas Evidencia COVID-19 Murcia Salud](https://www.murciasalud.es/preevid.php?op=banco&tema=761&idsec=453) 
- [European Vaccination Information Portal](https://vaccination-info.eu/en/covid-19/covid-19-vaccines), [European Comision response to coronavirus](https://ec.europa.eu/info/live-work-travel-eu/coronavirus-response_es) and [EurLex (Public Health about COVID-19)](https://eur-lex.europa.eu/content/news/Covid19.html)
- [Food and Drug Administration (FDA) Agency](https://www.fda.gov/about-fda/fda-en-espanol/enfermedad-del-coronavirus-covid-19)
- [Fisterra](https://www.fisterra.com/guias-clinicas/covid-19/)
- [Gaceta Médica](https://gacetamedica.com/tag/covid-19/)
- [Generalitat Valenciana - Preguntas frecuentes sobre COVID-19](https://coronavirus.san.gva.es/es/preguntas-frecuentes)
- [Gobierno de Aragón - Información sobre COVID-19](https://www.aragon.es/coronavirus)
- [Gobierno de Navarra - Información sobre COVID-19](https://coronavirus.navarra.es/es/)
- [Islas Baleares - Información sobre COVID-19](https://www.caib.es/sites/covid-19/es/covid-19/?campa=yes)
- [Junta de Andalucía, Consejería de Salud](https://www.juntadeandalucia.es/institutodeestadisticaycartografia/salud/COVID19.html)
- [LatamChequea](https://chequeado.com/latamcoronavirus/)
- [Mayo Clinic](https://www.mayoclinic.org/es-es/diseases-conditions/coronavirus/symptoms-causes/syc-20479963)
- [MedLinePlus](https://medlineplus.gov/spanish/covid19coronavirusdisease2019.html)
- [Ministerio de Sanidad de España](https://www.sanidad.gob.es/) y [Estrategia de Vacunación COVID-19](https://www.sanidad.gob.es/profesionales/saludPublica/ccayes/alertasActual/nCov/vacunaCovid19.htm)
- [Ministerio de Salud de Chile](https://www.minsal.cl/)
- [National Institutes of Health (USA)](https://covid19.nih.gov/), including the [National Cancer Institute](https://www.cancer.gov/espanol/cancer/coronavirus)
- [North Carolina Dept. of Health and Human Services](https://covid19.ncdhhs.gov/)
- [Organización Panamericana de la Salud (PAHO)](https://www.paho.org/es/temas/coronavirus)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov)
- Clinical trials announcements about interventions for COVID-19 published in the [EU Clinical Trials Register (EudraCT)](https://www.clinicaltrialsregister.eu) and [Registro Español de Estudios Clínicos (REEC)](https://reec.aemps.es)
- [Red de Autoridades en Medicamentos de Iberoamérica (Secretaría General Iberoamericana)](https://www.segib.org/red-eami/)
- [Servicio de Salud de Castilla-La Mancha](https://sanidad.castillalamancha.es)
- [The Conversation](https://theconversation.com/es/covid-19)
- [Tu otro médico](https://www.tuotromedico.com/temas/infeccion-coronavirus.htm)
- Twits related to COVID-19 from the [ProfNER Shared Task](https://temu.bsc.es/smm4h-spanish/)
- [UNICEF](https://www.unicef.org/es/coronavirus/covid-19)
- [United Nations](https://www.un.org/en/coronavirus)
- [US Department of Veterans Affairs](https://www.va.gov/search/?query=COVID-19&t=false&submit.x=48&submit.y=15)
- [World Health Organization](https://covid19.who.int/)
- [Wikipedia](https://es.wikipedia.org/wiki/Categor%C3%ADa:COVID-199)
- [Wikinews COVID-19](https://es.wikinews.org/wiki/Categor%C3%ADa:Pandemia_de_enfermedad_por_COVID-19)

If you use this resource, please cite as follows:

```
  @article{campillos2022,   
  title       = {MedLexSp – A Medical Lexicon for Spanish Medical Natural Language Processing},  
  author       = {Campillos-Llanos, Leonardo},   
  journal = {Journal of Biomedical Semantics},
  note = {\url{https://doi.org/10.20350/digitalCSIC/14656}},
  year      = {2022}
  }
```




