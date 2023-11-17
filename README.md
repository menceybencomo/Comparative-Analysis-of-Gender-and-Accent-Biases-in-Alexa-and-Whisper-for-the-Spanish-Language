[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10152506.svg)](https://doi.org/10.5281/zenodo.10152506)



# Comparative Analysis of Gender and Accent Biases in Alexa and Whisper for the Spanish Language

This repository contains the data related to the article titled "Comparative Analysis of Gender and Accent Biases in Alexa and Whisper for the Spanish Language."

The data structure is created using [Pysondb](https://pypi.org/project/pysondb/) and has the following format:

```
{
   "data": [
      {
         "sentence": "...",
         "path": "...mp3",
         "gender": "...",
         "accents": "...",
         "status_mx": false,
         "status_es": false,
         "status_us": false,
         "outtext_mx": -1,
         "outtext_es": -1,
         "outtext_us": -1,
         "wer_mx": -1,
         "wer_es": -1,
         "wer_us": -1,
         "mer_mx": -1,
         "mer_es": -1,
         "mer_us": -1,
         "wil_mx": -1,
         "wil_es": -1,
         "wil_us": -1,
         "wip_mx": -1,
         "wip_es": -1,
         "wip_us": -1,
         "cer_mx": -1,
         "cer_es": -1,
         "cer_us": -1,
         "id": ...
      }
  ]
}
```

MX, ES, and US refer to the variations of Alexa for the Spanish language. In Whisper, the data is stored under MX.

Data processing was conducted for the three variants of Alexa and for the Base and Large-v2 models of Whisper. The data is categorized based on gender and accent.

The data used corresponds to version 14 of [Mozilla Common Voice.](https://commonvoice.mozilla.org)

The analyzed accents are as follows:
- **Central American**
- **Andean-Pacific:** Colombia, Peru, Ecuador, Western Bolivia, Andean Venezuela
- **Caribbean:** Cuba, Venezuela, Puerto Rico, Dominican Republic, Panama, Caribbean Colombia, Caribbean Mexico, Gulf Coast of Mexico
- **Chilean:** Chile, Cuyo
- **Northern Iberian Peninsula:** Asturias, Castilla y León, Cantabria, Basque Country, Aragon, La Rioja, Guadalajara, Cuenca
- **Central-Southern Iberian Peninsula**: Madrid, Toledo, Castilla-La Mancha
- **Southern Iberian Peninsula:** Andalusia, Extremadura, Murcia
- **Canary Islands**
- **Mexico**    
- **Rioplatense:** Argentina, Uruguay, Eastern Bolivia, Paraguay
