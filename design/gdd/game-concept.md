# Game Concept: Ressac

*Created: 2026-11-10*
*Status: Draft*

> Titre retenu : « Ressac ». Le 2026-11-10, la recherche du magasin Steam ne
> renvoyait aucun résultat pour ce nom et la première page d'itch.io aucun titre
> identique. Les marques déposées (INPI, EUIPO) n'ont pas été vérifiées.
> Alternative gardée en réserve : *Les Feux du Ressac*.
>
> Les titres de sections sont en anglais parce que les commandes du studio les
> recherchent par leur nom. Le contenu est en français.

---

## Elevator Pitch

> C'est un jeu de vie et d'exploration où l'on échoue sur un archipel dont la
> marée découvre et recouvre des lieux entiers. On y survit, on s'installe près
> d'un village de pêcheurs coupé du monde, on se lie à ses habitants et l'on
> rallume les phares un à un pour percer le mystère de l'archipel.

---

## Core Identity

| Aspect | Detail |
| ---- | ---- |
| **Genre** | Simulation de vie et exploration, avec une ouverture de survie |
| **Platform** | PC (Steam), clavier-souris et manette |
| **Target Audience** | L'explorateur qui aime s'installer (voir Target Player Profile) |
| **Player Count** | Solo |
| **Session Length** | 30 à 120 minutes |
| **Monetization** | Premium (achat unique) |
| **Estimated Scope** | Large (24–30 mois, solo) |
| **Comparable Titles** | Stardew Valley, Moonstone Island, Core Keeper, Mayday: The Survival Island. Chiffres et sources : voir Market Risks |

---

## Core Fantasy

Bâtir une vie sur un archipel que la mer redessine chaque jour. Le joueur arrive
sans rien, apprend à lire les marées, se fait une place dans un village, voit sa
maison et ses compétences grandir avec ce qu'il fait, et s'attache à des
habitants qui ont chacun un métier, un caractère et une histoire.

La promesse : un chez-soi qui s'améliore, entouré de gens qu'on a envie de
retrouver, au bord d'un monde qui réserve toujours un lieu de plus à découvrir
quand l'eau se retire.

---

## Unique Hook

C'est comme Stardew Valley ou Moonstone Island, **et en plus des lieux entiers
apparaissent et disparaissent avec la marée**.

Sur chaque île, quelques lieux dessinés à la main s'ouvrent à marée basse et se
ferment à marée haute : une chaussée vers un îlot, un banc de sable, une grotte,
une épave, les parcs de l'estran. Le joueur voit l'eau se retirer et découvrir
le lieu. Un almanach annonce les horaires, y compris les grandes marées qui
ouvrent des lieux rares quelques jours par saison.

La marée touche le jeu et pas seulement le décor : elle décide où aller et
quand, elle porte une part de l'économie (sel, algues, huîtres) et elle donne à
chaque île un comportement propre.

**Trois constructions ont été comparées :**

| Option | Principe | Décision |
| ---- | ---- | ---- |
| Marée continue | L'eau monte case par case sur toutes les côtes | Écartée : chaque carte demande ses altitudes, tout le littoral est à tester, le joueur peut être coincé partout |
| **Marée par zones** | Trois états de mer ; des lieux précis s'ouvrent et se ferment | **Retenue** : garde le spectacle, supprime la contrainte, bien moins coûteuse |
| Marée par jour | L'état de la mer est fixé pour la journée | Écartée : la moins marquante, on perd le rythme dans la journée |

---

## Player Experience Analysis (MDA Framework)

### Target Aesthetics (What the player FEELS)

| Aesthetic | Priority | How We Deliver It |
| ---- | ---- | ---- |
| **Submission** (relaxation, comfort zone) | 1 | Rythme posé, gestes tactiles, confort acquis pour de bon, histoire sans échéance |
| **Discovery** (exploration, secrets) | 2 | Lieux de marée, îles distinctes, grandes marées, journal de l'archipel |
| **Fellowship** (social connection) | 3 | Habitants marquants, scènes d'amitié, anniversaires, fêtes du calendrier. Lien avec des personnages, le jeu étant solo |
| **Fantasy** (make-believe, role-playing) | 4 | Le naufragé qui devient un habitant de l'archipel |
| **Expression** (self-expression, creativity) | 5 | Maison et base aménagées, choix de ses activités |
| **Narrative** (drama, story arc) | 6 | Le mystère des phares éteints, les histoires des habitants |
| **Sensation** (sensory pleasure) | 7 | Le sec et le mouillé, la lumière, le retour à l'écran de chaque geste |
| **Challenge** (obstacle course, mastery) | 8 | Survie exigeante la première heure ou deux, marée à anticiper. Volontairement léger |

### Key Dynamics (Emergent player behaviors)

- Le joueur consulte l'almanach et organise sa journée autour des marées.
- Il alterne les activités selon la saison et la marée au lieu d'en répéter une seule.
- Il rend visite aux habitants par envie, pas par obligation, et note leurs goûts et leurs anniversaires.
- Il prépare ses sorties vers les îles lointaines : vivres, vêtements, horaire de retour.
- Il laisse l'histoire de côté quand il veut, sans rien perdre.

### Core Mechanics (Systems we build)

1. **Marée par zones et almanach** : trois états de mer (haute, basse, grande marée), lieux qui s'ouvrent et se ferment, horaires prévisibles.
2. **Temps et calendrier** : journée avec heure limite, saisons, années qui passent, événements à dates fixes, anniversaires.
3. **Récolte, artisanat et économie variée** : cueillette, estran, ferme, pêche, machines de transformation, marché.
4. **Compétences par la pratique** : chaque activité fait progresser sa compétence, par la variété des actions.
5. **Habitants et relations** : métier, emploi du temps, goûts, paliers d'amitié avec scènes.
6. **Survie adoucie** : faim, soif, énergie, froid ; exigeante au début, allégée par ce que le joueur construit.
7. **Navigation et îles** : radeau puis bateau, cinq îles distinctes, phares à rallumer.

---

## Player Motivation Profile

### Primary Psychological Needs Served

| Need | How This Game Satisfies It | Strength |
| ---- | ---- | ---- |
| **Autonomy** (freedom, meaningful choice) | Plusieurs activités font vivre le joueur, chaque objectif s'atteint de plusieurs façons, l'histoire n'a pas d'échéance | Core |
| **Competence** (mastery, skill growth) | Compétences qui montent par la pratique, lecture des marées, maison et outils améliorés | Supporting |
| **Relatedness** (connection, belonging) | Habitants marquants, scènes d'amitié, aide accrue à l'amitié maximale, vie de village | Core |

### Player Type Appeal (Bartle Taxonomy)

- [x] **Achievers** (goal completion, collection, progression) — How: compétences, journal de l'archipel, maison, phares rallumés
- [x] **Explorers** (discovery, understanding systems, finding secrets) — How: lieux de marée, îles, grandes marées, secrets. Type principal
- [x] **Socializers** (relationships, cooperation, community) — How: relations avec les habitants, fêtes, anniversaires
- [ ] **Killers/Competitors** (domination, PvP, leaderboards) — How: non servi. Ni combat ni classement dans la 1.0

**Pas pour** : les joueurs qui cherchent un jeu de combat exigeant, une survie impitoyable ou du multijoueur.

### Flow State Design

- **Onboarding curve** : le naufrage enseigne les gestes un par un (ramasser, boire, faire un feu, s'abriter). La première marée basse montre le banc de sable et l'épave.
- **Difficulty scaling** : la pression de la survie baisse à mesure que le joueur s'installe. L'effort se déplace vers la préparation des sorties lointaines.
- **Feedback clarity** : compétences qui montent à l'écran, almanach qui confirme les prévisions, habitants qui réagissent aux progrès, village qui se repeuple.
- **Recovery from failure** : ni mort définitive ni perte totale. Être surpris par la marée coûte de l'énergie et une partie de ce qu'on a ramassé dans ce lieu pendant cette marée ; dépasser l'heure limite coûte de l'énergie le lendemain. On repart le lendemain.

---

## Core Loop

### Moment-to-Moment (30 seconds)

Un geste posé et tactile : couper, cueillir, creuser l'estran, lancer la ligne.
Chaque geste a son animation, son bruit, ses particules et un léger retour à
l'écran. Il nourrit deux choses à la fois : l'inventaire et la compétence
correspondante. Le rythme est un peu plus vif en exploration.

### Short-Term (5-15 minutes)

**Une marée.** L'eau se retire, le joueur part sur le banc de sable, dans la
grotte ou l'épave chercher ce qu'on ne trouve que là, puis rentre avant la
fermeture, annoncée par une cloche et par l'écume. S'il reste, il est ramené au
rivage et perd de l'énergie ainsi qu'une partie de ce qu'il a ramassé dans ce
lieu pendant cette marée. C'est ici que naît le « encore une marée ».

### Session-Level (30-120 minutes)

**Quelques journées.** Chaque journée compte deux marées, puis un temps calme :
transformer (fumoir, saline), vendre, parler aux habitants, aménager la maison.
Passé une heure très tardive, le joueur est ramené chez lui de force avec une
petite pénalité, ce qui donne du tonus à la fin de journée. Dormir sauvegarde et
marque un point d'arrêt naturel.

**Le calendrier cadre les journées.**

- La date s'affiche et les années passent.
- Les îles évoluent avec les saisons : ressources, faune et paysages changent.
- Les événements tombent à dates fixes et font gagner de l'affection auprès des habitants. En manquer un ne fait jamais perdre d'affection : ce sont des occasions, pas des obligations.
- Chaque habitant a son anniversaire, le joueur aussi, avec d'autres dates personnelles du même ordre.

### Long-Term Progression

**Trois temps.**

1. **Survivre** : faim, soif, énergie, froid, premiers outils, un abri. Exigeant pendant 1 à 2 heures de jeu ; de l'inconfort, pas de l'échec.
2. **S'installer** : estran, ferme, saisons, machines, marché, maison qui s'agrandit, relations avec le village.
3. **Explorer** : radeau puis bateau, nouvelles îles, phares à rallumer, histoire.

Chaque phare rallumé fait revenir un bateau et peut amener un nouvel habitant.
L'histoire se termine au dernier phare, et le jeu continue après.

### Retention Hooks

- **Curiosity** : la prochaine grande marée de l'almanach, l'île suivante, le secret de chaque phare, la scène d'amitié à venir.
- **Investment** : la maison, les compétences, les amitiés, le village qui se repeuple.
- **Social** : sans objet (jeu solo). Remplacé par l'attachement aux habitants : anniversaires, fêtes.
- **Mastery** : mieux lire les marées, optimiser ses journées, remplir le journal.

---

## Game Pillars

### Pillar 1: La marée donne le rythme

La marée décide où et quand, jamais si. C'est un rythme prévisible, annoncé par
l'almanach, qu'on planifie et qu'on ne subit pas. Le village et la maison sont
des refuges hors de ce rythme.

*Design test* : si une mécanique de marée pousse à se précipiter plutôt qu'à
planifier, on allonge la fenêtre ou on l'annonce plus tôt.

### Pillar 2: Des habitants qu'on a envie de connaître

Chaque habitant est marquant : un design détaillé, un métier, des goûts, des
scènes propres. Le village commence avec 6 habitants complets et il est conçu
pour en accueillir d'autres ensuite.

- **Habitant complet** : un métier lié à l'archipel (saunier, ostréicultrice, ancien gardien de phare), un emploi du temps, des goûts, des paliers d'amitié avec une scène à chacun, une scène finale, des portraits expressifs.
- **Amitié maximale** : l'habitant reste chez lui, ses habitudes changent et il aide davantage le joueur, dans la quête des phares ou dans d'autres actions. Chaque habitant apporte au moins une aide concrète liée à son métier, si possible une voie vers un phare.
- **Emménager ensemble** est réservé à la relation amoureuse, à partir d'un certain seuil, avec ses scènes propres. La romance est hors de la 1.0, mais le système de relations est conçu dès le départ pour l'accueillir.

*Design test* : on n'ajoute un nouvel habitant que lorsque les précédents ont
leurs scènes complètes. Entre 12 habitants avec quelques répliques et 6 aboutis,
on commence par les 6.

### Pillar 3: On progresse par ce qu'on fait

Les compétences montent par la pratique et par la variété des actions. Plusieurs
activités font vivre le joueur et aucune n'est indispensable.

- Chaque objectif s'atteint de plusieurs façons. Rallumer un phare peut passer par l'artisanat, le commerce, l'exploration ou l'aide d'un habitant.
- Le joueur choisit d'avancer ou non. L'histoire des phares n'a aucune échéance : passer ses journées à récolter la ralentit, sans appauvrir l'expérience.

Le calendrier, les saisons, les anniversaires et l'heure limite sont décrits
dans la boucle de jeu (Core Loop, Session-Level).

*Design test* : si une fonctionnalité rend une seule activité indispensable pour
avancer, ou pénalise le joueur parce qu'il n'avance pas dans l'histoire, on
ajoute une autre voie ou on la retire.

### Pillar 4: Le confort se gagne, puis il reste

La survie pèse au début. Ce que le joueur construit (ferme, maison, village)
l'allège pour de bon. L'inconfort vit aux frontières : sur les îles lointaines,
le froid, la météo, la marée et l'éloignement de la maison pèsent.

- **Arbitrage** : près de la base, le confort l'emporte sur la marée ; aux frontières, c'est la marée qui commande.
- **Durée** : la phase de survie exigeante dure 1 à 2 heures de jeu.
- **Fin de journée** : passé une heure très tardive, retour forcé à la maison avec une petite pénalité.
- **Nature des pénalités** : la marée coûte de l'énergie et une partie de ce qui a été ramassé dans le lieu pendant cette marée ; l'heure limite coûte de l'énergie le lendemain. Aucune pénalité ne touche le reste de l'inventaire ni la progression.
- **Priorité** : l'heure limite l'emporte sur la marée. Si elle tombe pendant que le joueur est dans un lieu de marée, seul le retour forcé à la maison s'applique, avec sa pénalité ; celle de la marée ne s'ajoute pas.

*Design test* : la faim doit-elle encore menacer un joueur bien installé chez
lui ? Non. Une île lointaine doit-elle demander une préparation (vivres,
vêtements, horaires) ? Oui.

### Pillar 5: Chaque île vaut le voyage

Chaque île a ses ressources, ses lieux de marée, sa faune et son secret. Chacune
a son propre comportement de marée, et ce qu'on en rapporte améliore durablement
la base ou le village.

*Design test* : entre 8 îles qui se ressemblent et 5 vraiment distinctes, on
choisit 5.

### Anti-Pillars (What This Game Is NOT)

- **PAS une ferme obligatoire** : cela contredirait le pilier 3 et reproduirait ce qui lasse dans les longues plantations.
- **PAS une survie punitive** : ni mort définitive ni perte totale (pilier 4, expérience de détente).
- **PAS de combat dans la 1.0** : les créatures hostiles et le donjon caché dans une grotte sont prévus après la sortie. C'est le système le plus coûteux et le moins lié à la marée.
- **PAS de romance ni de mariage dans la 1.0** : la profondeur des amitiés passe avant (pilier 2). Le palier amoureux est prévu après la sortie.
- **PAS d'îles générées aléatoirement** : elles sont dessinées à la main (pilier 5).
- **PAS de multijoueur.**
- **PAS d'emprunt aux jeux de référence** : ni noms, ni personnages, ni lieux, ni histoires, ni graphismes, ni musiques, ni dialogues. Seules les mécaniques de genre sont reprises.

---

## Visual Identity Anchor

**Direction : Laisse de mer, avec deux emprunts.**

**Règle visuelle** : chaque chose existe à sec et mouillée. La marée se lit sur
le sol, pas dans l'interface.

**Principes**

1. **L'humidité est le code couleur du jeu.** Le sec est clair, crayeux, peu saturé ; le mouillé est sombre, saturé, avec des reflets. L'écart se lit aussi en luminosité, pas seulement en teinte.
   *Test* : un lieu de marée se reconnaît-il sur une capture d'écran en noir et blanc ? Sinon, on accentue le contraste.
2. **Un seul canal visuel par système.** La marée agit sur la bande d'estran, l'heure sur la teinte globale, la saison sur la végétation des hauteurs, la météo sur le ciel et les particules.
   *Test* : si deux systèmes modifient la même chose à l'écran, on en déplace un.
3. **La lumière chaude appartient aux humains** (emprunt à « Feux éteints »). L'ambre est réservé au feu, aux fenêtres et aux phares. Chaud signifie sûr.
   *Test* : une lumière chaude dans un lieu sauvage ? On la refroidit, sauf si un humain y vit.
4. **Une silhouette et une couleur signature par habitant** (emprunt à « Gens de l'archipel »), reprises sur sa maison et ses outils. Le détail passe par des portraits expressifs en dialogue, sur un corps de base commun en jeu pour partager les animations.
   *Test* : reconnaît-on l'habitant de loin, à sa silhouette seule ?

**Philosophie des couleurs** : un environnement naturel et retenu, où le
contraste sec/mouillé porte l'information, la chaleur signale l'humain et les
couleurs vives sont réservées aux habitants.

**Formes** : bandes horizontales et courbes molles pour le naturel (bancs de
sable, lignes d'algues, flaques) ; petites verticales anguleuses pour le
construit (phares, mâts, pieux), qui servent de repères.

**Directions écartées** : « Feux éteints » seule (début sombre, contraire à la
détente) ; « Gens de l'archipel » seule (dépend d'un pixel artiste, ne dit rien
de la marée).

**À décider dans la bible graphique** : la taille des tuiles (16 ou 32 pixels),
le ton de la nuit aux frontières, l'existence d'un pack du commerce couvrant
toutes les animations voulues (non vérifiée).

---

## Inspiration and References

| Reference | What We Take From It | What We Do Differently | Why It Matters |
| ---- | ---- | ---- | ---- |
| Stardew Valley | Le rythme posé, les habitants à personnalité, les relations qui progressent, l'heure limite du soir | La ferme n'est qu'une activité parmi d'autres | Montre qu'un jeu de vie tient par ses habitants |
| Core Keeper | Les statistiques qui montent selon ce qu'on fait, la variété d'objets et de décors | Des habitants avec qui se lier, absents de ce jeu | Valide la progression par la pratique |
| Terraria | Des zones bien distinctes, beaucoup d'objets, des PNJ pour échanger | Pas de combat dans la 1.0 ; l'enjeu vient de la marée et de l'éloignement | Valide l'envie d'explorer des lieux variés |
| Starbound | La variété des lieux visités, un équipage et un vaisseau à soi | Un bateau et un archipel dessiné à la main | Inspire l'aide des habitants à l'amitié maximale |
| Moonstone Island | L'exploration d'île en île, sa maison, des habitants qui ont chacun un métier, des événements relationnels | La marée change les lieux de chaque île | Le modèle le plus proche de la structure visée |
| Mayday: The Survival Island | La survie et l'exploration d'un archipel | Une survie qui s'efface une fois installé | Sert de repère de qualité visée |

**Non-game inspirations** : les tables de marées et les almanachs, les passages
submersibles et les îlots accessibles à pied à marée basse, les marais salants et
l'ostréiculture, les villages de pêcheurs, les phares.

---

## Target Player Profile

| Attribute | Detail |
| ---- | ---- |
| **Age range** | Non recherchée |
| **Gaming experience** | Occasionnel à intermédiaire, habitué des jeux de vie et d'exploration |
| **Time availability** | Sessions de 30 minutes à 2 heures |
| **Platform preference** | PC |
| **Current games they play** | Stardew Valley, Moonstone Island, Core Keeper |
| **What they're looking for** | Un chez-soi et des habitants attachants, avec une exploration qui garde de l'enjeu et une économie qui ne repose pas sur une seule activité |
| **What would turn them away** | Une ferme répétitive et obligatoire, une pression horaire lourde, un combat imposé, des habitants interchangeables |

---

## Technical Considerations

| Consideration | Assessment |
| ---- | ---- |
| **Recommended Engine** | Non décidé : à choisir dans `/setup-engine`. Le plan d'origine supposait Phaser et TypeScript avec des cartes Tiled |
| **Key Technical Challenges** | Marée par zones, emplois du temps des habitants, sauvegardes compatibles d'une version à l'autre, export Steam |
| **Art Style** | Pixel art 2D, vue de dessus |
| **Art Pipeline Complexity** | Moyenne : packs du commerce pour le décor, effet sec/mouillé par le code, portraits sur mesure (environ 25 à 30) |
| **Audio Needs** | Modérés : musique d'ambiance, bruitages pour chaque geste |
| **Networking** | Aucun |
| **Content Volume** | Cibles à ajuster : environ 40 heures, 5 îles, 6 habitants, 150 objets, 40 poissons, 60 recettes, 30 cultures |
| **Procedural Systems** | Aucun |

**Ce que le choix du moteur doit garantir** (avis du directeur technique) :

- un exécutable PC pour Steam avec l'intégration Steam qui fonctionne ;
- la manette, y compris dans les menus, et des touches reconfigurables ;
- un rendu pixel art net et des effets pour l'eau et la lumière ;
- un import fiable des cartes avec des calques personnalisés ;
- des tests automatiques.

**Règles techniques à fixer dès la première version** :

- L'état de la marée se calcule à partir de la date et de l'heure ; la sauvegarde ne stocke que la date. L'almanach affiche le même calcul.
- Les habitants se déplacent sur les cases toujours sèches. Leurs passages sur l'estran sont des scènes écrites.
- Un seul moteur de temps pilote la marée, les habitants, les cultures, l'heure limite et les événements, et peut être avancé pour les tests.
- Les sauvegardes portent un numéro de version, avec une migration testée à chaque version publiée.
- Tout le contenu (objets, recettes, habitants, dialogues) est rangé dans des fichiers de données, avec des identifiants stables et un contrôle automatique.
- Les textes sont séparés du code, pour permettre une traduction.
- Une seule source pour l'image et les règles : le niveau d'eau est une fonction du temps du jeu (jamais de l'horloge réelle). L'eau à l'écran, les passages, la cloche et l'almanach lisent tous cette fonction.
- Un seul mécanisme de retour forcé, pour la fermeture d'un lieu comme pour l'heure limite. Quand les deux tombent ensemble, l'heure limite l'emporte et les pénalités ne se cumulent pas.
- Le comportement du temps est écrit : ce qu'il fait dans les menus, les dialogues, les scènes et pendant le sommeil.
- Les lieux de marée sont décrits dans les cartes (zone, seuils, point de retour) et non dans le code, avec un nombre maximal par île.
- Budget technique : résolution interne fixe agrandie par un multiple entier, 60 images par seconde sur une machine modeste, une couche d'actions entre les touches et le jeu dès le départ.
- Le test d'export Steam se fait juste après le MVP, avec un exécutable minimal.

---

## Risks and Open Questions

### Review Verdicts

| Gate | Verdict | Suite donnée |
| ---- | ---- | ---- |
| CD-PILLARS (directeur créatif) | CONCERNS, puis APPROVE | Seconde relecture après correction des piliers. Remarques non bloquantes intégrées |
| AD-CONCEPT-VISUAL (directeur artistique) | STRONG | Direction « Laisse de mer » avec emprunts retenue |
| TD-FEASIBILITY (directeur technique) | CONCERNS, puis VIABLE | Seconde relecture après le passage à la marée par zones. Six règles ajoutées aux règles techniques |
| PR-SCOPE (producteur) | UNREALISTIC, puis OPTIMISTIC | Seconde relecture sur 24-30 mois, combat repoussé. Pas encore REALISTIC : la limite est le temps de test et de validation du directeur du jeu. Cette relecture a précédé l'engagement de 12 à 15 heures par semaine, qui n'a pas été réévalué |

### Design Risks

- La marée peut recréer une pression de journée contraire à la détente. Parade : pilier 1 et son test.
- Une progression par la pratique peut pousser à répéter un geste. Parade : progression par la variété.
- Sans créatures dans la 1.0, les îles lointaines peuvent manquer d'enjeu. À vérifier dès la tranche complète.
- La première heure, exigeante, est celle que voit un acheteur potentiel : elle doit rester de l'inconfort, pas de l'échec.
- L'amitié maximale doit offrir une récompense assez forte sans la romance.

### Technical Risks

- Le joueur présent dans un lieu de marée à sa fermeture : la règle (annonce, puis retour au rivage) est à prototyper.
- La dérive de l'architecture quand le code vient de séances successives. Parade : décisions d'architecture écrites tôt, tests automatiques.
- L'export Steam : à tester avant la quatrième version, pas à la fin.
- Le moteur n'est pas choisi.

### Market Risks

- **Un genre en forte croissance, donc encombré.** La part des nouveaux jeux Steam qui se disent « cozy » est passée de 0,4 % en 2022 à 3,1 % en 2025, parmi ceux qui dépassent 100 000 $ de recettes (GameDiscoverCo, cité par [PC Gamer](https://www.pcgamer.com/games/life-sim/the-cozy-game-boom-is-the-clearest-trend-on-steam-over-five-years-of-data/)). Un analyste tiers compte 632 jeux « cozy » sortis en 2025 et 1 041 en 2026 à la date de son rapport ([Steampageanalyzer](https://www.steampageanalyzer.com/blog/cozy-games-steam-2026-niche-report)).
- **La plupart des jeux du genre restent modestes.** Selon ce même analyste, environ 11 % des jeux « cozy » atteignent 1 000 avis, contre 4,2 % pour l'ensemble de Steam ; 27,8 % pour les simulations de ferme et 24,4 % pour les simulations de vie, sur des échantillons de 36 et 41 jeux. Source unique, définitions variables selon les étiquettes.
- **Stardew Valley est une exception, pas un repère.** Moonstone Island, le plus proche par sa structure, donne une idée plus juste d'un bon résultat.
- **Taille du public visé** : non recherchée. Les avis n'ont pas été convertis en ventes, faute de coefficient sourcé.
- **Nom « Ressac »** : libre sur Steam et sans titre identique sur la première page d'itch.io au 2026-11-10. Non vérifié : les marques déposées, les jeux non annoncés, les autres magasins. « Ressaca » signifie « gueule de bois » en portugais (« resaca » en espagnol).

**Jeux comparables** (fiches Steam relevées le 2026-11-10 ; « recommandations » est le compteur publié par Steam) :

| Jeu | Sortie | Prix de base | Recommandations | Ventes annoncées |
| ---- | ---- | ---- | ---- | ---- |
| Stardew Valley | 2016 | 14,99 $ | 904 399 | Plus de 41 millions, toutes plateformes, décembre 2024 ([Pocket Gamer.biz](https://www.pocketgamer.biz/stardew-valley-sells-over-41-million-copies)) |
| Terraria | 2011 | 9,99 $ | 1 250 353 | Non recherché |
| Starbound | 2016 | 14,99 $ | 120 672 | Non recherché |
| Core Keeper | 2024 (1.0) | 19,99 $ | 51 218 | 1 million en juin 2022, en accès anticipé ([communiqué](https://gamespress.com/Indie-hit-Core-Keeper-celebrates-1-million-sales)) |
| Moonstone Island | 2023 | 19,99 $ | 4 119 | Aucun chiffre trouvé |
| Mayday: The Survival Island | 2 novembre 2026 | 13,99 $ | 156 | Aucun chiffre trouvé ; sorti depuis huit jours au relevé |

Les prix de base des comparables vont de 9,99 $ à 19,99 $.
- Avant toute vente, faire vérifier le jeu et son nom par un professionnel du droit.

### Scope Risks

- Le volume de contenu est grand pour un premier jeu en solo. Le calendrier de 24-30 mois est une estimation de faible fiabilité, aucune séance n'ayant été mesurée.
- Le temps de test du directeur du jeu limite le rythme : un seul parcours complet prend au moins 40 heures. Engagement pris : 12 à 15 heures par semaine pour tester et valider.
- Le coût d'un habitant complet, en heures de validation, est inconnu. Il est mesuré au premier point de contrôle de la tranche complète, puis multiplié par 6.
- Le rythme mesuré au MVP, sans habitants ni contenu narratif, ne prédit pas ce coût.
- Les packs du commerce peuvent mal couvrir des besoins précis (40 poissons distincts, cohérence entre packs).
- Les portraits sur mesure dépassent le budget de 50 à 300 € prévu pour les packs : un devis est nécessaire.
- La page Steam et la communication sont à planifier.

### Open Questions

- Les années qui passent changent-elles les habitants et le village, ou chaque année reprend-elle le même cycle ? À trancher dans le document du calendrier.
- Quel moteur ? Réponse dans `/setup-engine`.
- Quelle taille de tuiles et quel pack graphique ? Réponse dans `/art-bible`, puis par un test d'une marée avec les tuiles du pack retenu.
- La boucle d'une marée est-elle agréable pendant 30 minutes ? Réponse par le prototype.
- Combien de lieux de marée par île, et quelle durée d'ouverture ? Réponse par le prototype, puis dans le document de la marée.

---

## MVP Definition

**Core hypothesis** : organiser sa journée autour de la marée sur l'île de départ
est agréable pendant au moins 30 minutes.

**Required for MVP** :

1. L'île de départ, avec deux lieux de marée : un banc de sable et une épave.
2. La marée par zones, avec son annonce et son almanach.
3. La récolte (bois, pierre, fibres, baies) et la fabrication de base.
4. La faim, la soif et l'énergie ; un feu et un abri.
5. Le cycle de la journée, avec l'heure limite et le retour forcé.
6. La sauvegarde au coucher, avec son numéro de version.

**Explicitly NOT in MVP** (defer to later) :

- La ferme, la pêche, les machines et le marché.
- Les habitants et le village.
- Le bateau et les autres îles.
- L'histoire et les phares.
- Les graphismes définitifs.

### Scope Tiers (if budget/time shrinks)

Échéances cumulées, estimées et de faible fiabilité. Elles sont recalculées après
le MVP à partir du temps réellement passé.

| Tier | Content | Features | Timeline |
| ---- | ---- | ---- | ---- |
| **Préparation** | Un test d'une marée avec les tuiles du pack retenu | Moteur et pack graphique choisis | Mois 0-1 |
| **MVP** | Île de départ, 2 lieux de marée | Marée, récolte, survie, fabrication, journée, sauvegarde | Mois 2-3 |
| **Vertical Slice, point 1** | Île de départ et île-village, 1 habitant complet | Estran, ferme, pêche, relations ; graphismes des packs appliqués. Mesure le coût d'un habitant | Mois 6 |
| **Vertical Slice, point 2** | 3 habitants complets, 1 phare | Machines, marché, compétences ; premiers testeurs extérieurs | Mois 9-10 |
| **Alpha** | 5 îles, 6 habitants, tous les phares | Bateau, calendrier et événements, histoire complète, journal ; page Steam, devis des portraits, testeurs extérieurs | Mois 18-20 |
| **Full Vision** | Contenu complet, environ 40 heures | Portraits, musique, équilibrage, tests par des joueurs extérieurs, page Steam, sortie | Mois 24-30 |
| **Après la sortie** | Nouveaux habitants, donjon caché | Créatures et combat, palier amoureux et emménagement | Non daté |

**Si le temps manque**, on coupe dans cet ordre, sans toucher aux piliers : le
nombre d'îles (de 5 à 3), puis le volume d'objets et de recettes, puis le nombre
d'habitants (de 6 à 4, chacun restant complet).

**Règles de suivi**

- Le temps passé est noté dès la préparation, pour chaque séance de code et pour les heures de test.
- Si le MVP dépasse le mois 4, l'ordre de coupe s'applique tout de suite.
- La décision « 5 ou 3 îles » se prend à l'entrée de l'alpha, vers les mois 12 à 14.
- Les outils qui avancent le temps servent de scénarios de test par île, pour alléger les tests à la main.

---

## Next Steps

- [ ] Prototyper la boucle d'une marée (`/prototype`) : valider l'hypothèse avant d'écrire les documents de design
- [ ] Choisir le moteur (`/setup-engine`)
- [ ] Écrire la bible graphique (`/art-bible`) : taille des tuiles, palette, choix du pack
- [ ] Vérifier le concept (`/design-review design/gdd/game-concept.md`)
- [ ] Découper le concept en systèmes (`/map-systems`)
- [ ] Concevoir chaque système (`/design-system [nom]`), en reprenant les enseignements du prototype
- [ ] Écrire l'architecture (`/create-architecture`, `/architecture-decision`, `/architecture-review`)
- [ ] Passer le contrôle d'étape (`/gate-check`)
- [ ] Construire la tranche complète en pré-production (`/vertical-slice`) et la faire tester (`/playtest-report`)
- [ ] Faire vérifier le nom « Ressac » auprès des registres de marques (INPI, EUIPO) avant toute vente
- [ ] Demander un devis pour les portraits
