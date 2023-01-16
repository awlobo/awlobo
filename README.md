<h1 align="center">Hi 👋, I'm <a href="https://awlobo.github.io/">Andrea</a>!</h1> <!-- Link to  https://awlobo.github.io/ -->
<h3 align="center">A passionate software developer from Madrid, Spain</h3>
<p align="center">🏢 Currently working on <a href="https://www.pix4d.com/product/pix4dscan-drone-flight-inspection-software">PIX4Dscan</a> @ <a href="https://www.pix4d.com/">PIX4D</a>
</p>

<img align="right" width="35%" src="https://media.giphy.com/media/ZG719ozZxGuThHBckn/source.gif"/>

```python
​
from __future__ import annotations

import json
from dataclasses import asdict, dataclass


@dataclass
class Skillset:
    languages: tuple[str, ...] = ("C++", "Python", "Kotlin")
    mobile: tuple[str, ...] = ("Android", "Flutter")
    databases: tuple[str, ...] = ("SQLite", "PostgreSQL", "MySQL")
    misc     : tuple[str, ...] = ("Docker", "Firebase", "Selenium", "Rx")
    os: tuple[str, ...] = ("Windows Server", "Arch Linux", "Ubuntu", "MacOS")
    ongoing  : tuple[str, ...] = ("Django", "DRF", "Asyncio")

    def jsonify(self) -> str:
        return json.dumps(asdict(self), indent=4)


skillset = Skillset()
print(skillset.jsonify())
print("Power is pizza")
​
```

<p align="center" ><img src="https://raw.githubusercontent.com/awlobo/awlobo/master/github-contribution-grid-snake.svg" alt="awlobo" /></p>
<p align="center"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=awlobo&show_icons=true&locale=en&layout=compact" alt="awlobo" /></p>
<p align="center"><img src="https://lastfm-recently-played.vercel.app/api?user=pand0ra93&count=1"></p>
<p align="center"><img src="https://profile-counter.glitch.me/awlobo/count.svg"></p>

<!--
**awlobo/awlobo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
