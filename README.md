# Games that use Natural Language Generation (NLG)
A curated list of digital games that use Natural Language Generation techniques. Game using Procedural Content Generation can be added too, as long as the generated content gives rise to textual game assets as well. For an example, see [the weapon types of Diablo III](https://diablo.gamepedia.com/List_of_Affixes).

- [Contribution guide](contributing.md)

Follow me on [Twitter](https://twitter.com/jd7h).

## Contents

- [Commercial games](#commercial-games)
- [Indie games](#indie-games)
  - [Idle games](#idle-games)
  - [Interactive fiction](#interactive-fiction)

## Commercial games
- [Diablo III](//diablo3.com) - Some of the loot in the Diablo games is procedurally generated. Different types of weapons have specific names and bonuses. [List of weapon types](https://diablo.gamepedia.com/List_of_Affixes)
- [Blood & Laurels](https://versu.com/2014/05/28/blood-laurels/) - No longer available but an iOS IF game which ran on "Versu" an engine built specifically for NLG use cases. The game generated character behaviours and dialogue procedurally. Posts on this system can be found on Emily Short's blog such as [Writing for Versu](https://emshort.blog/2017/05/18/mailbag-writing-for-versu/) and [Versu: Conversation Implementation](https://emshort.blog/2013/02/26/versu-conversation-implementation/).
- [Bot Colony](http://botcolony.com) (2014) - 3D commercial game using conventional dialogue-systems technology, including a full pipeline for natural language understanding.

## Indie games
### Idle games
- [Epitaph](https://mkremins.itch.io/epitaph) - Epitaph features procedurally generated civilizations, events and tech trees. [Underlying grammar for events](https://github.com/mkremins/epitaph/blob/master/src/epitaph/events.cljs).

### Interactive Fiction (IF)
- [Alabaster](http://emshort.home.mindspring.com/Alabaster/) - An IF game which incorporates 400+ snippets of text that get patched together based on internal state models. As with other works by Emily Short, various posts exist on her blog discussing implementation such as [Moods in conversation](https://emshort.blog/2009/12/10/moods-in-conversation/).
- [Glass](http://inform7.com/learn/eg/glass/index.html) - An IF game which takes a procedural approach to conversation modelling based on an internal conversation state flag. Making of is [found here](http://inform7.com/learn/eg/glass/Overview.html) and further discussion of the "Waypoint" narrative structure used is [found here](https://emshort.blog/2016/04/12/beyond-branching-quality-based-and-salience-based-narrative-structures/).
- [The Mary Jane of Tomorrow](http://ifdb.tads.org/viewgame?id=27ztb4iulm9l7sqe) - An IF game which uses procedural generation to determine how a robot NPC will behave/talk to the player based on internal state. A system not used in the game itself but which has similar end results is discussed in [Applying Filters to Character Dialogue](https://emshort.blog/2018/05/08/mailbag-applying-filters-to-character-dialogue/)
- [Voyageur](https://voyageur.space/) - An IF game that uses the [Improv](https://github.com/sequitur/improv) generative text library (created by the game’s author, [Bruno Dias](https://twitter.com/notbrunoagain)) to generate procedural descriptions of the various locations and situations you encounter. Here’s an [interview with Bruno](https://ifsff.wordpress.com/2016/06/17/interview-bruno-dias-on-voyageur-and-procedural-generation/) in which he discusses his approach to writing with procedural text.
- [Seedship](http://philome.la/johnayliff/seedship) - An IF game that procedurally assembles star system and event descriptions as you journey through space. Source code doesn’t appear to be readily available, but examining the HTML reveals that some of the surface text is being stitched together from smaller pieces.
- [Starfreighter](https://mkremins.itch.io/starfreighter) - An IF game about eking out an existence as a freelancing light freighter captain in a procedurally generated region of space. The vast majority of text in the game is procedural; [here’s a file with some good examples](https://github.com/mkremins/starfreighter/blob/master/src/starfreighter/cards/port.cljs) of how the game uses grammars to generate surface text.

### Other
- [Interruption Junction](http://squinky.me/2015/01/18/interruption-junction/) (2015) - An arcade game by Dietrich "Squinky" Squinkifier that explores the phenomenology of awkward conversation. Its ceaseless character dialogue is generated using Kate Compton's Tracery.
- [A Tough Sell](https://www.lablablab.net/?p=435) (2015) - A talking simulator that utilizes the ChatScript chatbot technology. The player speaks as Snow White's evil stepmother in an effort to get the former, an NPC, to eat the poisoned apple. The first game by LabLabLab, an academic game studio dedicated to exploring conversational interaction in games. 
- [SimProphet](https://www.lablablab.net/?p=437) (2015) - The second LabLabLab talking simulator also uses ChatScript technology, this time with the narrative framing in which the player is a deity attempting to convert an NPC peasant into converting to the deity's religion. This game extends A Tough Sell by reusing components of the player's utterances.
- [SimHamlet](https://www.lablablab.net/?p=436) (2016) - In LabLabLab's third ChatScript-driven game, the player is cast as a government official who must ascertain, from a gravedigger NPC, the various details of Hamlet's tragical events. This game extends the previous two LabLabLab efforts by making the player's task one of information retrieval from an NPC.
- [Hammurabi](https://www.lablablab.net/?p=505) (2017) - LabLabLab's fourth effort is a remake of the 1968 videogame of the same name and features more extensive use of natural language generation (using James Ryan's Expressionist system). At its heart a simple resource-management game (like the original), it obfuscates the underlying game state through a collection of three NPCs who serve as subjective (and biased) mediators between the player and that state. Updates about in-game events are expressed through generated character monologues.
- [Subject and Subjectivity](https://www.lablablab.net/?p=499) (2017) - This LabLabLab title, whose development was led by Ben Kybartas, is set in a Jane Austen-inspired world in which the player must match her friends with ideal bachelors. As the game proceeds, NPCs engage in polite conversation, with the utterances being generated from a context-free grammar that works similarly to Kate Compton's Tracery.

### Research
- [Crystal Island](https://www.intellimedia.ncsu.edu/wp-content/uploads/ci-dialogue-iva-08.pdf) (2009) - A serious game developed by researchers at North Carolina State University. NPC dialogue is generated using probabilistic unification-based architecture.
- [SpyFeet](https://games.soe.ucsc.edu/project/spyfeet) (2011) - An augmented-reality exercise game that utilizes conventional pipelines for dialogue management and natural language generation. A prototype was produced, but not released publicly.
- [MKULTRA](https://www.aaai.org/ocs/index.php/AIIDE/AIIDE15/paper/view/11549) (2014) - An experimental game by Northwestern professor Ian Horswill that generates character dialogue using a definite-clause grammar that is specified in Prolog. The game centers on a novel game mechanic that Horswill calls "belief injection": the player can freely type in messages that trigger updates to NPC beliefs, which is how puzzles are solved. A prototype with a complete first level is available on GitHub: https://github.com/ianhorswill/MKULTRA.
