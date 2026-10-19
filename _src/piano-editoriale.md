# Piano editoriale Micio Design

Regole per chi scrive (persona o sistema automatico):

- Ogni articolo va in `_src/content/articoli/AAAA-MM-GG-slug.md` con front matter: title, slug, category, date, description, (pillar: true solo per i pilastri), image e image_png se c'è un'illustrazione in `_src/static/img/`.
- Tipi: A = confronto prodotti (5-8 prodotti reali, tabella con prezzo indicativo e data, pro/contro, un consiglio chiaro, link Amazon.it di ricerca o prodotto); P = problema risolto passo per passo; I = informativo.
- Lunghezza: A e P 1.200-1.800 parole, I 900-1.400. Tono: pratico, diretto, niente elenchi di virtù, niente consigli medici (dove serve il veterinario, dirlo e basta).
- Ogni articolo linka il pilastro della sua categoria e almeno un altro articolo del sito; i link Amazon usano `https://www.amazon.it/s?k=...` o il link prodotto; il builder aggiunge il tag affiliato quando configurato.
- Illustrazione: per ogni articolo di tipo A o P creare un SVG schematico 1200x700 nello stile dei pilastri (palette: #fbfaf7 fondo, #24201b inchiostro, #c2651d ambra, #4e7a66 salvia, #e7e2d9 linee; font Outfit) e il PNG corrispondente.
- Dopo la scrittura: `python3 _src/build.py`, controllo link interni, commit e push su main. Aggiornare lo stato qui sotto.

Stato: [ ] da scrivere · [x] pubblicato

## Pilastri (G)

- [x] 1 Lettiera per gatti in appartamento: la guida completa · lettiera · 2026-10-17
- [x] 2 Mensole, tiragraffi e percorsi · spazio-verticale · 2026-10-18
- [x] 3 Balcone e finestre a prova di gatto · balcone-e-finestre · 2026-10-18
- [x] 4 Il gatto d'appartamento felice: acqua, cibo, gioco e routine · vita-quotidiana · 2026-10-19
- [x] 5 Gatto e casa: piante, bambini, altri animali · convivenze · 2026-10-19
- [x] 6 Arredare e pulire una casa con gatti · arredo-e-pulizia · 2026-10-20

## Razze in appartamento (2 a settimana dalla settimana 3, in aggiunta alla coda)

Nuova categoria `razze` da aggiungere in config.json (nome "Razze in appartamento", intro: come vive ciascuna razza in casa). Ogni scheda, tipo I, 900-1.200 parole: carattere in casa, spazio verticale richiesto, bisogno di gioco e compagnia, pelo e pulizia, adatta a monolocale sì/no, con cosa attrezzare la casa, link alle guide. Niente salute né prezzi dei cuccioli. Illustrazione: silhouette della razza nello stile del sito finché non arriva la foto Wikimedia (con riga di attribuzione obbligatoria: autore, Wikimedia Commons, licenza).

- [ ] R1 Maine Coon in appartamento: spazio, mensole e gioco per un gigante
- [ ] R2 Il gatto europeo (soriano) in casa: il più adattabile di tutti
- [ ] R3 Siamese in appartamento: compagnia, voce e noia
- [ ] R4 Britannico a pelo corto: il gatto da divano che ha bisogno di muoversi
- [ ] R5 Persiano in casa: pelo, spazi bassi e routine
- [ ] R6 Ragdoll in appartamento: il gatto da interno per definizione
- [ ] R7 Bengala in casa: energia, altezza e arricchimento
- [ ] R8 Sacro di Birmania in appartamento
- [ ] R9 Norvegese delle foreste: un arrampicatore in casa
- [ ] R10 Scottish Fold in appartamento
- [ ] R11 Sphynx in casa: caldo, pulizia e compagnia
- [ ] R12 Abissino in appartamento: il gatto che non sta mai fermo
- [ ] R13 Certosino in casa
- [ ] R14 Siberiano in appartamento

## Coda, in ordine di pubblicazione (5 a settimana)

- [x] 7 A Le migliori lettiere autopulenti del 2026 · lettiera · 2026-10-20
- [x] 8 A Lettiere chiuse: le 7 migliori e come scegliere · lettiera · 2026-10-21
- [x] 14 A I migliori tiragraffi alti e stabili · spazio-verticale · 2026-10-22
- [x] 21 A Rete per gatti sul balcone: le migliori e come montarla · balcone-e-finestre · 2026-10-23
- [x] 27 A Le migliori fontanelle per gatti silenziose · vita-quotidiana · 2026-10-24
- [ ] 9 A Lettiere per gatti grandi e Maine Coon · lettiera
- [ ] 10 A Sabbia agglomerante, vegetale o silicio: quale conviene · lettiera
- [ ] 16 P Mensole per gatti a parete: misure, distanze, montaggio · spazio-verticale
- [ ] 22 P Rete balcone senza forare: sistemi a pressione e a morsetto · balcone-e-finestre
- [ ] 29 A Distributori automatici di cibo: i migliori per gatti · vita-quotidiana
- [ ] 11 P Dove mettere la lettiera in un bilocale · lettiera
- [ ] 12 P Il gatto fa i bisogni fuori dalla lettiera: le 9 cause · lettiera
- [ ] 15 A Tiragraffi per gatti grandi: cosa deve avere · spazio-verticale
- [ ] 23 P Finestra a vasistas: il pericolo per i gatti e le protezioni · balcone-e-finestre
- [ ] 31 A Giochi intelligenti e puzzle alimentari: i migliori · vita-quotidiana
- [ ] 13 A Mobili copri-lettiera: i migliori e come arieggiarli · lettiera
- [ ] 17 A Alberi per gatti da soffitto: i migliori a pressione · spazio-verticale
- [ ] 24 P Come costruire un catio sul balcone · balcone-e-finestre
- [ ] 28 P Il gatto beve poco: 8 modi per farlo bere di più · vita-quotidiana
- [ ] 37 I Piante tossiche per gatti: l'elenco completo · convivenze
- [ ] 18 P Il gatto non usa il tiragraffi: come convincerlo · spazio-verticale
- [ ] 25 A Zanzariere a prova di gatto · balcone-e-finestre
- [ ] 32 P Gatto annoiato in casa: 15 idee che funzionano · vita-quotidiana
- [ ] 38 I Piante sicure per gatti: 25 specie da tenere in casa · convivenze
- [ ] 44 A Divani a prova di gatto: tessuti che resistono · arredo-e-pulizia
- [ ] 19 P Percorsi per gatti in una casa in affitto, senza forare · spazio-verticale
- [ ] 26 A Gatto sul balcone d'inverno: cucce e ripari · balcone-e-finestre
- [ ] 33 I Giocare col gatto: quanto, quando e con cosa · vita-quotidiana
- [ ] 39 I Gatto e neonato in casa: come preparare l'arrivo · convivenze
- [ ] 45 P Il gatto graffia il divano: cosa fare davvero · arredo-e-pulizia
- [ ] 20 A Amache da finestra: le migliori e quanto reggono · spazio-verticale
- [ ] 30 A Ciotole rialzate e antiscivolo: servono davvero · vita-quotidiana
- [ ] 34 P Il gatto miagola di notte: cause e soluzioni · vita-quotidiana
- [ ] 40 P Due gatti in appartamento: come farli andare d'accordo · convivenze
- [ ] 46 P Eliminare l'odore di pipì di gatto da divano, materasso e pavimento · arredo-e-pulizia
- [ ] 35 A Telecamere per gatti: le migliori per vederlo da fuori · vita-quotidiana
- [ ] 36 I Lasciare il gatto solo: per quanto e come organizzarsi · vita-quotidiana
- [ ] 41 P Gatto e cane in casa: l'inserimento passo per passo · convivenze
- [ ] 47 A I migliori aspirapolvere per peli di gatto · arredo-e-pulizia
- [ ] 48 A Robot aspirapolvere e gatti: quali funzionano · arredo-e-pulizia
- [ ] 42 I Un secondo gatto: quando sì e quando no · convivenze
- [ ] 43 I Gatto e ospiti: il gatto che si nasconde · convivenze
- [ ] 49 A Peli ovunque: spazzole, rulli e routine · arredo-e-pulizia
- [ ] 50 P Tende e gatti: come salvarle · arredo-e-pulizia
- [ ] 51 A Il miglior trasportino per gatti (e come farglielo amare) · vita-quotidiana
- [ ] 52 A Zaini per gatti: i migliori e quando usarli · vita-quotidiana
- [ ] 53 I Gatto in auto per lunghi viaggi · vita-quotidiana
- [ ] 54 I Vacanze: cat sitter, pensione o gatto a casa · vita-quotidiana
- [ ] 55 A Cucce riscaldate e lettini da termosifone · vita-quotidiana
- [ ] 56 A Tappetini refrigeranti: il gatto e il caldo · vita-quotidiana
- [ ] 57 I Il gatto dorme con me: pro, contro e igiene · vita-quotidiana
- [ ] 58 A GPS per gatti: ha senso in appartamento · vita-quotidiana
- [ ] 59 A Gattaiole con microchip per porta e finestra · balcone-e-finestre
- [ ] 60 I Casa nuova col gatto: il trasloco senza stress · vita-quotidiana
