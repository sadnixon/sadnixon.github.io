---
layout: page
title: Coding
permalink: /code/
---

## Spencer's Data Projects
# [LA City Assessor Data Project](https://github.com/sadnixon/LACityDataProject)
Inspired by a question about which areas of LA are the "oldest", Spencer used Python webscraping to gather information on every building from the City of Los Angeles. By systematically gathering data from the [ZIMAS](https://zimas.lacity.org/) tool, he was able to create a map of Los Angeles in which each building is colored according to age.

<button type="button" onclick="show_map()" id="mapBtn">
	Toggle Map
</button>
<img id="map-image" src="/assets/LAConstructionDateMapFinal.png" style="display: none;"/>

<script>
	function show_map() {
	var x = document.getElementById("map-image");
	if (x.style.display === "none") {
		x.style.display = "block";
	} else {
		x.style.display = "none";
	}
}
</script>

# Board Game Tournament & Gameplay Data Project
Spencer's involvement with the Social Deduction board game community on Discord has led him to produce multiple series of videos. These videos showcase data science techniques implemented with Python code, designed to gain various insights to the games that are played. These data science undertakings have included:

1. [A simulator which calculates the odds of any given team winning in a specific game tournament](https://youtu.be/uOcQQZUn0Ag)
2. [Detailed analyses of "drafts" of players which occured in game tournaments](https://youtu.be/hZcY5yVu4Y0)
3. [A data-based study of whether or not a specific common gameplay tactic is good to do or not](https://youtu.be/9Nw9TI4enfk)

Playlist of videos focusing on gameplay analysis:
<style type="text/css">
	.container {
		position: relative;
		overflow: hidden;
		width: 100%;
		padding-top: 56.25%; /* 16:9 Aspect Ratio (divide 9 by 16 = 0.5625) */
	}
	.responsive-iframe {
		position: absolute;
		top: 0;
		left: 0;
		bottom: 0;
		right: 0;
		width: 100%;
		height: 100%;
	}
</style>
<div class="container">
	<iframe class="responsive-iframe" width="600" height="340" src="https://www.youtube.com/embed/videoseries?si=LeSX47byCapO-WtT&amp;list=PLDdSKif6ugc03TFEvtcPyJ3KFh0EpgrvU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
Playlist of videos focusing on game tournament analysis:
<div class="container">
	<iframe class="responsive-iframe" width="600" height="340" src="https://www.youtube.com/embed/videoseries?si=om6SDyGnGRGA1Uj1&amp;list=PLDdSKif6ugc0TxKmnZAY7g6rpo6svb_ym" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

## Spencer's Game/AI Projects
# [UsurperBot](https://github.com/sadnixon/UsurperBot)
Out of a desire to play the card game [Usurper: A Game Of Dark Factions](https://www.kickstarter.com/projects/1051573872/usurper-a-game-of-dark-factions) without someone else to play it with, Spencer recreated the game using only Python's Pygame library and coded an AI capable of playing at an extremely high skill level - perhaps superhuman. The AI works in two segments - one segment which conducts the initial card draft using weights calculated after thousands of practice games, and one segment which plays the cards in an order calculated to be as efficient as possible. All features of the game were implemented, as well as multiple AI difficulties.

<button type="button" onclick="show_draft()" id="draftBtn">
	Toggle Image of Draft Phase
</button>
<img id="draft-image" src="/assets/DraftPhaseUsurper.png" style="display: none;"/>

<button type="button" onclick="show_play()" id="playBtn">
	Toggle Image of Play Phase
</button>
<img id="play-image" src="/assets/PlayPhaseUsurper.png" style="display: none;"/>

<script>
	function show_draft() {
	var x = document.getElementById("draft-image");
	if (x.style.display === "none") {
		x.style.display = "block";
	} else {
		x.style.display = "none";
	}
}
</script>

<script>
	function show_play() {
	var x = document.getElementById("play-image");
	if (x.style.display === "none") {
		x.style.display = "block";
	} else {
		x.style.display = "none";
	}
}
</script>


## Spencer's Discord Bots
Spencer has created and maintained a number of bespoke Discord Bots which are custom-built for sophisticated use cases in specific online communities.

# [Tourney Bot](https://github.com/sadnixon/tourney-bot)
The Tourney Bot, written in JavaScript, is used by multiple communities within the broader Social Deduction board game community. Since April of 2021, it has been maintained by Spencer. It provides tournament participants, admins, and spectators with many useful features such as looking up detailed statistics on any player, displaying tournament standings, placing "side-bets", and sending "ping" reminders about upcoming game times.

# [Uprising Bot](https://github.com/nch0w/uprising)
The Uprising Bot, written in Javascript, was created in 2021 for use in a long-form tournament called Deduction Team Comps run within the Social Deduction board game community. Spencer worked as a primary contributor on the project. The bot was used to facilitate playthroughs of the game Coup: Uprising, a highly complex expansion of the popular card game Coup. The bot keeps track of gamestates and allows players to use Discord commands to inpute game actions, allowing the game to be played entirely within a Discord channel.

# [EpoxyBot](https://github.com/sadnixon/EpoxyBot)
The EpoxyBot, written in Python, was created in 2023 for use in a local Dodgeball community. Spencer created the bot as a simple but effective way to keep track of whether people in a given server are participating in weekly activities.