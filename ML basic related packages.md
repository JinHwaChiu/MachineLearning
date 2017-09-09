{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### https://www.kaggle.com/arthurtok/introduction-to-ensembling-stacking-in-python/notebook\n",
    "Following packages are tools for this basic ML contest\n",
    "--\n",
    "\n",
    "### Load in our libraries\n",
    "\n",
    "###### 科學計算撈數據用的包\n",
    "* import pandas as pd\n",
    "* import numpy as np\n",
    "\n",
    "###### 正則表示的模塊\n",
    "* import re\n",
    "###### ML的包\n",
    "* import sklearn\n",
    "\n",
    "###### xgboost是陳天奇大牛新開發的Boosting庫。它是一個大規模、分布式的通用Gradient Boosting（GBDT）庫，它在Gradient Boosting框架下實現了GBDT和一些廣義的線性機器學習算法原文網址：https://read01.com/yPxxaM.html\n",
    "* import xgboost as xgb\n",
    "\n",
    "###### Seaborn视为matplotlib的补充\n",
    "* import seaborn as sns\n",
    "\n",
    "###### 畫圖用的包\n",
    "* import matplotlib.pyplot as plt\n",
    "* %matplotlib inline\n",
    "* import plotly.offline as py\n",
    "* py.init_notebook_mode(connected=True)\n",
    "* import plotly.graph_objs as go\n",
    "* import plotly.tools as tls\n",
    "\n",
    "\n",
    "* import warnings\n",
    "* warnings.filterwarnings('ignore')\n",
    "\n",
    "###### Going to use these 5 base models for the stacking\n",
    "* from sklearn.ensemble import RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier, ExtraTreesClassifier\n",
    "* from sklearn.svm import SVC\n",
    "* from sklearn.cross_validation import KFold;\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 2",
   "language": "python",
   "name": "python2"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 2
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython2",
   "version": "2.7.13"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
