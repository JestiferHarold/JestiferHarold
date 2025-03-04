<p align="center">
  <a href="" rel="noopener">
 <img src="https://i.imgur.com/AZ2iWek.png" alt="Project logo"></a>
</p>
<h3 align="center">movie-mixer</h3>

<div align="center">

[![Hackathon](https://img.shields.io/badge/hackathon-name-orange.svg)](http://hackathon.url.com)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)

</div>

---

<p align="center"> Smart Movie Recommender: Personalized Group-Based Movie  Suggestions
    <br> 
</p>

## 📝 Table of Contents

- [Problem Statement] ()
- [Idea / Solution](#idea)
- [Dependencies / Limitations](#limitations)
- [Future Scope](#future_scope)
- [Setting up a local environment](#getting_started)
- [Usage](#usage)
- [Technology Stack](#tech_stack)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## 🧐 Problem Statement <a name = "problem_statement"></a>

Choosing a movie for a group of people with diverse preferences can be
a time-consuming and frustrating task. Existing recommendation systems primarily focus on
individual preferences and do not effectively cater to group dynamics. Our project aims to
streamline this process by providing a smart movie recommendation system that considers
the choices of multiple users and suggests the most suitable movie while also presenting
relevant details, ratings, and top reviews.

- IDEAL: This section is used to describe the desired or “to be” state of the process or product. At large, this section
  should illustrate what the expected environment would look like once the solution is implemented.
- REALITY: This section is used to describe the current or “as is” state of the process or product.
- CONSEQUENCES: This section is used to describe the impacts on the business if the problem is not fixed or improved upon.
  This includes costs associated with loss of money, time, productivity, competitive advantage, and so forth.

Following this format will result in a workable document that can be used to understand the problem and elicit
requirements that will lead to a winning solution.

## 💡 Idea / Solution <a name = "idea"></a>

Our system collects movie preferences from a group of users, processes
their choices using a weighted recommendation algorithm, and suggests the most suitable
movie based on collective preferences. The application integrates IMDb API to fetch movie
details, including ratings and reviews, ensuring informed decision-making. By incorporating
user feedback mechanisms, the system improves over time, enhancing recommendation
accuracy

## ⛓️ Dependencies / Limitations <a name = "limitations"></a>

- What are the dependencies of your project?
- Describe each limitation in detailed but concise terms
- Explain why each limitation exists
- Provide the reasons why each limitation could not be overcome using the method(s) chosen to acquire.
- Assess the impact of each limitation in relation to the overall findings and conclusions of your project, and if
  appropriate, describe how these limitations could point to the need for further research.

## 🚀 Future Scope <a name = "future_scope"></a>

Write about what you could not develop during the course of the Hackathon; and about what your project can achieve
in the future.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development
and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

<!-- What things you need to install the software and how to install them. -->

##Node 

For Windows 

```winget install Schniz.fnm
fnm install 22
```

For MacOS and Linux

```
curl -o- https://fnm.vercel.app/install | bash
fnm install 22
```

Verify installation 

```
node -v
npm -v
```

  React

```
npm install -g react react-dom
```
Vite
```
npm install -g create-vite
```
  Verify installation 
```
create-vite --version
```
Tailwind
```
npm install -g tailwindcss 
```

Give examples


### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

## 🎈 Usage <a name="usage"></a>

Add notes about how to use the system.

## ⛏️ Built With <a name = "tech_stack"></a>

- [AppWrite](https://www.mongodb.com/) - Database
<!-- - [Express](https://expressjs.com/) - Server Framework -->
<!-- - [VueJs](https://vuejs.org/) - Web Framework -->
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@Dharshan2208](https://github.com/Dharshan2208) - Idea & Initial work
- [@arhamgarg](https://github.com/arhamgarg)
- [@JestiferHarold](https://github.com/JestiferHarold)

## 🎉 Acknowledgments <a name = "acknowledgments"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
