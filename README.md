<div>
  <h2>About me &#x1f468;</h2>
  <ul>
    <li>Front-end Developer at <a href="https://www.eruda.com.br">Eruda</a></li>
    <li>Graduating in Computer Science at <a href="https://portal.ifba.edu.br/jacobina">IFBA</a></li>
  </ul>

  ```typescript
  type Job = {
    position: string;
    title: string;
    company: string;
    time?: string;
  }
  
  type Graduation = {
    name: string;
    institution: string;
    semester: number;
  }
  
  type Person = {
    age?: number;
    name: string;
    fullName: string;
    job?: Job;
    graduation?: Graduation;
  }
  
  const me: Person = {
    name: "Gabriel",
    fullName: "Gabriel Cavalcante de Jesus Oliveira",
    job: {
      position: "Intern",
      title: "Front-end Software Developer",
      company: "Eruda",
      time: "0Y 2M 15D"
    },
    graduation: {
      name: "Licenciatura em Computação",
      institution: "IFBA (Instituto Federal de Educação, Ciência e Tecnologia da Bahia)",
      semester: 7
    }
  }

  function selfPresentation(me: Person): void {
    console.info(`Hello!, my name is ${me.name}!`);
    console.info(`I'm ${me.job.title} at ${me.job.company}!`);
    console.info(`I'm cursing ${me.graduation.name} at ${me.graduation.institution}!`);
  }

  selfPresentation(me);

  >> Hello!, my name is Gabriel!
  >> I'm Front-end Software Developer at Eruda!
  >> I'm cursing Licenciatura em Computação at IFBA (Intituto Federal de Educação, Ciência e Tecnologia da Bahia)!
  ```
 
  <h2>Languages & Tools (Web) &#x1f4bb;</h2>

  <ul>
    <li>HTML5</li>
    <li>CSS3</li>
    <li>SASS</li>
    <li>JavaScript</li>
    <li>TypeScript</li>
    <li>Bootstrap</li>
    <li>React</li>
    <li>React Native</li>
  </ul>

  <br>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="55px" />
  <br>
  <br>

  <h2>Languages & Tools (Others) &#x1f4bb;</h2>
  <ul>
    <li>SQL</li>
    <li>Java</li>
    <li>C</li>
    <li>Git e GitHub</li>
    <li>Shell Script</li>
  </ul>

  <br>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="55px" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" width="55px" />
  <br>
  <br>
  <p>Note: these are not the only languages/tools I know, but they are the ones I know I have the most command of.</p>
</div>

<div>
  <h2>Achievements &#x1f3c6;</h2>

  <ul>
    <li>Top 2341 of 519241 on Beecrowd</li>
    <li>LinkedIn Seal of Competency in C Language</li>
    <li>LinkedIn Seal of Competency in Shell Script Language</li>
  </ul>
</div>

<div>
  <h2>Social &#x1fac2</h2>

  <ul>
    <li><a href="https://www.beecrowd.com.br/judge/pt/profile/853225">Beecrowd</a></li>
    <li><a href="mailto:gabriel.lcifba@gmail.com">G-mail</a></li>
    <li><a href="https://www.linkedin.com/in/zolppy">LinkedIn</a></li>
    <li><a href="http://wa.me/5574981343313">WhatsApp</a></li>
  </ul>
</div>

<div>
  <h2>Others &#x1f4da</h2>

  <ul>
    <li><a href="https://zolppy.github.io/zolppy">Curriculum Vitae</a></li>
    <li><a href="https://drive.google.com/drive/folders/1d0CI4v6SahD471GgcGoZ1BvCuf5F-Am-?usp=drive_link">Certificates</a></li>
  </ul>
</div>
