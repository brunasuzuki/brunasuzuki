<h2>Hello, I'm Bruna👋</h2>


<div align="center">
  <a href="https://github.com/brunasuzuki">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=brunasuzuki&show_icons=true&theme=cobalt&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=brunasuzuki&layout=compact&langs_count=7&theme=cobalt"/>
</div>

  
 <div style="display: inline_block"><br>
  <img align="center" alt="Bruna-RUBY" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ruby/ruby-plain.svg">
  <img align="center" alt="Bruna-RAILS" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rails/rails-original-wordmark.svg">
  <img align="center" alt="Bruna-JQUERY" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jquery/jquery-original.svg">
  <img align="center" alt="Bruna-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Bruna-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Bruna-SASS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg">
  <img align="center" alt="Bruna-BOOTSTRAP" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain.svg">
  <img align="center" alt="Bruna-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Bruna-GITHUB" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg">
  <img align="center" alt="Bruna-FIGMA" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/figma/figma-original.svg">  
</div>
  

<div>
 ![Snake animation](https://github.com/brunasuzuki/brunasuzuki/blob/output/github-contribution-grid-snake.svg)
  name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: brunasuzuki
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
</div>
