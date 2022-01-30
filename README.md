# Simple Stremlit sample program

This program is a simple sample program using Streamlit.
Use this program to deploy to IBM Cloud Code Engine.

# DEMO
This program will display the simple streamlit UI.

![Screenshot 2022-01-30 13 48 20](https://user-images.githubusercontent.com/37370521/151687066-482e32ee-3fa1-4840-945c-20c747ae9807.png)

# Features

This program contains the following command in the Streamlit.

streamlit.title()
streamlit.markdown()

Just sample!
You can add the your code to sample program.  (^_^)v

# Requirement

following python library is needed.

* streamlit

# Installation

This sample program use the streamlit library.
If you run this sample on your local phtyon environment, you have to install streamlit library.

```bash
pip install streamlit
```
When you run on the IBM Cloud Code Engine, pip command is described in the Dockerfile. You don't necessary to install streamlit library.

# Usage

On IBM Cloud Code Engine environment, you just access the target URL by using your browser.
The target URL will be assing when you deploy IBM Cloud.

If you want to run on the your local environment.
You can run the following simple command.
```bash
streamlit run sample1.py
```
# Note
I have checked this source , streamlit and IBM Cloud Code Engine envirionment on January 20222.

In that case, docker image file size are..

Using Python-slim : 270MB
      Python      : 570MB

F.Y.I.

# Author

* Yasushi Saito
* saboten102003@gmail.com

# License
This sample program is license free
enjoy!
