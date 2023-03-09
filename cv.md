### rsschool-cv

# Viktoria Krasavceva

### Junior Frontend Developer

---

#### CONTACTS:

- **Address:** P.Mstislavca st. Minsk, Belarus
- **Phone:** +375(29)6319584
- **E-mail:** krasavceva.va@gmail.com
- **LinkedIn:** [Krasavceva Viktoria](https://www.linkedin.com/feed/)
- **GitHub:** [Krasavceva](https://github.com/Krasavceva/)

---

#### SUMMARY:

<p>I'm a beginner front-end developer with experience in projects.<p/>
<p>I have strong creative and analytical skills.</p>
<p>I have always been interested in computers and everything connected with them. In the 10th grade, I independently studied and made up my first site for the game "World of Warcraft"))</p>
<p>I was working for a long time in a senior position in a construction company, at the same time she studied fronted. I always wanted to work in IT, because. I am very attracted by the prospect of constantly developing and working remotely.</p>
I would like to work in a great team. Ready for remote work, office work and even relocation in the future

---

#### SKILLS AND PROFICIENCY:

- HTML5, CSS3(Bootstrap, SCSS, BEM, Flex, Grid)
- JavaScript ES6+ (Basics, DOM, JSON, AJAX)
- React JS
- Git, GitHub
- MobX
- Figma(for web development)
- Agile, Scrum

---

#### CODE EXAMPLE:

<pre>async function loadData() {
  let response = await fetch(
    "https://api.nasa.gov/planetary/apod?api_key=9WXzy1UhmfPiAeNiMwkzpyAun9Bj0k3Jthyzalwm"
  );
  let data = await response.json();
  return data;
}

function render(data) {
  let resultNode = document.createElement("div");
  let imgNode = document.createElement("img");
  imgNode.src = data.hdurl;
  imgNode.width = 100;

  let pNode = document.createElement("p");
  pNode.textContent = data.title;

  let explanation = document.createElement("text");
  explanation.textContent = data.explanation;

  resultNode.append(pNode);
  resultNode.append(imgNode);
  resultNode.append(explanation);
  document.body.append(resultNode);
}

//весь стартовый код пишем внутри асинхронной функции
async function initApp() {
  let data = await loadData();
  render(data);
}

//вызываем функцию
initApp();</pre>

---

#### EDUCATION:

- University: Francisk Skorina Gomel State University, Jurisprudence major
- Courses: [ITGirlschool](https://itgirlschool.com/frontend-developer): Frontend Development

---

#### EXPERIENCE:

FRONTEND DEVELOPER | Project employment

- Built the logic for an English flashcards App with React. (independent project) (stack: react, hooks, html, css, sass, MobX)
- Developed several responsive pages for Chess Club with SPA logic using JS(Stack: JS, html, css, sass)
- Experience in projects as a team leader
- Extensive experience in website development

---

#### LANGUAGES:

- **Russian** - Basic
- **Belarussian** - Basic
- **English** - Pre-Intermediate
