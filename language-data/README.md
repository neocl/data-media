###Formats

The Kanji alive language data files (_ka_data_ and _japanese_radicals_) are offered in UTF-8 encoded, .csv (comma-delimited) and in Microsoft Excel (.xlsx) formats. 

###Kanji alive data (ka_data.csv and .xlsx)

This contains all of the langauge data used by the Kanji alive web application with the following exceptions: For copyright reasons, it does not include data on the mnemonic hints and the (Classic) Nelson and Kondansha dictionary indices for each kanji seen in the app's 'detail' view or data on the division of kanji into chapters/lessons for [textbooks supported](http://kanjialive.com/supported-textbooks/) in Kanji alive.

Note that in order to make use in particular of the [kanji animation](https://github.com/kintopp/Kanji-alive/tree/master/kanji-animations) and [example audio](https://github.com/kintopp/Kanji-alive/tree/master/examples-audio) media, you will need to match the kanji character you are looking for (e.g. ⻌) with the unique, romanized name we assigned to it when we created their filenames, e.g. jutsu-no(beru). In the case of the example audio files, the filenames were additionally marked (in alphabetical order) with the letters 'a' to 'l' to match them to their respective readings. For example, there are 10 audio files starting with "jutsu-no(beru)" and ending with [a-j].aac. These are the audio files for the 10 readings (in the same order) for this kanji.

Please note also that some of the radical characters in the spreadsheet are not defined in Unicode and had to be assigned PUA (private use area) encodings. To view these characters correctly, you will first have to install our custom [Japanese Radicals](https://github.com/kintopp/Kanji-alive/tree/master/radicals-font) font. 

###Radicals data (japanese_radicals.csv and .xlsx)

The data in _radicals_data_ is subsumed by and identical to that in _ka_data_ with two exceptions: The _radicals_data_ files include a listing the Unicode encoding of each radical and an indication of whether they belong to the category of the most important radicals and are therefore worth memorizing. This information is re-used on the [214 trandtional kanji radicals](http://kanjialive.com/214-traditional-kanji-radicals/) page on the Kanji alive website. 

As with _ka-data_, please note also that some of the radical characters in the spreadsheet are not defined in Unicode and had to be assigned PUA (private use area) encoding. To view these characters correctly, you will first have to install our custom [Japanese Radicals](https://github.com/kintopp/Kanji-alive/tree/master/radicals-font) font. 

###Data Provenance

None of the language data presented here draws on material from Jim Breen's [Electronic Dictionary Research and Development Group](http://www.edrdg.org), (i.e. JMDICT/EDICT, KANJIDIC and KRADFILE/RADKFILE). 

The language data on kanji was compiled by native Japanese instructors and graduate students at the University of Chicago, largely between 2002 and 2005 (see [Credits](http://kanjialive.com/credits/)) with reference, as needed, to Jack Halpern, "The Kodansha Kanji Learner’s Dictionary", 1st ed. 1999, Kodansha, and Andrew N. Nelson, "The Original Modern Reader’s Japanese-English Character Dictionary: Classic Edition", 2nd. ed. (1974), Tuttle Publishing. 

The language data on radicals draws on the following references: For the English meanings of each radical, "Kanji & Kana" by Wolfgang Hadamitzky & Mark Spahn, (1981), Tuttle Publishing with additional reference to "Basic Kanji" by Matsuo Soga & Michio Yusa (1989), Taishūkan, and Andrew N. Nelson, "The Original Modern Reader’s Japanese-English Character Dictionary: Classic Edition", 2nd. ed. (1974), Tuttle Publishing. For the Japanese names for the radicals,『講談社カラー版日本語大辞典』（第一版）1989, 講談社.

All of the language data in Kanji alive was carefully reviewed and revised by Harumi Lory in 2014-2015.