<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Hi%20I'm%20Vidhi&fontSize=50"/>

</div>

<h1 align="center">
Hi 👋 I'm Vidhi
</h1>

<h3 align="center">
MCA Student | Full Stack Developer | Open Source Contributor
</h3>


<p align="center">

I love building modern web applications  
and solving real world problems.

Currently exploring:

- Machine Learning
- Backend Development
- Open Source Contributions

</p>

## 🛠️ Tech Stack


### Languages

![C++](https://img.shields.io/badge/C++-black?style=for-the-badge&logo=cplusplus)
![JavaScript](https://img.shields.io/badge/javascript-black?style=for-the-badge&logo=javascript)
![Python](https://img.shields.io/badge/python-black?style=for-the-badge&logo=python)

### Frontend
![React](https://img.shields.io/badge/react-black?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/next.js-black?style=for-the-badge&logo=next.js)

### Backend
![Node.js](https://img.shields.io/badge/node.js-black?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/express-black?style=for-the-badge&logo=express)

### Database
![MongoDB](https://img.shields.io/badge/mongodb-black?style=for-the-badge&logo=mongodb)

<p align="center">

<img 
src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&rank_icon=github"
height="180"
/>

</p>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=donut&theme=tokyonight"/>

name: Generate Snake

on:
 schedule:
   - cron: "0 */12 * * *"

jobs:
 snake:
  runs-on: ubuntu-latest

  steps:
   - uses: Platane/snk@v3
     with:
       github_user_name: vidhimeshram
       outputs: |
        dist/github-contribution-grid-snake.svg

 



