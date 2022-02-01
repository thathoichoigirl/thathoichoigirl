<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: thathoichoigirl/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
          SHOW_OS: "False"
          SHOW_PROJECTS: "False"
          
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=thathoichoigirl&theme=radical&date_format=M%20j%5B%2C%20Y%5D)](https://git.io/streak-stats)

![ezgif com-gif-maker](https://user-images.githubusercontent.com/91699007/150616708-92e0953c-e775-468d-bd0e-b745afe1222f.gif)

## **Watch my contribution graph get eaten by the snake 🐍**
![snake gif](https://github.com/thathoichoigirl/thathoichoigirl/blob/output/github-contribution-grid-snake.svg)
