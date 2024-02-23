# indian-raga-classifier
IRC - neural network to classify certain Indian Ragas

(What are indian ragas? Find out more about indian ragas at this link: https://en.wikipedia.org/wiki/Carnatic_raga)

We want to classify them based on a set of recordings that are passed in:

- Convert all of them to .wav
- get 30 second samples of each recording, balance it so that there are equal amount of samples for each recording (by creating pickle)
- gather all of the features based on those 30 second samples (also by creating pickle)
- create train and test split
- train and test on basic dense network using different feature pickles. (Each file is mapped to a certain feature)


What ragas are we classifying on? Well, I've provided sample audio recordings for 20 ragas, you can fork and modify to add new ragas or add more data into existing ragas:
The ragas I've included are:
- Surutti (https://en.wikipedia.org/wiki/Surutti)
- Bhairavi (https://en.wikipedia.org/wiki/Bhairavi_(Carnatic))
- Kamas	(https://en.wikipedia.org/wiki/Khamas_(raga))
- Madhyamavathi	(https://en.wikipedia.org/wiki/Madhyamavati)
- Shanmukhapriya (https://en.wikipedia.org/wiki/Shanmukhapriya)
- Bilahari (https://en.wikipedia.org/wiki/Bilahari)
- Kambhodhi	(https://en.wikipedia.org/wiki/Kambhoji)
- Mohanam (https://en.wikipedia.org/wiki/Mohanam)
- SindhuBhairavi (https://en.wikipedia.org/wiki/Sindhu_Bhairavi_(raga))
- Hamsadhwani (https://en.wikipedia.org/wiki/Hamsadhvani)
- Kapi (https://en.wikipedia.org/wiki/Kapi_(raga))
- PoorviKalyani (no wiki link, just know PoorviKalyani != Gamanashrama)
- Sri (https://en.wikipedia.org/wiki/Shree_(Carnatic_raga))
- Jaganmohini (no wiki link)
- Keeravani (https://en.wikipedia.org/wiki/Keeravani)
- Reethigowla (https://en.wikipedia.org/wiki/Reetigowla)
- Kalyani (https://en.wikipedia.org/wiki/Kalyani_(raga))
- Kharaharapriya (https://en.wikipedia.org/wiki/Kharaharapriya)
- Sankarabaranam (https://en.wikipedia.org/wiki/Sankarabharanam_(raga))
- Thodi (https://en.wikipedia.org/wiki/Hanumatodi)