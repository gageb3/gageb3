Hi ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif)My name is Gage Bays
=================================================================================================================================

Web Developer and Designer
--------------------------

<p align="center">
  <img src="https://i0.wp.com/therebelwalk.com/wp-content/uploads/2024/02/IMG_0436.jpg?resize=1242%2C640&ssl=1" width="350"/>
</p>



I have learned to code within web development, python, and java. I also have knowledge of databases, cybersecurity, and networking.



* 🌍  I'm based in Florence, AL
* ✉️  You can contact me at [gagebays@gmail.com](mailto:gagebays@gmail.com)
* 🚀  I'm currently working on [Dev Charlie](http://gageb3.github.io/dev-charlie/)
* 🧠  I'm learning HTML
* 🤝  I'm open to collaborating on Anything
* www.linkedin.com/in/gage-bays-6bb231355


### Skills


<p align="left">
<a href="https://www.oracle.com/java/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/java-colored.svg" width="36" height="36" alt="Java" /></a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a><a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a><a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/visualstudiocode.svg" width="36" height="36" alt="VS Code" /></a><a href="https://www.vim.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/vim.svg" width="36" height="36" alt="Vim" /></a><a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a><a href="https://jquery.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/jquery-colored.svg" width="36" height="36" alt="JQuery" /></a><a href="https://getbootstrap.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/bootstrap-colored.svg" width="36" height="36" alt="Bootstrap" /></a><a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="36" height="36" alt="CSS3" /></a><a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" /></a><a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/googlecloud-colored.svg" width="36" height="36" alt="Google Cloud" /></a>
</p>


### Socials

<p align="left"> <a href="https://www.github.com/gageb3" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /> </picture> </a> <a href="http://www.instagram.com/gagebays_3" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" width="32" height="32" /> </picture> </a></p>


# dev-fox
🖥️ Dev Baker Lab Layout

"A visual layout of the Dev Baker computer lab, built with HTML, CSS, and JavaScript." 🧑‍💻

👤 Authorship & Attribution

Project by: Gage B

Project Repo: Dev Baker Project

Live Site: https://gageb3.github.io/dev-baker-project/

"This project was created for a web development course to represent a real-world classroom layout using code."

"The Dev Baker Lab Layout is a visual web-based representation of a real-life computer lab. It helps viewers understand the physical desk/seating arrangement using interactive or programmatically generated elements."

Features:

🖥️ Dynamic or static computer station layout

📐 Responsive grid and styling

🔍 Visual reference for seat/desk placement

🧪 Console logs for layout interaction (if applicable)

🐢 Optional mascot image for class personality

- Built using vanilla HTML/CSS/JS
- May use JS to dynamically generate layout
- Designed for responsive viewing of physical computer lab layout
- Mascot image and style optional, for personality or flair
  
```markdown
<details>
<summary>🧠 Draggable and Positioning Code (click to expand)</summary>

<h4>Original Version</h4>
```JavaScript
<pre><code class="language-javascript">
$(document).ready(function() {
  console.log("Welcome to the Interactive Computer Lab!");

  $(".seat").draggable({ containment: "#computerLab" });
  $(".pc").draggable({ containment: "#computerLab" });
  $("#door").draggable({ containment: "#computerLab" });

  $(document).on("click", (event) => {
    let clickedId = event.target.id;
    if (clickedId) {
      alert("Clicked: " + clickedId);
      let $clickedElement = $('#' + clickedId);
      alert("Top position: " + $clickedElement.position().top);
      console.log("Element: ", clickedId, "Left: ", $clickedElement.position().left);
    }
  });
});

</code></pre>

<h4>Refactored Version</h4>

<pre><code class="language-javascript">
$(function () {
  console.log("👋 Welcome to the Interactive Computer Lab!");

  const draggableSelectors = [".seat", ".pc", "#door"];
  draggableSelectors.forEach(selector => {
    $(selector).draggable({ containment: "#computerLab" });
  });

  $(document).on("click", (event) => {
    const clickedId = event.target.id;
    if (!clickedId) return;

    const $element = $("#" + clickedId);

    alert(`🖱️ Clicked: ${clickedId}\\nTop: ${$element.position().top}px`);
    console.log(`🖱️ Clicked: ${clickedId}, Left: ${$element.position().left}px`);
  });
});
</code></pre>
```

### Summary of Improvements:
- Makes <code>.seat</code>, <code>.pc</code>, and <code>#door</code> elements <strong>draggable</strong>  
- Logs and alerts <strong>element positions</strong>  
- Uses a <code>forEach</code> loop for cleaner, reusable code  
- Improves user feedback with <strong>template literals</strong> and <strong>emojis</strong>

</details>

### 💬 Quote  
> “Design is not just what it looks like — it’s how it works.”  
> — **Steve Jobs**
