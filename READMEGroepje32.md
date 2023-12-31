ReadMe-bestand: Onderzoek naar de Evolutie van het Woord 'Neger' in Literatuur

Onderzoeksvraag

"Hoe is de context en het gebruik van het woord 'neger' in literatuur geëvolueerd in boeken gepubliceerd vóór en na de 21e eeuw, en welke veranderingen in betekenis en connotatie kunnen worden waargenomen?"

Deze aangepaste onderzoeksvraag richt zich niet alleen op de frequentie van het woord 'neger' in teksten, maar ook op de context waarin het woord wordt gebruikt en hoe die context in de loop van de tijd is veranderd. We zouden bijvoorbeeld kunnen onderzoeken welke soorten zinnen of passages het woord 'neger' bevatten, welke emoties of associaties erbij horen, en of er veranderingen zijn opgetreden in de manier waarop het woord wordt begrepen en geïnterpreteerd.

Dataset

Bronnen

We zullen Nederlandstalige boeken gebruiken uit online bibliotheken. Enkele mogelijke bronnen zijn:

Google Books Ngram Viewer: Biedt frequentiegegevens van woorden in boeken.
Project Gutenberg: Biedt gratis toegang tot de volledige tekst van boeken.
Periode
We willen de periode vóór 2001 vergelijken met de periode na 2001. Deze keuze is gebaseerd op de suggestie uit 2001 om het woord 'neger' uit het woordenboek te schrappen en de daaropvolgende discussie over het strafbaar stellen van het gebruik ervan.

Taakverdeling

Pablo: Code schrijven voor het vinden van associaties.

Maria: Opmaak bestand, onderbouwen van onderzoek en alles inleveren.

Lars: Woorden zoeken die een bepaalde emotie of associatie kunnen aantonen.

Finn: Code schrijven voor het vinden van het woord 'neger'.

Max: 10 teksten verzamelen van vóór 2001 & 10 teksten verzamelen van na 2001.


Pseudocode (ruw)

def count_specific_words(text, specific_words):
    text = text.translate(str.maketrans('', '', string.punctuation)).lower()
    
    words = text.split()

    word_count = {word: 0 for word in specific_words}
    
    for word in words:
        if word in word_count:
            word_count[word] += 1
    
    return word_count

text = "Dit is een voorbeeld van de tekst, ik zal hier een paar woorden in doen, pos1, pos4, Neger, neg2, neg5, neg5, neger. Neger"

woorden_neger = ["neger"]
woorden_positieve_associatie = ["pos1","pos2","pos3","pos4","pos5"]
woorden_negatieve_associatie = ["neg1","neg2","neg3","neg4","neg5"]

word_count_neger = count_specific_words(text, woorden_neger)
word_count_positive = count_specific_words(text, woorden_positieve_associatie)
word_count_negative = count_specific_words(text, woorden_negatieve_associatie)

for word, count in word_count_neger.items():
    print(f"Aantal keer '{word}' in tekst: {count}")
print()
for word, count in word_count_positive.items():
    print(f"Aantal keer '{word}' in tekst: {count}")
for word, count in word_count_negative.items():
    print(f"Aantal keer '{word}' in tekst: {count}")
    
Logboek

Week 1: Onderwerp bepaald, onderzoeksvraag opgesteld en bronnen gezocht.
Week 2: Datasetbronnen geïdentificeerd, periodekeuze onderbouwd, opmaak van het document gestart.
Week 3: Logboek en extra context toegevoegd, vragen aan docent gesteld.
Negatieve en Positieve Associaties

Negatieve Associatie

Slecht, Stom, Afschuwelijk, Ondraaglijk, Vervelend, Irritant, Onaangenaam, Onaantrekkelijk, Verschrikkelijk, Onbetrouwbaar.
Termen zoals 'Blank', 'Etniciteit', 'Exotisch', 'Gekleurd', 'Inlander', 'Halfbloed', 'Kaukasisch', 'Ontdekken', 'Oriëntaals', 'Ras', 'Slaaf' worden betwist.

Positieve Associatie

Liefde, Vrede, Glimlach, Hoop, Dankbaarheid, Succes, Vriendschap, Vrijheid, Creativiteit, Avontuur.
Specifieke aandacht voor respectvol taalgebruik in de geschiedenis van negers in de Verenigde Staten.

Dit ReadMe-bestand dient als leidraad voor ons onderzoek en wordt regelmatig bijgewerkt.
