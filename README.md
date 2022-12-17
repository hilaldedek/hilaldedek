<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=69F712&background=000000A5&width=435&lines=Hello+I'm+Hilal.;I'm+a+Full-stack+developer." alt="Typing SVG" /></a>
<br />

### 🔧 Languages and Tools:

[<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />][vsCode]
[<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />][git]
[<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />][github]
[<img align="left" alt="Python" width="26px" src="https://raw.githubusercontent.com/github/explore/cebd63002168a05a6a642f309227eefeccd92950/topics/python/python.png" />][python]

<br />


[vsCode]: https://code.visualstudio.com/
[git]: https://git-scm.com/
[github]: https://github.com/IbrahimTalha0
[python]: https://www.python.org/


<br />
<br />
 <img height="180em" align="center" src="https://github-readme-stats.vercel.app/api?username=hilaldedek&show_icons=true&locale=en&theme=algolia&include_all_commits=true&count_private=true" alt="mukireus"/>
  <img height="180em" align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=hilaldedek&show_icons=true&locale=en&layout=compact&langs_count=8&theme=algolia" alt="mukireus"/>
  
  
name: Contribution snake

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update snake grid
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: hilaldedek
          svg_out_path: dist/github-contribution-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<!---
hilitomilito/hilitomilito is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
