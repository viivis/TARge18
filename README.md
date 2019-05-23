# TARge18
# Kangelased
Agentuuril on nimekiri kangelastest, milles on lisaks nende nimedele ka asukoht. Faili igal real on ühe kangelase andmed järgmises formaadis, näiteks:
Superman* / London
Batman / Tokyo
Spiderman / Los Angeles
Kangelaste hulgas võib olla superkangelasi, mis siis on märgitud tärniga nime järel.
1.	Klassis Kangelane privaatsed isendiväljad järgmise info jaoks: nimi (String), asukoht (String). Klassis on vähemalt üks konstruktor.
Klassis on vähemalt järgmised meetodid.
•	Kõigi isendiväljade jaoks on vastavad get-meetodid ja set-meetodid.
•	Meetod päästa (int-tüüpi), mille argumendiks on ohus olevate inimeste arv (int). Meetod tagastab päästetud inimeste arvu, mis on ohus olevate inimeste arvust 95 protsenti (ümardatuna täisarvuks).
•	On ka meetod toString, mis võimaldab kangelast mõistlikult ekraanil kujutada.

2.	Klass SuperKangelane on klassi Kangelane alamklass. Ülemklassis olemasolevaid isendivälju siin uuesti mitte kirjeldada. Klassis SuperKangelane on veel isendiväli osavuse kohta (double), mis kõigub vahemikus (1-5).
Klassis on vähemalt üks konstruktor, mis muuhulgas määrab juhuslikult superkangelase osavuse.
Klassis on vähemalt järgmised meetodid:
•	Meetod päästa kaetakse üle nii, et meetod tagastab päästetud inimeste arvu, mis on ohus olevate inimeste arvust (95 + osavus) protsenti (ümardatuna täisarvuks).
•	Meetodi toString ülekatmisel on rakendatud ülemklassi meetodit toString lisades osavuse väljastamise.

3.	Peaklassis on vähemalt järgmised muutujad ja meetodid:
•	Staatiline muutuja kangelaste listi jaoks.
•	Staatiline (void-tüüpi) meetod, mis loeb argumendina antud failist kangelaste andmed. Nende andmete põhjal luuakse klasside Kangelane ja SuperKangelane isendid. (Superkangelasel on tärn nime järel.) Vastavalt täidetakse ka kangelaste list.

4.	Peameetodis tehakse järgmised tegevused.
•	Rakendatakse eelmist meetodit selleks, et täita kangelaste list failis olevate andmete põhjal.
•	Vähemalt ühe „tavalise“ kangelase ja ühe superkangelase puhul rakendatakse meetodit päästa.
•	Sobivates kohtades näidata isendite infot ja meetodite töö tulemusi ekraanil.
