---
num: "lect10"
desc: "Big-Oh: Analyzing the efficiency of algorithms"
ready: false
pdfurl: /lectures/CS24_Lecture10.pdf
annotatedpdfurl: /lectures/CS24_Lecture10_ann.pdf
annotatedready: true
lecture_date: 2019-10-31
---

## Code written in class
[{{site.lect_repo}}/tree/master/{{ page.lecture_date | slice: 5, 5 }}]({{site.lect_repo}}/tree/master/{{ page.lecture_date | slice: 5, 5 }})
# Topics

* Challenges in measuring time efficiency and the pros/cons of different methods - absolute time, counting steps 
* Measuring the impact of algorithms on running time (independent of implementation details/hardware/compiler....etc) - Count steps by detailed computer model of times to fetch, store, assign … 
* O notation - Big Oh - asymptotic analysis and orders of growth, but also briefly Little O, Big Omega, Big Theta
* Formal Big O - formula and graphical presentation
* Complexity classes - constant, logarithmic, exponential, linear, quadratic, cubic
* Best case, worst case, average case
* Example algorithms
