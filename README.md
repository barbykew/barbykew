<!--
  Palette matches Shulker's own GlassUIConstants:
    accent   #A36CD8   (163,108,216)
    surface  #0F0E14   (15,14,20)
    text     #C5C9D8   (197,201,216)
-->

<img width="100%" src="./assets/banner.svg" alt="barbykew">

<p align="center">
  <a href="https://github.com/barbykew">
    <img src="https://readme-typing-svg.demolab.com?font=VT323&size=30&pause=1400&color=A36CD8&center=true&vCenter=true&width=860&height=48&lines=i+build+ghost+clients;i+build+websites;i+write+things+from+scratch;mostly+java+and+typescript" alt="typing">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/I%20BUILD-GHOST%20CLIENTS-A36CD8?style=flat-square&labelColor=0F0E14" alt="ghost clients">
  <img src="https://img.shields.io/badge/AND-WEBSITES-6E3FA3?style=flat-square&labelColor=0F0E14" alt="websites">
  <img src="https://img.shields.io/badge/FROM-SCRATCH-2A1E3D?style=flat-square&labelColor=0F0E14" alt="from scratch">
</p>

<br>

## `~/ stack`

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,gradle,vulkan,idea,git,ts,react,tailwind,nodejs,figma&theme=dark&perline=5" alt="stack">
</p>

<br>

## `~/ me`

I write low-level Java and front-end TypeScript, and I'd rather build a thing myself than
pull in a dependency for it — which is why my client ships its own renderer instead of
borrowing one.

## `~/ shulker`

The project I spend most of my time on. A ghost client for Minecraft — though the features
aren't the hard part; keeping **one source tree honest across two Minecraft versions and two
graphics APIs at once** is.

<table>
<tr>
<td width="50%" valign="top">

**one tree, two versions**

Targets `1.21.11` and `26.2-snapshot-2` through
[Stonecutter](https://github.com/kikugie/stonecutter). Version-specific code is quarantined
in small compat classes instead of being smeared through every module — so a Minecraft
release breaks four files, not four hundred.

</td>
<td width="50%" valign="top">

**two render backends**

A custom 2D/3D renderer abstracted over **OpenGL and Vulkan**. Every shader effect ships as
a mirrored pair so neither backend is a second-class citizen.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**built to be quiet**

Ghost client, so the whole design goal is that nothing it does is observable from the
outside — that constraint drives most of the interesting decisions.

</td>
<td width="50%" valign="top">

**internals**

Mixin-driven, reflective event bus, and a settings system that builds its own GUI from
module fields. ~100 modules across combat, movement, render, player and HUD.

</td>
</tr>
</table>

<br>

## `~/ stats`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=barbykew&show_icons=true&hide_border=true&bg_color=0F0E14&title_color=A36CD8&icon_color=A36CD8&text_color=C5C9D8&hide_title=true" alt="stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=barbykew&layout=compact&hide_border=true&bg_color=0F0E14&title_color=A36CD8&text_color=C5C9D8&langs_count=8" alt="languages">
</p>

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com?user=barbykew&hide_border=true&background=0F0E14&stroke=2A1E3D&ring=A36CD8&fire=A36CD8&currStreakLabel=A36CD8&sideLabels=C5C9D8&dates=6E6E7A&sideNums=C5C9D8&currStreakNum=EDE6F7" alt="streak">
</p>

<p align="center">
  <img width="90%" src="https://github-profile-trophy.vercel.app/?username=barbykew&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=6&margin-h=6" alt="trophies">
</p>

<br>

## `~/ contributions`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/barbykew/barbykew/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/barbykew/barbykew/output/snake.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/barbykew/barbykew/output/snake.svg">
</picture>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=barbykew&bg_color=0F0E14&color=C5C9D8&line=A36CD8&point=EDE6F7&area=true&hide_border=true&custom_title=commit%20activity" alt="activity graph">
</p>

<br>

<img width="100%" src="./assets/footer.svg" alt="">
