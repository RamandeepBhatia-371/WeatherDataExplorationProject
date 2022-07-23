# WeatherDataExplorationProject
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "2fbff8a456f78421e8875e08e5f022184fd95424"
   },
   "source": [
    "In order to build forecasting model, I have opted for using CRISP-DM methodology."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "16c9744a1d5997d407c5ff182fa1607997b59d6e"
   },
   "source": [
    "**Business understanding**"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "89d2739687e6151953bb4e88a3a3bd6021ba9ae2"
   },
   "source": [
    "This first step is essentially about understanding the business, the need for the specific project and the resources that we have. "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "dea8b62ffb699648adb7c68394c5e54534444ed3"
   },
   "source": [
    "**Gathered background information**\n",
    "\n",
    " *Compiled the business background *\n",
    "\n",
    "this project is about historical weather around Szeged, Hungary , from 2006 to 2016\n",
    "\n",
    "**Defined business objectives**\n",
    "\n",
    "Made data more accessible and understandable for everyone.\n",
    "\n",
    "Provided fast analytics for the different Factors Affecting Weather .\n",
    "\n",
    "I used different prediction and classification algorithms\n",
    "\n",
    "Calculated and compared evaluation measures\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "076ca1160d13477a63950a132730cbd94410b918"
   },
   "source": [
    "**Assessed the situation**\n",
    "\n",
    "** Resource Inventory **\n",
    "\n",
    "Data : dataset contains in a practical format 10 years (2006-2016) of hourly data in just a single file.\n",
    "\n",
    "Computing resources : hp , i5 processor, 16 GB RAM\n",
    "\n",
    "Programming languages and libraries : python ( Numpy, pandas, matplotlib, seaborn, tensorflow, scikitlearn)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "7899795183bc32ed1c71e53623bfd70f90b32c06"
   },
   "source": [
    "**- Main Objectives of the project**\n",
    "\n",
    " the objective of this project is to analyze the weather data and extract the hypotheses to arrive at a prediction"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "875855d88e7236c31146ef9da08c7fc53d35a02e"
   },
   "source": [
    "**Collected initial data from kaggle**\n",
    "\n",
    "Dataset from Kaggle : https://www.kaggle.com/budincsevity/szeged-weather"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "1cf619c13d7c27fdb4254a3b06c2cf8e37fbc808"
   },
   "source": [
    "**- Data Exploration**\n",
    "\n",
    "Exploration is to understand how all these columns are related and the value structures so the correlation between these data"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "_uuid": "0c2c7ecf0041363b962777130b709205c14447e5"
   },
   "source": [
