---
layout: page
title: "Courses Taught"
permalink: /courses
hero_height: is-small
---

# University of Nebraska-Lincoln

#### Faculty Instructor of Record

- STAT 462: Introduction to Mathematical Statistics I: Distribution Theory
  - 4 Student Credit Hours, 60 Student-Contact Hours
  - Times Taught: 3
  - Total Students: 109
  - Last Taught: Fall 2024
    - <button class="show-hide-btn" onclick="toggleContent(this, 'description462')">Show Description</button>
    <div class="course-description hidden-content" id="description462">
    Sample space, random variable, expectation, conditional probability and independence, moment generating function, special distributions, sampling distributions, order statistics, limiting distributions, and central limit theorem.
    </div>
- STAT 380: Statistics and Applications
  - 3 Student Credit Hours, 45 Student-Contact Hours
  - Times Taught: 6
  - Total Students: 436
  - Last Taught: Spring 2023
    - <button class="show-hide-btn" onclick="toggleContent(this, 'description380')">Show Description</button>
    <div class="course-description hidden-content" id="description380">
    Probability calculus; random variables, their probability distributions and expected values; t, F and chi-square sampling distributions; estimation; testing of hypothesis; and regression analysis with applications.
    </div>
- STAT 218: Introduction to Statistics
  - 3 Student Credit Hours, 45 Student-Contact Hours
  - Time Taught: 1
  - Total Students: 30
  - Last Taught: Fall 2021
    - <button class="show-hide-btn" onclick="toggleContent(this, 'description218')">Show Description</button>
    <div class="course-description hidden-content" id="description218">
    The practical application of statistical thinking to contemporary issues; collection and organization of data; probability distributions; statistical inference; estimation; and hypothesis testing.
    </div>
- STAT 101: Introduction to Data
  - 3 Student Credit Hours, 45 Student-Contact Hours
  - Times Taught: 1
  - Total Students: 24
  - Last Taught: Fall 2024
    - <button class="show-hide-btn" onclick="toggleContent(this, 'description101')">Show Description</button>
    <div class="course-description hidden-content" id="description101">
    An introduction to statistics through exploratory data analysis and data visualization. Topics include data types, chart types, methods for working with and reducing data, simple regression, regression diagnostics. Focuses on how to communicate statistical information and how to critically consume statistical information presented in the media and popular press.
    </div>

#### Graduate Student Instructor of Record

- STAT 380: Statistics and Applications
  - <button class="show-hide-btn" onclick="toggleContent(this, 'description380-2')">Show Description</button>
  <div class="course-description hidden-content" id="description380-2">
  Probability calculus; random variables, their probability distributions and expected values; t, F and chi-square sampling distributions; estimation; testing of hypothesis; and regression analysis with applications.
  </div>
- LIFE 120L: Fundamentals of Biology I laboratory
  - <button class="show-hide-btn" onclick="toggleContent(this, 'description120l')">Show Description</button>
  <div class="course-description hidden-content" id="description120l">
  This laboratory will use a systems-based approach to explore the study of life at the cellular level, investigating cellular structures, chemical processes, cell metabolism, cell division, gene expression and introducing patterns of inheritance.
  </div>

---

<!--
# Michigan Technological University

#### Undergraduate Teaching Assistant

-

#### Undergraduate Grading Assistant

---


### STAT 462

Description or details about STAT 462.

### STAT 380

Description or details about STAT 380.

### STAT 101

Description or details about STAT 101.

### Course Name

Description or details about the course at Michigan Technological University.
-->

<script>
    function toggleContent(button, contentId) {
        const content = document.getElementById(contentId);
        const isHidden = content.classList.contains('hidden-content');
        
        if (isHidden) {
            content.classList.remove('hidden-content');
            button.textContent = 'Hide ' + button.textContent.split(' ')[1];
        } else {
            content.classList.add('hidden-content');
            button.textContent = 'Show ' + button.textContent.split(' ')[1];
        }
    }
</script>

<style>
    .hidden-content {
        display: none;
    }
    
    .show-hide-btn {
        background: none;
        border: none;
        color: #3498db;
        cursor: pointer;
        font-weight: 500;
        display: block;
        margin-top: 2px;
        font-size: 0.9rem;
            }
    
    .show-hide-btn:hover {
        text-decoration: underline;
    }
</style>
