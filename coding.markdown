---
layout: page
title: Coding
permalink: /code/
---

## Spencer's Data Projects
# [LA City Assessor Data Project](https://github.com/sadnixon/LACityDataProject)
Inspired by a question about which areas of LA are the "oldest", Spencer used Python webscraping to gather information on every building from the City of Los Angeles. By systematically gathering data from the [ZIMAS](https://zimas.lacity.org/) tool, he was able to create a map of Los Angeles in which each building is colored according to age.


<button type="button" onclick="show()" id="btnID">
	Toggle Map
</button>
<img id="image" src="/assets/LAConstructionDateMapFinal.png" style="display: none;"/>

<script>
	function show() {
	var x = document.getElementById("image");
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
The Uprising Bot, written in Javascript, was created in 2021 for use in a long-form tournament called Deduction Team Comps run within the Social Deduction board game community. Spencer worked as the primary contributor on the project. The bot was used to facilitate playthroughs of the game Coup: Uprising, a highly complex expansion of the popular card game Coup. The bot keeps track of gamestates and allows players to use Discord commands to inpute game actions, allowing the game to be played entirely within a Discord channel.

# [EpoxyBot](https://github.com/sadnixon/EpoxyBot)
The EpoxyBot, written in Python, was created in 2023 for use in a local Dodgeball community. Spencer created the bot as a simple but effective way to keep track of whether people in a given server are participating in weekly activities.