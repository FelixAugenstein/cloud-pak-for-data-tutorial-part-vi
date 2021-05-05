<h1 align="center" style="border-bottom: none;">:bar_chart: IBM Cloud Pak for Data Tutorial: Part VI</h1>
<h3 align="center">In this hands-on tutorial you will learn how Watson OpenScale can be used to monitor your deployed Machine Learning models</h3>

## Prerequisites

1. Sign up for an [IBM Cloud account](https://cloud.ibm.com/registration).
2. Fill in the required information and press the „Create Account“ button.
3. After you submit your registration, you will receive an e-mail from the IBM Cloud team with details about your account. In this e-mail, you will need to click the link provided to confirm your registration.
4. Now you should be able to login to your new IBM Cloud account ;-)

## Cloud Pak for Data Tutorials Part I to VI

This tutorial consists of 6 parts, you can start with part I or any other part, however, the necessary environment is set up in part I.<br>
[Part I - data visualization, preparation, and transformation](https://github.com/FelixAugenstein/cloud-pak-for-data-tutorial)<br>
[Part II - build and evaluate machine learning models by using the AutoAI](https://github.com/FelixAugenstein/cloud-pak-for-data-tutorial-part-ii)<br>
[Part III - graphically build and evaluate machine learning models by using the SPSS Modeler flow](https://github.com/FelixAugenstein/cloud-pak-for-data-tutorial-part-iii)<br>
[Part IV - set up and run Jupyter Notebooks to develop a machine learning model](https://github.com/FelixAugenstein/cloud-pak-for-data-tutorial-part-iv)<br>
[Part V - deploy a local app to test your model](https://github.com/FelixAugenstein/cloud-pak-for-data-tutorial-part-v)
[Part VI - monitor your model with OpenScale](https://github.com/FelixAugenstein/cloud-pak-for-data-tutorial-part-vi)

The first 4 parts of this tutorial are based on the [Learning path: Getting started with Watson Studio](https://developer.ibm.com/series/learning-path-watson-studio/).

<h4>1) CRISP-DM</h4>
The <b>CR</b>oss <b>I</b>ndustry <b>S</b>tandard <b>P</b>rocess for <b>D</b>ata <b>M</b>ining is a model to display the cycle of a data science project. It consists of six phases:<br />
1. Business Understanding - What does the business need?<br />
2. Data Understanding - What data do we have and how is it made up of?<br />
3. Data Preparation - How can we structure the data for the modeling?<br />
4. Modeling - Which modeling techniques could apply?<br />
5. Evaluation - Which model is the most accurate?<br />
6. Deployment - How to implement the model?<br />

![CRISP DM](readme_images/crisp_dm.png)

In this case we have a business understanding provided (predict churns) and we will focus on getting to understand the data better and prepare it for modeling.

## Set up Watson OpenScale

<h4>1) Create the OpenScale service</h4>
