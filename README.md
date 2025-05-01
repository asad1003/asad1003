<h1 align="center">Hi 👋, I'm Asad Ahmed</h1>
<h3 align="center">A passionate Android app developer from Bnagladesh</h3>

- 🌱 I’m currently learning **Flutter, iot**

- 👯 I’m looking to collaborate on **Android native and hydride app**

- 👨‍💻 All of my projects are available at [asad1003](asad1003)

- 💬 Ask me about **Everything**

- 📫 How to reach me **fahimanuri60@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://fb.com/facebook.com/profile.php?id=100078980270381" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="facebook.com/profile.php?id=100078980270381" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/https://www.youtube.com/@asadzone522" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="https://www.youtube.com/@asadzone522" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> </p>

name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"  # Runs every day at midnight UTC
  workflow_dispatch:      # Allows you to run the workflow manually

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate GitHub Snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: asad1003
          outputs: |
            dist/github-contribution-grid-snake.svg

      - name: Push SVG to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/bikash , +8801313915666"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="bikash , +8801313915666" /></a></p><br><br>
