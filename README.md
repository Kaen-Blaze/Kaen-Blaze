<div align="center">

# ⚡ KAEN BLAZE ⚡

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=32&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Full-Stack+Developer;Python+%7C+MERN+%7C+Shopify;Building+Futuristic+Solutions" />

<img src="https://skillicons.dev/icons?i=python,javascript,typescript,react,nodejs,nextjs,php,wordpress,firebase,docker,git,github,vscode&theme=dark" />

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Kaen-Blaze&theme=tokyonight&no-frame=true&row=1&column=6" />

</div>



pacman.yml


name: Generate Pacman Animation

on:
schedule:
- cron: "0 */12 * * *"

workflow_dispatch:

jobs:
generate:
permissions:
contents: write

```
runs-on: ubuntu-latest

steps:
  - name: Generate Pacman
    uses: abozanona/pacman-contribution-graph@main
    with:
      github_user_name: Kaen-Blaze

  - name: Push Pacman Animation
    uses: crazy-max/ghaction-github-pages@v3
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```


1-3 minutes


## 👾 Contribution Game

<div align="center">

<img src="https://raw.githubusercontent.com/Kaen-Blaze/Kaen-Blaze/output/pacman-contribution-graph.svg">

</div>




## 🌌 Current Focus

* ⚡ Full-Stack Web Development
* 🛒 Shopify & E-Commerce Systems
* 📱 Cross-Platform Mobile Apps
* 🚀 REST APIs & Backend Development
* 🎨 Modern UI/UX Interfaces
