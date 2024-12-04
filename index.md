---
layout: default
---

<div class="container">
  <div class="left-column">
    <img src="{{ site.profile.picture }}" alt="Profile Picture" />
    <h1>{{ site.profile.name }}</h1>
    <h2>{{ site.profile.title }}</h2>
    <p>Email: {{ site.profile.email }}</p>
    <p>Phone: {{ site.profile.phone }}</p>
    <p>LinkedIn: <a href="{{ site.profile.linkedin }}">{{ site.profile.linkedin }}</a></p>
    <p>GitHub: <a href="{{ site.profile.github }}">{{ site.profile.github }}</a></p>
  </div>
  <div class="right-column">
    <h2>Projects</h2>
    <h3>Project 1: Data Visualization Dashboard</h3>
    <p>Description: A dashboard that visualizes sales data using Python and Tableau.</p>
    <p>Technologies: Python, Tableau, SQL</p>
    <p>Link: <a href="https://github.com/yourusername/project1">View Project</a></p>

    <h3>Project 2: Predictive Analytics Model</h3>
    <p>Description: A predictive model built using machine learning techniques to forecast sales.</p>
    <p>Technologies: Python, scikit-learn, Pandas</p>
    <p>Link: <a href="https://github.com/yourusername/project2">View Project</a></p>
  </div>
</div>
