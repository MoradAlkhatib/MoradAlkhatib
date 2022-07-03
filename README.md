<h1 align="center">Hi There 👋 Welcome To My GitHub ❤️ Morad Alkhatib ❤️</h1>


<!--
**MoradAlkhatib/MoradAlkhatib** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
<h2 align="center" style="color:red;">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Morad,+25years!+👋;TeacherAssistant..Of;SoftwareDevelopment;**Love->Learning,Teaching.;Hobby-->Sports;Nice+to+meet+you!&center=true&size=30">
  </a>
</h2>

<p align="center">
  <img src="https://media3.giphy.com/media/ln7z2eWriiQAllfVcn/200w.webp" width="100"><img src="https://i.giphy.com/media/LMt9638dO8dftAjtco/200.webp" width="100"><img src="https://i.giphy.com/media/eNAsjO55tPbgaor7ma/200w.webp" width="100"><img src="https://i.giphy.com/media/KzJkzjggfGN5Py6nkT/200.webp" width="100"><img src="https://i.giphy.com/media/IdyAQJVN2kVPNUrojM/200.webp" width="100"><br><br>
  <img src="https://camo.githubusercontent.com/936a08778c7e4885053d148c07bbd2339dfbdd80/68747470733a2f2f6665726f73732e6e65742f782f6e6f6465322e676966" /><br><br>
  
</p>

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MoradAlkhatib&layout=compact)](https://github.com/anuraghazra/github-readme-stats)


[![Typing SVG](https://readme-typing-svg.herokuapp.com?lines=HTML,Css...;JavaScript,React.js,Node.js..;Python,Django,Rest_Framework..;NoSql,Sql,Plsql.)](https://git.io/typing-svg)

iter <- 10000
p <- runif(iter)
coord <- matrix(c(0, 0), ncol = 1)
df <- rbind(data.frame(), t(coord))
for (i in 1:iter) {
    if (p[i] <= 0.05) {
        m <- matrix(c(0, 0, 0, 0.16), nrow = 2, ncol = 2)
        const <- matrix(c(0, 0), ncol = 1)
    } else if (p[i] > 0.05 && p[i] <= 0.86) {
        m <- matrix(c(0.85, -0.04, 0.04, 0.85), nrow = 2, ncol = 2)
        const <- matrix(c(0, 1.6), ncol = 1)
    } else if (p[i] > 0.86 && p[i] <= 0.93) {
        m <- matrix(c(0.2, 0.23, -0.26, 0.22), nrow = 2, ncol = 2)
        const <- matrix(c(0, 1.6), ncol = 1)

    } else {
        m <- matrix(c(-0.15, 0.26, 0.28, 0.24), nrow = 2, ncol = 2)
        const <- matrix(c(0, 0.44), ncol = 1)
    }
    coord <- m %*% coord + const
    df <- rbind(df, t(coord))
}

plot(x = df[, 2], y = df[, 1], plt = c(0, 10, -5, 5), cex = 0.1, asp = 1)



