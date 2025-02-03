# 💫 About Me:
👋 Hi, I'm Balaji D – AI/ML Developer 🚀<br>🧠 Innovating with AI | 💡 Solving Real-World Problems | 🌍 Building Intelligent Solutions<br>Passionate about Artificial Intelligence & Machine Learning, I specialize in crafting cutting-edge models that drive automation, intelligence, and impact. From Deep Learning & NLP to Computer Vision & MLOps, I leverage AI to create scalable, high-performance solutions.<br><br>Let’s collaborate, innovate, and shape the future together! 🤖✨<br><br>🔭 Areas of Expertise<br>Machine Learning & Deep Learning 🧠<br><br>End-to-end model development: from research to production<br>Optimization & fine-tuning for performance & scalability<br>Natural Language Processing (NLP) 📖<br><br>Building intelligent chatbots & language-based applications<br>Transformers, LLMs, and multilingual NLP solutions<br>Computer Vision & Image Processing 👀<br><br>Django, Flask: Bridging AI with web technologies<br>WordPress & SEO expertise for optimized web presence<br>🛠 Skills & Technologies<br>🚀 Programming & Frameworks<br><br>🔹 Python | SQL | Bash | Ubuntu<br><br>🧠 AI & Machine Learning<br><br>🔹 TensorFlow | PyTorch | Scikit-Learn | NumPy | Pandas | OpenCV<br><br>🛠 MLOps & Deployment<br><br>🔹 Django | Flask | FastAPI | Git | <br><br>🌍 Web Development & SEO<br><br>🔹 Web Development | WordPress | SEO Optimization


## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/feed/update/urn:li:share:7292052796290293760/) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:balajidevaraj18@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)

name: GitHub Snake Game

on:
  # Schedule the workflow to run daily at midnight UTC
  schedule:
    - cron: "0 0 * * *"
  # Allow manual triggering of the workflow
  workflow_dispatch:
  # Trigger the workflow on pushes to the main branch
  push:
    branches:
      - main
jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      # Step 1: Checkout the repository
      - name: Checkout Repository
        uses: actions/checkout@v3
      # Step 2: Generate the snake animations
      - name: Generate GitHub Contributions Snake Animations
        uses: Platane/snk@v3
        with:
          # GitHub username to generate the animation for
          github_user_name: ${{ github.repository_owner }}
          # Define the output files and their configurations
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
            dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
      # Step 3: Deploy the generated files to the 'output' branch
      - name: Deploy to Output Branch
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./dist
          publish_branch: output
          # Optionally, you can set a custom commit message
          commit_message: "Update snake animation [skip ci]"
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Balaji6382&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=Balaji6382&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Balaji6382&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=Balaji6382&icon=10&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
