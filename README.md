# javaharjutused
Java harjutused
Projektist:
Tegemist oleks programmiga, kuhu saaks lisada töötajate töötatud päevade vahemikud nt Mati oli tööl 10.09.2016-13.09.2016; 20.09.2016-29.09.2016 jne (tööpäevade arv on igal töötajal erinev + iga töötaja tööpäevade arv on ka iga kuu erinev) ning programm aitaks kokku arvutada mitu tööpäeva mingi töötaja tööl oli ja kui palju palka ta selle eest peaks saama. Erialaspetsiifilise infona on ilmselt kasulik defineerida töötatud aeg deployment'ina, sest töötajad lähevad nö. välislähetusele vastavalt vajadusele ning tööajana arvestatakse seda päeva, kui nad hakkavad välislähetusele minema kuni selle hetkeni kui nad tagasi jõuavad.
Oluline on siin märkida, et see, kes selle arvestusega tegeleb sisestab käsitsi programmi töötaja deployment'ile mineku kuupäeva ning tagasituleku kuupäeva - mõlemad päevad kuuluvad tasutatavate tööpäevade alla. Mõnel kuul toimub ühel töötajal mitu deployment'i ning sellisel juhul peaks programm vastavalt käesoleva kuu töötatud päevad ja töötasu kokku arvutama. Kuna võib juhtuda ka nii, et mõni kuu mõnel töötajal pole ühtegi deploymen'ti, siis võiks nt kuu lõpus saada programmilt väljavõte, kes eelmisel kuul tööl olid ning kui palju nende töötasu peaks olema.
Sisestamise üks eripära on aga see, et deployment'i algus lisatakse kohe kui keegi tööle läheb ning lõpetatakse siis, kui ta tagasi tuleb (sest see pole sageli ette teada). Seetõttu tekib küsimus, kuidas oleks võimalik jätta kellegi staatust nö "veel tööl" vms, et programm teaks töötasu osas arvestada - juhul kui keegi on kuu vahetumise hetkel tööl ning tema kohta pole deployment'i lõpetamise märget programmis.
Võiks saada nt tellida kokkuvõtet, kes on käesoleval kuul tööl olnud, mitu päeva ning mis töötasu kokku tuleb.
Kui see on lihtne, siis kindlasti saaks sinna vajaliku funktsionaalsuseid juurde mõelda (nt kuna see inimene, kes töötasusid arvestab on vahelüli kliendi ja töötaja vahel, siis vastavalt töötasule võiks programm koostada arve eelneval kuul töötatud tundide eest, nt koondarvena või eraldi arvetena).
