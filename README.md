 <h3 align="left"> Hi, everyone!👋</h3>

<div style="background-color: #f9f9f9; padding: 20px; border-radius: 10px;">
  <h3 style="text-align: center;">Utilisation des Technologies</h3>
  
  <div style="display: flex; justify-content: center;">
    <div style="width: 300px; margin-right: 20px;">
      <h4>Langages de Programmation</h4>
      <canvas id="programming-languages-chart"></canvas>
    </div>
    <div style="width: 300px;">
      <h4>Frameworks</h4>
      <canvas id="frameworks-chart"></canvas>
    </div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  // Données de test pour les graphiques
  const programmingLanguagesData = {
    labels: ['Java', 'JavaScript', 'Python', 'C#', 'C++'],
    datasets: [{
      label: 'Utilisation',
      data: [50, 30, 20, 15, 10],
      backgroundColor: [
        'rgba(255, 99, 132, 0.2)',
        'rgba(54, 162, 235, 0.2)',
        'rgba(255, 206, 86, 0.2)',
        'rgba(75, 192, 192, 0.2)',
        'rgba(153, 102, 255, 0.2)',
      ],
      borderColor: [
        'rgba(255, 99, 132, 1)',
        'rgba(54, 162, 235, 1)',
        'rgba(255, 206, 86, 1)',
        'rgba(75, 192, 192, 1)',
        'rgba(153, 102, 255, 1)',
      ],
      borderWidth: 1
    }]
  };

  const frameworksData = {
    labels: ['Spring Boot', 'React', 'Vue.js', 'Angular', 'Express.js'],
    datasets: [{
      label: 'Utilisation',
      data: [40, 35, 25, 20, 15],
      backgroundColor: [
        'rgba(255, 99, 132, 0.2)',
        'rgba(54, 162, 235, 0.2)',
        'rgba(255, 206, 86, 0.2)',
        'rgba(75, 192, 192, 0.2)',
        'rgba(153, 102, 255, 0.2)',
      ],
      borderColor: [
        'rgba(255, 99, 132, 1)',
        'rgba(54, 162, 235, 1)',
        'rgba(255, 206, 86, 1)',
        'rgba(75, 192, 192, 1)',
        'rgba(153, 102, 255, 1)',
      ],
      borderWidth: 1
    }]
  };

  // Création des graphiques
  const programmingLanguagesChart = new Chart(document.getElementById('programming-languages-chart'), {
    type: 'bar',
    data: programmingLanguagesData,
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });

  const frameworksChart = new Chart(document.getElementById('frameworks-chart'), {
    type: 'bar',
    data: frameworksData,
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>








<h3 align="left">Continuously honing my skills in web development through the use of :</h3>
<p align="left">
  <a href="https://www.java.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  </a> 
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  </a>
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
  </a>
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
  </a>
  <a href="https://vuejs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/>
  </a>
  <a href="https://babel.dev/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/babel/babel-original.svg" alt="babel" width="40" height="40"/>
  </a>
  <a href="https://spring.io/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/>
  </a>
  <a href="https://nodejs.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
  </a>
  <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/>
  </a>
</p>




