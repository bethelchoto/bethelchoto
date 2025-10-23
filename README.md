# Bethel Panashe Choto


![Profile Views](https://komarev.com/ghpvc/?username=bethelchoto&label=Profile%20views&color=0e75b6&style=flat)


<div align="center" style="font-family: 'Courier New', Courier, monospace; color: #0e75b6; background: #f5f7fa; padding: 20px; border-radius: 10px; border: 1px solid #ddd;">
  <pre style="font-size: 14px; line-height: 1.4em; color: #0d6efd;">
<span style="color: #dc3545;"> ____       _   _          _    ____ _           _        </span>
<span style="color: #28a745;">| __ )  ___| |_| |__   ___| |  / ___| |__   ___ | |_ ___  </span>
<span style="color: #fd7e14;">|  _ \ / _ \ __| '_ \ / _ \ | | |   | '_ \ / _ \| __/ _ \ </span>
<span style="color: #20c997;">| |_) |  __/ |_| | | |  __/ | | |___| | | | (_) | || (_) |</span>
<span style="color: #6f42c1;">|____/ \___|\__|_| |_|\___|_|  \____|_| |_|\___/ \__\___/ </span>
  </pre>


  <h2 style="margin-top: 20px;">
    <code style="color: #212529; font-size: 18px;">console.log('Senior Software Developer @ Tribetron 🚀')</code>
  </h2>
</div>


---


## 🌐 About Me


Hi! I'm Bethel Panashe Choto, a passionate **Senior Software Developer** specializing in modern web development technologies. My expertise lies in building reliable backend services and polished frontend experiences. I have a keen interest in **Python**, **JavaScript**, **Java**, and I'm always eager to explore new tools and technologies.


### Portfolio
🔗 [Check out my portfolio](https://bethelchoto-portifolio.netlify.app/)


### Blog
📘 [Visit my blog](#) for in-depth articles and tutorials on web development.


---


## 🚀 Skills & Expertise


### 💻 Development
- Full-Stack Development  
- Backend Services & APIs  
- Python, JavaScript, Java, PHP  
- MySQL & Database Management  
- Flask & Web Frameworks  


### 🔧 Other Skills
- Docker & Containerization  
- Google Cloud Platform  
- Computer Vision (OpenCV)  
- Git & Version Control  
- Bootstrap & Frontend Frameworks  


---


### [Get my projects from the shop](#)
- **Tech Stack:** Python, JavaScript, Flask, Docker and lot others more


```javascript
// Backend: Express server (server.js)
const express = require('express');
const mongoose = require('mongoose');
const cors = require('cors');


const app = express();
app.use(cors());
app.use(express.json());


mongoose.connect('mongodb://localhost/myapp', { useNewUrlParser: true, useUnifiedTopology: true });


const TaskSchema = new mongoose.Schema({
  title: String,
  completed: Boolean
});


const Task = mongoose.model('Task', TaskSchema);


app.get('/api/tasks', async (req, res) => {
  const tasks = await Task.find();
  res.json(tasks);
});


app.post('/api/tasks', async (req, res) => {
  const task = new Task(req.body);
  await task.save();
  res.status(201).json(task);
});


app.listen(5000, () => console.log('Server running on port 5000'));
```


## 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=bethelchoto&theme=algolia&hide_border=false&include_all_commits=false&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=bethelchoto&theme=algolia&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=bethelchoto&theme=algolia&hide_border=false&include_all_commits=false&count_private=true&layout=compact)


 ## 💰 You can support me by Donating
  [![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](#) [![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](#) 


---


## 📬 Let's Connect


<div>
  <a href="#" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="https://linkedin.com/in/bethel-panashe-choto/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="#" target="_blank"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" /></a>
  <a href="mailto:chotobethelp@gmail.com"><img src="https://img.shields.io/badge/📧_Email-D14836?style=for-the-badge&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/bethelchoto" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</div>
