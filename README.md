### Olá, eu me chamo Bruno - bsousanascimento🤓
### Sou apaixonado por tecnologia, estou estudando para ser 
### um desenvolvedor front-and!
### Já chego lá...


![SKills](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
)
![SKills](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
)
![SKill](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCbyE8crMMP4vX0W_HdBCsNA)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://m.facebook.com/Bsousanascimento-324602435120475/) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white
)](https://www.instagram.com/bsousanascimento/)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
)](https://www.linkedin.com/in/bruno-de-sousa-nascimento-971689191/?originalSubdomain=br) [![outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](https://outlook.live.com/mail/0/bsousanascimento@outlook.com)
[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
](https://github.com/bsousanascimento/)
[![Whatsapp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white
)](https://wa.me/+5521966702225)


[![bsousanascimento GitHub stats](https://github-readme-stats.vercel.app/api?username=bsousanascimento )](https://github.com/bsousanascimento/github-readme-stats)

 
 ​name​: ​Generate Datas 
  
 ​on​: 
 ​  ​schedule​: ​#​ execute every 12 hours 
 ​    - ​cron​: ​"​* */12 * * *​" 
 ​  ​workflow_dispatch​: 
  
 ​jobs​: 
 ​  ​build​: 
 ​    ​name​: ​Jobs to update datas 
 ​    ​runs-on​: ​ubuntu-latest 
 ​    ​steps​: 
 ​      ​#​ Snake Animation 
 ​      - ​uses​: ​Platane/snk@master 
 ​        ​id​: ​snake-gif 
 ​        ​with​: 
 ​          ​github_user_name​: ​rafaballerini 
 ​          ​svg_out_path​: ​dist/github-contribution-grid-snake.svg 
  
 ​      - ​uses​: ​crazy-max/ghaction-github-pages@v2.1.3 
 ​        ​with​: 
 ​          ​target_branch​: ​output 
 ​          ​build_dir​: ​dist 
 ​        ​env​: 
 ​          ​GITHUB_TOKEN​: ​${{ secrets.GITHUB_TOKEN }}
