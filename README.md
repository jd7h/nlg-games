# Games that use Natural Language Generation (NLG)
A curated list of digital games that use Natural Language Generation techniques. Game using Procedural Content Generation can be added too, as long as the generated content gives rise to textual game assets as well. For an example, see [the weapon types of Diablo III](https://diablo.gamepedia.com/List_of_Affixes).

- [Contribution guide](contributing.md)

Follow me on [Twitter](https://twitter.com/jd7h).

## Contents

- [Commercial games](#commercial-games)
- [Indie games](#indie-games)

## Commercial games
- [Diablo III](//diablo3.com) - Some of the loot in the Diablo games is procedurally generated. Different types of weapons have specific names and bonuses. [List of weapon types](https://diablo.gamepedia.com/List_of_Affixes)
- [Blood & Laurels](https://versu.com/2014/05/28/blood-laurels/) - No longer available but an iOS IF game which ran on "Versu" an engine built specifically for NLG use cases. The game generated character behaviours and dialogue procedurally. Posts on this system can be found on Emily Short's blog such as [Writing for Versu](https://emshort.blog/2017/05/18/mailbag-writing-for-versu/) and [Versu: Conversation Implementation](https://emshort.blog/2013/02/26/versu-conversation-implementation/).

## Indie games
- [Epitaph](https://mkremins.itch.io/epitaph) - Epitaph features procedurally generated civilizations, events and tech trees. [Underlying grammar for events](https://github.com/mkremins/epitaph/blob/master/src/epitaph/events.cljs).
- [Alabaster](http://emshort.home.mindspring.com/Alabaster/) - An IF game which incorporates 400+ snippets of text that get patched together based on internal state models. As with other works by Emily Short, various posts exist on her blog discussing implementation such as [Moods in conversation](https://emshort.blog/2009/12/10/moods-in-conversation/).
- [Glass](http://inform7.com/learn/eg/glass/index.html) - An IF game which takes a procedural approach to conversation modelling based on an internal conversation state flag. Making of is [found here](http://inform7.com/learn/eg/glass/Overview.html) and further discussion of the "Waypoint" narrative structure used is [found here](https://emshort.blog/2016/04/12/beyond-branching-quality-based-and-salience-based-narrative-structures/).
- [The Mary Jane of Tomorrow](http://ifdb.tads.org/viewgame?id=27ztb4iulm9l7sqe) - An IF game which uses procedural generation to determine how a robot NPC will behave/talk to the player based on internal state. A system not used in the game itself but which has similar end results is discussed in [Applying Filters to Character Dialogue](https://emshort.blog/2018/05/08/mailbag-applying-filters-to-character-dialogue/)
- [Voyageur](https://voyageur.space/) - An IF game that uses the [Improv](https://github.com/sequitur/improv) generative text library (created by the game’s author, [Bruno Dias](https://twitter.com/notbrunoagain)) to generate procedural descriptions of the various locations and situations you encounter. Here’s an [interview with Bruno](https://ifsff.wordpress.com/2016/06/17/interview-bruno-dias-on-voyageur-and-procedural-generation/) in which he discusses his approach to writing with procedural text.
