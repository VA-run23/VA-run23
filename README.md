- 👋 Hi, I’m @VA-Run
- 👀 I’m interested in ...Problem solving, WebDev, DevOps, CloudComputing, Docker and Kubernetes
- 🌱 I’m currently learning ... Data Structures and Algorithms
- 💞️ I’m looking to collaborate on ... WebDev
- 📫 How to reach me ... 
- 😄 Pronouns: ... He/Him
- ⚡ Fun fact: ...

## Technologies and Tools

![JavaScript](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=2bbc8a)
![Java](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=java&logoColor=white&color=2bbc8a)
![HTML5](https://img.shields.io/badge/Code-HTML5-informational?style=flat&logo=html5&logoColor=white&color=2bbc8a)
![CSS3](https://img.shields.io/badge/Code-CSS3-informational?style=flat&logo=css3&logoColor=white&color=2bbc8a)
![React](https://img.shields.io/badge/Framework-React-informational?style=flat&logo=react&logoColor=white&color=2bbc8a)
![Python](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=2bbc8a)
![Windows](https://img.shields.io/badge/OS-Windows-informational?style=flat&logo=windows&logoColor=white&color=2bbc8a)
![VisualStudioCode](https://img.shields.io/badge/Editor-VisualStudioCode-informational?style=flat&logo=visual-studio-code&logoColor=white&color=2bbc8a)
![EclipseIDE](https://img.shields.io/badge/Editor-EclipseIDE-informational?style=flat&logo=eclipse-ide&logoColor=white&color=2bbc8a)

![](https://komarev.com/ghpvc/?username=VA-run&color=green)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Stats</title>
</head>
<body>
    <h1>GitHub Analytics</h1>

    <div id="stats"></div>

    <script>
        async function fetchGitHubStats() {
            const response = await fetch('https://api.github.com/users/YOUR_USERNAME/repos');
            const repos = await response.json();
            const totalStars = repos.reduce((sum, repo) => sum + repo.stargazers_count, 0);
            const totalCommits = repos.reduce((sum, repo) => sum + repo.commits_url.split('/').length, 0);
            const totalPRs = repos.reduce((sum, repo) => sum + repo.pulls_url.split('/').length, 0);
            const totalIssues = repos.reduce((sum, repo) => sum + repo.issues_url.split('/').length, 0);

            document.getElementById('stats').innerHTML = `
                <h2>My GitHub Statistics</h2>
                <ul>
                    <li><strong>Total Stars:</strong> ${totalStars}</li>
                    <li><strong>Total Commits:</strong> ${totalCommits}</li>
                    <li><strong>Total PRs:</strong> ${totalPRs}</li>
                    <li><strong>Total Issues:</strong> ${totalIssues}</li>
                </ul>
            `;
        }

        fetchGitHubStats();
    </script>
</body>
</html>



