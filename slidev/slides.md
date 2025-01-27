---
theme: academic
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

- **Objective**: we try to find a meaning of the 2nd derivative of tempo curve. 

- **Why**: The idea came from physics. The 2nd derivative of location chart (x) is the acceleration. so we can apply the same.  
</v-clicks>


---
layout: two-cols
---

# Dynamic Warping Path 

<style>
    img{
        background: #fff;
        width:300px;
        height: 300px;
        margin:10px;
    }
    </style>


![DTW Path](./imgs/dtw.png)

::right::
# Tempo
![Tempo Graph](./imgs/tempo.png)



---
layout: two-cols
---

<style>
    img{
        background: #fff;
        width:300px;
        height: 300px;
        margin:10px;
    }
    p{
        display:inline;
    }
    </style>

# 1st Derivative of Tempo


![First Derivative](./imgs/first-derivative-graph.png)
::right::
# 2nd Derivative
![2nd Derivative](./imgs/output.png)




---

# Example from FMP Notebook

<style>
img{
        background: #fff;
        width:4500px;
        height: 450px;
    }
</style>

![Piano Roll](./imgs/piano-role.jpg)

---

# Observations from Chart

- Points about rapid valleys leading to speed increases.
- Consistency in local valleys.
---
layout: center
---

<style>
img{
        background: #fff;
        width:500px;
        height: 500px;
    }
</style>
![Detailed Chart](./imgs/chart-human-vs-roll.png)
---

# Challenges with Performers Comparison

<v-clicks>

- Issues with fluctuating tempo curves.
- Limitation in data due to only analyzing the first 30 seconds.
- Challenges with differentiation due to discontinuities.

</v-clicks>
---
layout: center
---

<style>
img{
        background: #fff;
        width:500px;
        height: 500px;
    }
</style>
![Detailed Chart](./imgs/human-vs-human.png)
---

# Limitations
<v-clicks>

- Time constraints
- Conversion issues from Music XML to CSV
- Lack of comprehensive musical information

</v-clicks>
---

# Future Work

<v-clicks>

- Further comparisons between piano roll and performers.
- Exploration of datasets with more continuous tempo curves.
</v-clicks>



---

# Q&A

- Thank you note
Open for questions from the audience.