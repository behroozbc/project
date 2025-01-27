---
layout: cover
title: 'Dynamic Time Warping and Tempo Analysis in Music'
subtitle: 'Understanding Musical Sequences'
presenter: 'Mozhgan & Behrooz'
---

# What is the possible meaning of 2nd Derivative.
## Understanding Musical Sequences
### Presenter: Mozhgan & Behrooz
---

<toc></toc>

---

# Introduction

<v-clicks>

- Objective: we try to find a meaning of the 2nd derivative of tempo curve. 

- why: The idea came from physics. The 2nd derivative of location chart (x) is the acceleration. so we can apply the same.  
</v-clicks>


---
layout: center
---
# Dynamic Warping Path and Tempo

<style>
    img{
        background: #fff;
        width:300px;
        display: inline;
        height: 300px;
        margin:10px;
    }
    p{
        display:inline;
    }
    </style>


![DTW Path](./imgs/dtw.png)

![Tempo Graph](./imgs/tempo.png)



---
layout: center
---

<style>
    img{
        background: #fff;
        width:300px;
        display: inline;
        height: 300px;
        margin:10px;
    }
    p{
        display:inline;
    }
    </style>

# First Derivative of Tempo


![First Derivative](./imgs/first-derivative-graph.png)

![2nd Derivative](./imgs/output.png)

---

# Example from FMP Notebook

![Piano Roll](./imgs/piano-role.jpg)


---

# Observations from Chart

![Detailed Chart](./imgs/chart-human-vs-roll.png)

- Points about rapid valleys leading to speed increases.
- Consistency in local valleys.

---

# Challenges with Performers Comparison

- Issues with fluctuating tempo curves.
- Limitation in data due to only analyzing the first 30 seconds.
- Challenges with differentiation due to discontinuities.

---

# Limitations

- Time constraints
- Conversion issues from Music XML to CSV
- Lack of comprehensive musical information

---

# Future Work

- Further comparisons between piano roll and performers.
- Exploration of datasets with more continuous tempo curves.

---

# Conclusion

- Recap of findings
- Thank you note

---

# Q&A

Open for questions from the audience.