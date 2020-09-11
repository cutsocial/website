---
title: 
date: 2020-09-05 19:44:00 +0200
layout: page
---

## 


Balloon Analogue Risk Task
This task is invented Lejuez et al. (2002) to measure risk-taking behavior. A ball that is shown in the middle of the screen. Each time the we tap on the ball, it get pumped a little bigger. With each pump, the subject receives a point. However, there is a risk the ball explodes and the subject loses all of their points in that round. But they can choose to cash out their points and save them before the ball explodes. A demo version of our new implementation is shown below. The code snippet needed to set the options of the task are shown next to it. The experimenter can set the number of rounds and the maximum number of pumps (i.e., in how many pumps the balloon has to explode).


<div class="demo-container">
  <iframe src="https://lens.cut.social/#/bart/en" frameborder="0" allowfullscreen=""></iframe>
</div>

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h2>Two Equal Columns</h2>

<div class="row">
<div class="demo-container">
  <iframe src="https://lens.cut.social/#/bart/en" frameborder="0" allowfullscreen=""></iframe>
</div>
<div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>
