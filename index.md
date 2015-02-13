---
layout: base
title: Starbound Reverse Engineering
---

Welcome to the Starbound reverse engineering hub! This is a community-maintained, unofficial website to collect information
about reverse engineering [Starbound](http://playstarbound.com). This website is open-source - you can help us reverse engineer
the game and offer your discoveries by submitting a pull request to [Starbound-Dev/starbound-dev](https://github.com/Starbound-Dev/starbound-dev).

Have you got questions, or do you want to get help with Starbound dev? Join our IRC channel,
<a target="_blank" href="http://webchat.freenode.net/?channels=##starbound-dev">##starbound-dev on irc.freenode.net</a>.

Though some of the information here may be valuable to modders, this website is **not** meant to document information for modding
the game. It is instead meant for reverse engineering the game and creating entirely new software based on that research.

## Projects

Want your project listed? Submit a pull request! Projects here should have some degree of usability, though they may not
yet be complete.

<!--
    These lists are for open-source projects only.
    Maintain these lists first by supported Starbound version, and second alphabetically. Don't compete for room here.
    External links should have target="_blank"
    Add categories when appropriate. I expect there to be a "server" and "client" section eventually, and probably a
    "libraries" section. Make an "other" section if your stuff doesn't fit into the existing categories.

	Categories have been condensed to "client," "server," "tools" and "other" until we get more projects added. I'm
	leaving out the "client" category until we actually get a client project on the list. Also, whenever we get more
	projects it may be beneficial to have some form of navigation in order to navigate quickly to the category you're
	looking for.
-->

{% include project-category-header.html name="Server" description="A server project can be anything from a wrapper to a complete recode of the official server." %}
<table class="table">
    <thead>
        <tr>
            <th>Project</th>
            <th>Description</th>
            <th>Starbound</th>
            <th>Stability</th>
            <th>Languages</th>
            <th>License</th>
        </tr>
    </thead>
    <tbody>
        <tr> <!-- StarryPy -->
            <td><a target="_blank" href="https://github.com/StarryPy/StarryPy">StarryPy/StarryPy</a></td>
            <td>Plugin-driven Starbound proxy server built using Twisted.</td>
            <td><span class="label label-success">Upbeat Giraffe</span></td>
            <td><span class="label label-success">Stable</span></td>
            <td>Python</td>
            <td><a target="_blank" href="https://github.com/StarryPy/StarryPy/blob/master/LICENSE">WTFPL</a></td>
        </tr>
	</tbody>
</table>

{% include project-category-header.html name="Tools" description="Tools are either a library or a program that can be used to view and/or edit some form of data (player, world, etc.) file(s)." %}
<table class="table">
    <thead>
        <tr>
            <th>Project</th>
            <th>Description</th>
            <th>Starbound</th>
            <th>Stability</th>
            <th>Languages</th>
            <th>License</th>
        </tr>
    </thead>
    <tbody>
        <tr> <!-- starcheat -->
            <td><a target="_blank" href="https://github.com/wizzomafizzo/starcheat">wizzomafizzo/starcheat</a></td>
            <td>Python modules for parsing/editing .player files and assets</td>
            <td><span class="label label-success">Upbeat Giraffe</span></td>
            <td><span class="label label-success">Unstable</span></td>
            <td>Python</td>
            <td><a target="_blank" href="https://github.com/wizzomafizzo/starcheat/blob/master/LICENSE">MIT</a></td>
        </tr>
	</tbody>
</table>

{% include project-category-header.html name="Other" description="Projects in this category either don't fit under any of the categories above or the project submitter was unsure what category to put the project under." %}
<table class="table">
    <thead>
        <tr>
            <th>Project</th>
            <th>Description</th>
            <th>Starbound</th>
            <th>Stability</th>
            <th>Languages</th>
            <th>License</th>
        </tr>
    </thead>
</table>
