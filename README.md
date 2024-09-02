Olá, sou a Rafaela Bernardes! 👋

Sou estudante de Análise e Desenvolvimento de Sistemas no ensino superior e também estou cursando Programação Web pelo PROA como aluna Proane. Tenho paixão por aprendizado e evolução, além de ser esforçada e determinada em tudo o que faço.

💻 Interesses Profissionais

Desenvolvedora Full Stack: Interesse em atuar como Analista e Desenvolvedora de Sistemas, tanto no Front-end quanto no Back-end.

📔💙Atualmente Estou me Aprofundando em:

Java e Banco de Dados: Desenvolvendo habilidades avançadas em programação orientada a objetos e gestão de dados.

Desenvolvimento Web: Criando sistemas web robustos utilizando HTML, CSS e JavaScript.

UI/UX Design: Projetando interfaces centradas no usuário com Figma.

💞️ Objetivos

Estou em busca de mais aprendizado e evolução, sempre buscando aprimorar minhas habilidades técnicas. Adoro trabalhar em projetos colaborativos e estou sempre aberta a novas ideias e desafios.

  <div align="center">
    <a href="https://github.com/rafabernardess">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=rafabernardess&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rafabernardess&layout=compact&langs_count=7&theme=dark"/>
</div>
      
<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-plain.svg">
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>

  ##
  ## Minhas Redes de Contato:
  
<div>
    <a href="https://www.instagram.com/rafabernardess_/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
    <a href="https://www.linkedin.com/in/rafaela-bernardes-05b4652b5/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  </div>

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
          github_user_name: rafabernardess
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  



