<!-- Using HTML and CSS to customize the appearance of your profile -->
<style>
  body {
    background-color: #333;
    color: #fff;
    font-family: 'Roboto', sans-serif;
  }
  h1, h2, h3 {
    color: #fff;
  }
  a {
    color: #1e90ff;
  }
</style>

<!-- Using Markdown to add content and formatting to your profile -->
# Your Name

A software developer with a passion for creating intuitive and efficient solutions.

## Skills
- Java
- Python
- HTML/CSS
- JavaScript

## Experience
- Software Developer Intern at XYZ Company (Summer 2020)
- Full-Stack Developer at ABC Company (2019-2020)

## Projects
- [Project Name](https://github.com/USERNAME/project-name) - A brief description of the project goes here.
- [Another Project](https://github.com/USERNAME/another-project) - Another brief description goes here.

## Repositories
- [Repo Name](https://github.com/USERNAME/repo-name) - A brief description of the repository goes here.
- [Another Repo](https://github.com/USERNAME/another-repo) - Another brief description goes here.

## Contact
- Email: yourname@example.com
- LinkedIn: [Your Name](https://www.linkedin.com/in/your-name/)
- Twitter: [@yourname](https://twitter.com/yourname)

<!-- Using a GitHub widget to showcase your activity and contributions -->
## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME)](https://github.com/USERNAME)

<!-- Using JavaScript to add an interactive element to your profile -->
## Fun Fact

<button onclick="displayFact()">Click here to see a fun fact</button>

<div id="fact"></div>

<script>
  const facts = [
    "I am a certified scuba diver.",
    "I have climbed to the top of a mountain.",
    "I can play the piano.",
    "I have traveled to 5 different countries."
  ];

  function displayFact() {
    const fact = facts[Math.floor(Math.random() * facts.length)];
    document.getElementById("fact").innerHTML = fact;
  }
</script>
