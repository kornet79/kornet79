<h1 display="flex" align="center">👋  My name is Guymin and I'm hoping for the DevOps.</h1>

<img width="100%" loading="lazy" src="https://github.com/SamirPaulb/SamirPaulb/blob/main/assets/rainbow-superthin.webp" />
<p align="left"> <img src="https://komarev.com/ghpvc/?username=wlstmd&label=Profile%20views&color=0e75b6&style=flat" alt="wlstmd" /> </p>
name: kornet79

on:
  # run automatically every 24 hours
  schedule:
    - cron: "0 */24 * * *" 
  
  # allows to manually run the job at any time
  workflow_dispatch:
  
  # run on every push on the master branch
  push:
    branches:
    - master
    
  

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    
    steps:
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: {kornet79}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      # push the content of <build_dir> to a branch
      # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GH_TOKEN }}
```json
{
    "Name": "Gyumin kim",
    "Birthday": "2007.10.27",
    "School": "sungil infomaincn High School",
    "Tech": ["Cloud", "Backend"],
    "Skills": ["AWS", "Docker", "NestJS", "JAVA", "Python", "Node.js", "React"],
    "Awards": [ "test"
    ],
    "Certificate": [
        { "name": "ITQ", "IssuedAt": "2023년 9월 25일", "Number": "23403250566P" },
        { "name": "정보처리산업기사", "IssuedAt": "과정형 평가중", "Score": "94.6" }
    ],
    "MostLanguage": ["JAVA", "Go", "Python", "Django"],
    "MyBlog": "https://blog.naver.com/jinseung0327",
    "Discord": "https://discord.com/users/648462033775362061"
}
```

<div style="display: flex;">
    <img src="contributions.svg"/>
</div>

<br />

<details>
  <summary>Github-Profile-Trophy (click me) </summary>
  
![](https://github-profile-trophy.vercel.app/?username=kornet79&row=1&column=8&theme=nord)
  
</details>

<details>
    <summary>Github-README-Stats (click me) </summary>
    <div style="display: flex; align-items: center; margin-top: 30px;">
        <img style="width: 380px; border: none;" src="https://github-readme-stats.vercel.app/api?username=kornet79&show_icons=true&theme=tokyonight" />
        <img style="width: 289px; border: none;" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kornet79&layout=compact&theme=tokyonight" />
    </div>
</details>






<div align="center">
  <img src="[https://cdn.discordapp.com/attachments/1181568622150299761/1216693240384851978/image.png?ex=6613c5e1&is=660150e1&hm=2de02346070a25823849b41c131b1176af245fc18084969473ce3de5eed0bb05&]" />
</div>
 <br>

 language. <br><br>
![](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![]([https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white))
![](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)
[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=First+line+of+text;Second+line+of+text)](https://git.io/typing-svg)

<br><br>
engine <br><br>
![](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)
![](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![](<img src="https://img.shields.io/badge/Node.js?style=for-the-badge&logo=#339933&logoColor=white">)

<br><br><br>

My fist WEB : https://indelibleinexperiencedclients--kky7530874.repl.co/

My <br> <br>
[![Solved.ac 프로필](http://mazassumnida.wtf/api/generate_badge?boj={kornet79})](https://solved.ac/{handle}) <br> <br>
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=kornet79&show_icons=true&theme=radical)
<br>
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kornet79&layout=compact)
