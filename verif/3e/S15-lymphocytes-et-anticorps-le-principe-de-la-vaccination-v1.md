# Vérification 3e S15 — v1

- **Version :** v1 (relecture complète)
- **Date :** 2026-11-17
- **Séance :** 3e S15 — Lymphocytes et anticorps ; le principe de la vaccination
- **Commit vérifié :** edf45a9 (HEAD de main)
- **Rapport précédent comparé :** aucun pour S15
- **Documents lus :** fiche de cours, fiche prof, fiche de révision (.docx), diaporama (.pptx, notes comprises ; diapos 6, 7, 8 regardées en image).
- **Limite :** les sites www.who.int et www.santepubliquefrance.fr ne sont pas accessibles depuis la session de relecture (domaines non autorisés) ; les chiffres des cas d'usage n'ont donc pas pu être recontrôlés à la source. Ce qui est dit ci-dessous sur ces chiffres repose sur le tableau de sources de la fiche prof.

**Verdict : corrections nécessaires.** Une contradiction scientifique interne (cas 2 de Jenner vs règle de spécificité), deux questions soulevées mais non expliquées, et un cours nettement plus court que la pilote.

## Métriques de longueur

| Séance | A | B | C | D | E (retour) | Total cours | Pages fiche de cours | Mots fiche prof | Diapos |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3e S06 (pilote) | 160 | 99 | 103 | 147 | 123 | 632 | 4 | 4276 | 12 |
| 3e S13 | 61 | 98 | 90 | 78 | 131 | 458 | 3 | 2831 | 12 |
| 3e S14 | 57 | 90 | 63 | 41 | 125 | 376 | 3 | 2774 | 12 |
| **3e S15** | 56 | 66 | 78 | 75 | 123 | **398** | 3 | 2933 | 12 |

Total S15 : −37 % par rapport à S06. Partie B : −33 % (66 vs 99). Partie A : −65 %, mais c'est un rappel, ce qui se justifie. Fiche prof : −31 %. La baisse est déjà acquise en S13-S14 (S15 est stable par rapport à S14 : +6 %).

## Erreurs (bloquantes)

- [ ] **Jenner : la mémoire « du même microbe » est contredite (nouveau).** Fiche de cours, parties C et E ; diapo 10 ; fiche prof (§5, §9). Citations : « [la mémoire immunitaire] ne protège que contre le même microbe » (C) ; « un anticorps ne reconnaît qu'un seul antigène » (B) ; puis (E) « Jenner a utilisé la variole bovine pour provoquer une réponse immunitaire : la mémoire immunitaire de James Phipps lui a permis de résister à la variole ». La variole bovine (virus de la vaccine/cowpox) n'est pas le virus de la variole humaine : l'enfant est protégé parce que les deux virus ont des antigènes très proches (protection croisée). Tel quel, un élève qui applique la règle du cours conclut que l'expérience de Jenner est impossible. Correction : ajouter en B/C que des virus très proches peuvent partager des antigènes semblables, et écrire en E « la variole bovine est due à un virus proche de celui de la variole : ses antigènes sont semblables, donc la mémoire créée protège aussi contre la variole ». Source à ajouter dans le tableau (non vérifiée ici) : OMS, « A Brief History of Vaccination » (https://www.who.int/news-room/spotlight/history-of-vaccination/a-brief-history-of-vaccination) ou un manuel.

## Points douteux

- [ ] **Sources « à recontrôler » utilisées dans la fiche élève (nouveau).** Fiche prof §12. Les lignes suivantes sont marquées « extraits de recherche : à recontrôler » alors que les faits figurent dans la fiche de cours : exposition à la variole deux mois plus tard (cas 2), éradication déclarée en 1980, origine « vacca ». Règle du dépôt : ce qui n'est pas vérifié est retiré ou reformulé. À faire : lire la page OMS (ou Britannica/PMC) et passer la ligne en « page lue ». Ces faits sont par ailleurs très probablement exacts (connaissance générale : inoculation à Phipps le 14 mai 1796, exposition en juillet 1796, éradication déclarée en 1980) ; je n'ai pas pu le confirmer en ligne.
- [ ] **« plus d'anticorps, produits plus vite » (partie C) : source « à recontrôler » (nouveau).** Fiche prof §12. Le fait est exact (réponse secondaire plus rapide et plus intense), mais l'extrait MSD lu dit seulement « rapide et très efficace ». Lire une source qui dit explicitement « plus intense ».
- [ ] **Chiffre 90,4 % : population à préciser (nouveau).** Cas 1 : « chez les adultes de 18 à 35 ans, elle est estimée à 90,4 % (2021) » juste après « 95 % avec deux doses ». Le texte laisse croire que 90,4 % est une couverture à deux doses ; la fiche prof dit « baromètre 2021 » sans préciser le nombre de doses. Vérifier la page Santé publique France (non accessible ici) et indiquer « au moins une dose » ou « deux doses » selon la source, sans quoi la comparaison 90,4 / 95 est trompeuse.
- [ ] **« est protégée avant de tomber malade » (D, E) trop absolu (nouveau).** Aucun vaccin ne protège à 100 % ; la fiche prof cite elle-même 90 à 95 % de pouvoir protecteur (Vaccination Info Service). Proposer : « est le plus souvent protégée ». Cela justifie aussi la deuxième dose (voir Incohérences).
- [ ] **Diapo 8, étape 3 (nouveau).** Les anticorps et le microbe sont dessinés côte à côte sans liaison, tandis que le texte dit « réponse rapide, protection ». Le schéma n'est pas faux mais ne montre pas la fixation de l'anticorps sur l'antigène du microbe, pourtant l'idée centrale. Ajouter, au clic 3, les anticorps accolés aux antigènes du microbe.
- [ ] **Diapo 7, courbe (nouveau).** Au 2e contact la courbe repart d'un niveau d'anticorps non nul : cohérent avec la décroissance mais pas expliqué ; la fiche prof dit « schéma qualitatif ». Les cellules mémoire, notion clé du schéma, n'y apparaissent pas : à indiquer en légende pour relier courbe et texte C.
- [ ] **Lymphocyte B « produit » les anticorps (B ; diapo 6).** Simplification acceptable au collège (les anticorps sont sécrétés par les plasmocytes, issus des lymphocytes B) ; signalée dans la fiche prof (« ni les plasmocytes »). Pas de correction obligatoire. Même remarque : « les lymphocytes T détruisent les cellules infectées » ne vaut que pour les T cytotoxiques (le tableau de sources dit « T Killer ») ; formulation « certains lymphocytes T » plus exacte.

## Incohérences

- [ ] **Question « pourquoi deux doses ? » posée, non expliquée (nouveau).** Cas 1 et leur diapo 2 posent la question ; la fiche de cours dit seulement « une seconde dose renforce cette réponse » (E) et « plusieurs doses ou des rappels sont nécessaires pour certains vaccins » (D). Manque : le mécanisme (la première dose crée la mémoire, la seconde est un second contact qui amplifie la réponse, comme sur la courbe de la partie C ; certains enfants ne répondent pas à la première dose). Lier explicitement la 2e dose à la courbe « 2e contact ».
- [ ] **« une couverture vaccinale élevée limite les cas » non expliqué (nouveau).** Fin du cas 1 en E. Notion de protection collective jamais introduite (ni couverture vaccinale définie). Ou retirer la phrase, ou ajouter une définition (« part de la population vaccinée ») et une ligne : un virus a plus de mal à circuler quand peu de personnes sont sensibles.
- [ ] **Partie D réduite à un résumé (75 mots) (nouveau).** Elle ne dit pas ce qu'est un vaccin inactivé vs atténué, ni pourquoi un vaccin ne provoque pas la maladie (microbe atténué/inactivé ou partie de microbe, incapable de se multiplier en provoquant la maladie). Un élève peut se demander pourquoi on s'injecte un microbe. Ajouter une phrase.
- [ ] **Baisse de longueur par rapport à la pilote (nouveau).** Cours total −37 % (398 vs 632 mots), fiche prof −31 %. Parties B (66 mots) et C (78) : une idée par paragraphe, peu de mécanisme. Ex. B ne dit pas comment un lymphocyte « devient » productif ni ce que signifie « marquer » (qui détruit ensuite l'antigène marqué : les phagocytes de S14, lien utile). C ne dit pas ce que sont les cellules mémoire en dehors de « gardent la trace de l'antigène ». Pas d'erreur, mais un cours moins développé que la pilote, comme le ressent l'utilisateur ; l'écart est installé depuis S13-S14.
- [ ] **Vocabulaire avec S13-S14 :** « microbe pathogène », « globules blancs », « phagocytes » repris à l'identique de S14 : cohérent. La partie A de S15 supprime « leucocyte » (défini en S14) : sans gravité. Aucun renvoi aux séances suivantes trouvé (diapo 1 : « quatrième séance », neutre).
- [ ] **Définition d'anticorps (fiche prof / révision).** « Substance produite par les lymphocytes B » : acceptable, mais le cours ne dit pas qu'il s'agit de protéines ; sans importance au collège.

## Ce qui est solide

Structure complète (cas, problématique, A à E, bilan à légender), vocabulaire cohérent avec S14, spécificité de l'anticorps et réponse lente/rapide correctes, courbe qualitative signalée comme telle, mention honnête dans la fiche prof des types de vaccins et de l'éthique de l'expérience de Jenner, exercice de type brevet conforme (3 questions croissantes, barème sur 10).
