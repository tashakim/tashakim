<!--
**tashakim/tashakim** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
[![Tasha's github stats](https://github-readme-stats.vercel.app/api?username=tashakim&theme=merko&hide_rank=false&hide_title=false&count_private=true&include_all_commits=true&show_icons=true)](https://github.com/tashakim/github-readme-stats)
![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=tashakim&repo=puzzles_python&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)
![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=tashakim&repo=apertium-kor&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

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
# Banner
![alt text](https://github.com/tashakim/tashakim/blob/master/banner-with-a-summer-look.png?raw=true)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'

jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->
