# Web Kryštůfka Robina

Šablona pro Czechitas workshop Tvořím web. Pull requests are welcome.

## Zjednodušení

Cílem návrhu je vytvořit pouze jednostránkovou verzi původního webu Kryštůfka Robina se zjednodušeným layoutem bez zbytečných komplikací. Účelem je, aby slečny na konci workshopu odcházeli s hotovou stránkou, ne rozdělaným polotovarem, a aby byly schopné vytvořit podobný web znovu samy.

## První návrh (Luděk)

**Demo:** http://krystufek.rolecek.cz

Berte to prosím jako první pokus, ze kterého lze vycházet při dalších diskuzích. Neberu to nutně jako finální produkt, i když si myslím, že i jako finální produkt by to bylo dostačující.

Při tvorbě jsem se snažil o vzhled jednoduchý na pochopení a vytvoření. Chtěl jsem, aby stránka obsahovala prvky, bez kterých se klidně obejde, když se nestihnou dodělat, ale které se dají přidat, ukázat a vysvětlit těm rychlejším, když jim zbyde čas.

-	**Menu** - Ponecháno z původního webu, i když na jednostránkové verzi nedává příliš smysl. Jde o praktický prvek, který je v nějaké podobě na každém webu a je myslím dobré, umět ho udělat.
-	**Float** - Oproti původnímu webu se nepoužívá pro layout (užitečné, ale příliš komplikované), ale jen pro umístění obrázků obtékaných textem. V sekci Kontakt je pak použit i clear, aby šlo vysvětlit, jak řešit "komplikace" s floatováním.
-	**Galerie** - Nepoužívá float, ale inline-block, aby se předcházelo případným problémům s různě vysokými obrázky. Na galerii lze vysvětlit počítání width, height, margin pomocí procent, aby obrázky vyšly přesně 3 na řádek a byly mezi nimi stejné rozestupy. (Procenta čeho to jsou? Šířky nadřazeného kontejneru.)
-	**Vizuální vylepšení** - Pro rychlejší lze na stránku přidat různá vizuální vylepšení, z nichž má slečna radost a přitom jde většinou o jeden řádek v CSS. Jedná se např. o přidání fontu z Google Fonts, rámečky a stíny kolem obrázků, kulaté okraje, zcela kruhový obrázek Kryštůfka Robina, pattern na pozadí, apod.

	Bez všech těchto vychytávek se web obejde a bude zcela funkční. Základem bude tvorba zjednodušeného webu, aby ho stihly všechny slečny dokončit, a následně ho lze vylepšovat a dělat krásnější.
