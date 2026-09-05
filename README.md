<div align="center">

<!-- ✦ animated intro · light & dark variants ✦ -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=25&duration=3200&pause=1000&color=FAB387&center=true&vCenter=true&width=620&height=60&lines=Hey%2C%20I%27m%20Th%C3%A9o%20%F0%9F%91%8B;software%20student%20%26%20maker;my%20house%20knows%20when%20I%27m%20home;currently%20lost%20in%20graph%20databases;the%203D%20printer%20never%20sleeps;ask%20me%20about%20mmWave%20radar" />
  <img alt="Hey, I'm Théo" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=25&duration=3200&pause=1000&color=FE640B&center=true&vCenter=true&width=620&height=60&lines=Hey%2C%20I%27m%20Th%C3%A9o%20%F0%9F%91%8B;software%20student%20%26%20maker;my%20house%20knows%20when%20I%27m%20home;currently%20lost%20in%20graph%20databases;the%203D%20printer%20never%20sleeps;ask%20me%20about%20mmWave%20radar" />
</picture>

<samp>🇨🇭 Geneva, Switzerland &nbsp;·&nbsp; student by day, maker by night</samp>

<br/>

<!-- 🏠 self-hosted animated svg · assets/house.svg -->
<img width="100%" alt="a dot walks home, the street lamps and the house wake up" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/main/assets/house.svg" />

</div>

<img width="100%" alt="" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/main/assets/divider.svg" />

## ☕ about me

<samp>everything below is a drawer &nbsp;·&nbsp; click to open</samp>

<details>
<summary><b>🎓 what I'm studying</b></summary>

<br/>

software dev student, currently deep in NoSQL land: MongoDB ⇄ ArangoDB graph pipelines in C# / .NET 8.
turns out modelling a house as a graph is much nicer than modelling it as 40 rows in a table.

<img width="100%" alt="a graph traversal lighting up node by node" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/main/assets/graph.svg" />

</details>

<details>
<summary><b>🏠 the house that knows</b></summary>

<br/>

ESP32-C3 boards + mmWave presence radar in most rooms, all talking ESPHome to Home Assistant.
no PIR sensors, no "the lights turned off because I stopped moving" nonsense.

```mermaid
flowchart LR
  R["📡 mmWave radar"] --> E["ESP32-C3<br/>ESPHome"]
  D["🌡️ temp / lux"] --> E
  E -- MQTT --> H(("🏠 Home<br/>Assistant"))
  H --> L["💡 lights"]
  H --> C["🔥 heating"]
  H --> S["🔊 speakers"]
  H --> G[("🕸️ graph db<br/>of every event")]
  G -.-> H
```

<details>
<summary><i>...and what actually breaks</i></summary>

<br/>

- radar picks up the neighbour through the wall → lights on at 3am
- wifi drops → the house forgets I exist
- I flash new firmware at midnight → see above

</details>

</details>

<details>
<summary><b>🖨️ the printer that never sleeps</b></summary>

<br/>

about a decade of 3D printing now. if it can be printed, it will be printed —
enclosures for the ESP boards, brackets, and an unreasonable number of things that hold other things.

<img width="100%" alt="a 3D printer laying down layers on loop" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/main/assets/printer.svg" />

</details>

<details>
<summary><b>📌 currently</b></summary>

<br/>

- [x] wire the ground floor with presence sensors
- [x] get ArangoDB traversals into the .NET side
- [ ] first floor (the wiring is *right there*, I promise)
- [ ] stop starting new projects
- [ ] ~~stop starting new projects~~

</details>

<img width="100%" alt="" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/main/assets/divider.svg" />

## 🧰 toolbox

<div align="center">

<!-- swap icons freely · full list: https://skillicons.dev -->
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=cs,dotnet,mongodb,js,html,css,git,vscode" alt="code stack" /></a>
<br/>
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=arduino,raspberrypi,linux" alt="maker stack" /></a>

<br/><br/>

<a href="https://arangodb.com"><img src="https://img.shields.io/badge/ArangoDB-313244?style=flat-square&logo=arangodb&logoColor=A6E3A1" alt="ArangoDB" /></a>
<a href="https://www.home-assistant.io"><img src="https://img.shields.io/badge/Home_Assistant-313244?style=flat-square&logo=homeassistant&logoColor=89DCEB" alt="Home Assistant" /></a>
<a href="https://esphome.io"><img src="https://img.shields.io/badge/ESPHome-313244?style=flat-square&logo=esphome&logoColor=CDD6F4" alt="ESPHome" /></a>
<a href="https://www.espressif.com/en/products/socs/esp32-c3"><img src="https://img.shields.io/badge/ESP32--C3-313244?style=flat-square&logo=espressif&logoColor=F38BA8" alt="ESP32-C3" /></a>

</div>

<img width="100%" alt="" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/main/assets/divider.svg" />

## 📈 stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=theo-bggtt&show_icons=true&hide_border=true&theme=catppuccin_mocha" />
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=theo-bggtt&show_icons=true&hide_border=true&theme=catppuccin_latte" />
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=theo-bggtt&hide_border=true&theme=catppuccin-mocha" />
  <img height="165" alt="contribution streak" src="https://streak-stats.demolab.com?user=theo-bggtt&hide_border=true&theme=catppuccin-latte" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=theo-bggtt&layout=compact&langs_count=8&hide_border=true&theme=catppuccin_mocha" />
  <img height="165" alt="most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=theo-bggtt&layout=compact&langs_count=8&hide_border=true&theme=catppuccin_latte" />
</picture>

<br/><br/>

<!-- 📉 last 31 days of activity, redrawn on every page load -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=theo-bggtt&bg_color=00000000&color=cdd6f4&title_color=cba6f7&line=cba6f7&point=fab387&area=true&area_color=cba6f7&hide_border=true&custom_title=last%2031%20days" />
  <img width="100%" alt="contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=theo-bggtt&bg_color=00000000&color=4c4f69&title_color=8839ef&line=8839ef&point=fe640b&area=true&area_color=8839ef&hide_border=true&custom_title=last%2031%20days" />
</picture>

<br/><br/>

<!-- 🐍 generated by .github/workflows/snake.yml · appears after the first workflow run -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/output/github-snake.svg" />
  <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/output/github-snake.svg" />
</picture>

</div>

<img width="100%" alt="" src="https://raw.githubusercontent.com/theo-bggtt/theo-bggtt/main/assets/divider.svg" />

<div align="center">

<a href="https://github.com/theo-bggtt?tab=repositories"><img src="https://img.shields.io/badge/poke_around_my_repos-313244?style=for-the-badge&logo=github&logoColor=FAB387" alt="repos" /></a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=theo-bggtt&style=for-the-badge&color=8839ef&label=PROFILE+VIEWS" alt="profile views" />

<br/><br/>

<sub>built with ☕, a soldering iron and a 3D printer that never sleeps</sub>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:FAB387,100:CBA6F7&section=footer" alt="" />
