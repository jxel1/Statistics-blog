---
layout: post
title: "Statistics Homework: Datasets, Distributions, and Frequency Analysis in Cybersecurity"
date: 2025-10-12
---

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>



<canvas id="originalChart" width="400" height="200"></canvas>
<script>
const ctxOriginal = document.getElementById('originalChart').getContext('2d');
const originalData = {
  labels: ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z'],
  datasets: [{
    label: 'Letter Frequency (%)',
    data: [8.33, 1.41, 2.21, 4.27, 11.84, 2.14, 2.13, 5.91, 7.13, 0.11, 0.94, 4.19, 2.74, 6.97, 7.87, 1.54, 0.09, 5.28, 6.08, 9.16, 3.07, 1.25, 2.49, 0.14, 2.65, 0.08],
    backgroundColor: 'rgba(75, 192, 192, 0.2)',
    borderColor: 'rgba(75, 192, 192, 1)',
    borderWidth: 1
  }]
};
new Chart(ctxOriginal, { type: 'bar', data: originalData, options: { scales: { y: { beginAtZero: true } } } });
</script>
