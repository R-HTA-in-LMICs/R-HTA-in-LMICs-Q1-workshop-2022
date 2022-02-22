# R-HTA in LMICs: Presentation Workshop 2022
This repository is for the code and decks used by the presenters of the first-quarter R-HTA in LMICs 2022 workshop.

<img src="img/logo.png" width="260" align="right" />

<h1 id = 'first'>Programme </h1>
<h2 id = 'Titles'>Introduction</h2>
<body>
<b>Presenters: Co-chairs of R-HTA in LMICs</b>
<p>
An introduction to the inaugral R-HTA in LMICs workshop. The co-chairs discuss the motivations behind the chapter and introduce the team.
</p>
<h2 id = 'Titles'>Getting Started with Github and R</h2>
<body>
<b>Presenter: <a href = "https://jsoboil.github.io/">Joshua Soboil<a/></b>
<p>
A brief overview and tutorial on using Github with R and Rstudio.
</p>
See the R-HTA in LMICs <a href = "https://github.com/R-HTA-in-LMICs/Getting-Started-with-Github-and-R">Github repo<a/>
</body>
<h2 id = 'Titles'>BCEA: making decision modelling in R more user-friendly</h2>
<body>
<b>Presenter: <a href="https://www.ucl.ac.uk/statistics/dr-nathan-green">Dr Nathan Green<a/></b>
<p>
An introduction to the BCEA package and how it enables more user-friendly health economic decision modelling in R.
</p>
<a href = "https://cran.r-project.org/web/packages/BCEA/index.html">CRAN link<a/>
</body>
<h2 id = 'Titles'>The Potential of R Shiny User Interfaces to Support Health Economic Decision Making</h2>
<body>
<b>Presenters: <a href = "https://www.bresmed.com/team/rose-hart/">Rose Hart<a/> and <a href = "https://www.sheffield.ac.uk/scharr/people/pgr-students/robert-smith">Robert Smith<a/></b>
<p>
Health economic evaluation models have traditionally been built in Microsoft Excel, but more sophisticated tools are increasingly being used as model complexity and computational requirements increase. Of all the programming languages, R is most popular amongst health economists because it has a plethora of user created packages and is highly flexible. However, even with an integrated development environment such as R Studio, R lacks a simple point and click user interface and therefore requires some programming ability. This might make the switch from Microsoft Excel to R seem daunting, and it might make it difficult to directly communicate results with decisions makers and other stakeholders.
</p>
<p>
The R package Shiny has the potential to resolve this limitation. It allows programmers to embed health economic models developed in R into interactive web browser based user interfaces. Users can specify their own assumptions about model parameters and run different scenario analyses, which, in the case of regular a Markov model, can be computed within seconds. This paper provides a tutorial on how to wrap a health economic model built in R into a Shiny application. We use a four-state Markov model developed by the Decision Analysis in R for Technologies in Health (DARTH) group as a case-study to demonstrate main principles and basic functionality.
</p>
<a href = "https://github.com/r-hta/R-Shiny-for-HTA">Github repo<a/>
</body>
<h2 id = 'Titles'>Economic Burden of Female Genital Mutilation in 27 High-Prevalence Countries: a series of national cohort models in R and a web app in Shiny</h2>
<body>
<b>Presenter: <a href = "http://www.davidtordrup.dk/">David Tordup<a/></b>
<p>
Overview of the models and presentation of a Shiny app by Mr David Tordrup, Triangulate Health Ltd. The model and app were developed by the World Health Organization in in collaboration with Triangulate Health Ltd.
</p>
Read the study in <a href = "https://gh.bmj.com/content/7/2/e004512">BMJ Global Health<a/>
</body>
<h2 id = 'Titles'>The Cost-Effectiveness of COVID Vaccines: a Shiny presentation</h2>
<body>
<b>Presenter: <a href = "https://www.himss.org/speaker-alejandro-lopez-osornio">Dr Alejandro Lopez Osornio<a/></b>
<p>
A an interactive presentation on the health impact and cost-effectiveness of COVID-19 vaccines for 26 Latin American counties, using Shiny.
</p>
The code for this model is not open-source
</body>
<h2 id = 'Titles'>Budget Impact Analysis: a Shiny based calculator</h2>
<body>
<b>Presenter: <a href = "https://www.iecs.org.ar/evaluacion-de-tecnologias-sanitarias-y-economia-de-la-salud/equipo-de-trabajo/">Dr Federico Cairoli<a/></b>
<p>
A Budget Impact Analysis presentation focusing Shiny and its ability to provide decision makers with an interactive model format.
</p>
The code for this model is not open-source
</body>
<h2 id = 'Titles'>Modelling Covid in R: an experience in using R over Excel for SIR modelling</h2>
<body>
<b>Presenter: <a href = "https://www.linkedin.com/in/ivan-zimmermann-57392852/">Dr Ivan Zimmerman<a/></b>
<p>
On presentation on moving from Excel to R for SIR modelling. The presentation discuss why modelling an SIR model in Excel takes time and a high probability of error due to cells replication. In comparison, using R is much simpler and less prone to error.
</p>
The code for this model is not open-source
</body>
<h2 id = 'Titles'>A Simplified Model of the Cost-Effectiveness of Screening: An Open-Source Teaching and Research Tool Coded in R</h2>
<body>
<b>Presenter: <a href = "https://www.tcd.ie/medicine/health_policy_management/staff/">Yi-Shu Lin<a/></b>
<p>
Models applied in cost-effectiveness analyses of screening are typically designed to address specific policy questions and consequently tend to be large and complex. They are not well suited to teaching the fundamentals of screening modelling or to demonstrating novel modelling methods.
</p>
<p>
The presentations thus describes a lightweight, fully shareable and transparent screening model for teaching and methods research. This is a simplified, discrete-event, microsimulation model of screening coded in R and supported with an Excel-based user interface for the specification of input parameters. The model's components relating to the natural history of disease, test performance and anticipated health gain and healthcare costs are also demonstrated.
</p>
The source code for this model will be shared once the author has given permission
</body>
<h2 id = 'Titles'>A Need for Change! A Coding Framework for Improving Transparency in Decision Modelling</h2>
<body>
<b>Presenter: <a href = "https://r-hta.org/authors/fernando-alarid-escudero/">Dr Fernando Escudero<a/></b>
<p>
The use of open-source programming languages, such as R, in health decision sciences is growing and has the potential to facilitate model transparency, reproducibility, and shareability. However, realizing this potential can be challenging. Models are complex and primarily built to answer a research question, with model sharing and transparency relegated to being secondary goals. Consequently, code is often neither well documented nor systematically organized in a comprehensible and shareable approach. Moreover, many decision modelers are not formally trained in computer programming and may lack good coding practices, further compounding the problem of model transparency. To address these challenges, the presentation provides an overview of a high-level framework for model-based decision and cost-effectiveness analyses (CEA) in R.
</p>
Read the open-access article in <a href = "https://link.springer.com/article/10.1007/s40273-019-00837-x">Springer<a/>
</body>
<h2 id = 'Titles'>Panel discussion: are the features of modern software tools ( R ) also useful for HTA modeling  in LMICs?</h2>
<body>
<b>
<p>
Panelists: <a href ="https://r-hta.org/authors/fernando-alarid-escudero/">Assistant Prof Fernando Alarid-Escudero<a/>, <a href = "https://www.ucl.ac.uk/statistics/people/gianlucabaio">Prof Gianluca Biao<a/>, <a href = "https://southafrica.inspiringfifty.org/lucy-cunnama">Dr Lucy Cunnama<a/>, and <a href = "https://www.bristol.ac.uk/people/person/Howard-Thom-7d5ace0c-a4eb-4fa0-8c0b-37dc141c0e9f/">Dr Howard Thom<a/>
</p>
<p>Moderator: <a href = "https://za.linkedin.com/in/buhle-n-04a5661a">Buhle Ndweni<a/></p>
</b>
<p>
The panel discussesion centers on the potential strengths and weaknesses of R for HTA in LMICs across four domains: clinical realism, quantifying decision uncertainty, transparency/reproducibility, and reusability/adaptability
</p>
</body>