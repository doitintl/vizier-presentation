# Sample Workbooks for Vizier
* This repo is accessible at [http://bit.ly/viziergithub](http://bit.ly/viziergithub)
* See the presentation at [https://bit.ly/vizierpresentation](https://bit.ly/vizierpresentation)

## Workbooks
###  Sample for GAPIC Vertex API
  * [/gapic-vizier-fraud.ipynb](/gapic-vizier-fraud.ipynb)
  * Uses the Vertex AI Vizier API.  Generally available.
  * This notebook is the only avialable sample for Machine Learning with Vertex AI Vizier, after the ML sample mentioned below.
  * This is the recommended API as the Vertex platform is Google's main direction.
  * Step through by the guidepoints tagged `#[0]`, `#[1]`, `#[2]`, etc.
### Sample for Discovery API
  * [/discovery-api-fraud.ipynb](/discovery-api-fraud.ipynb)
  * Uses the discovery-based API as part of Google AI Platform. Beta as of 11/2022. 
  * This is the recommended API as the Vertex platform is Google's main direction.
  * Step through by the guidepoints tagged `#[0]`, `#[1]`, `#[2]`, etc.
### For you to try: A Notebook based on Ryan Holbrook's Major League Baseball Notebook 
  * [/mlb/vertex-ai-with-mlb-player-digital-engagement.ipynb](/mlb//vertex-ai-with-mlb-player-digital-engagement.ipynb)
  * From  this  on Kaggle [https://bit.ly/viziermlb](https://bit.ly/viziermlb)
  * Improvements [here](/mlb//vertex-ai-with-mlb-player-digital-engagement.ipynb):
    * Shows my run output
    * Auto-sets project
    * Allows non-home-dir run
    * Delete import (which is  not actually used by the code ) that triggers error 
  * How to run that  Notebook
    * Read the NB itself for instructions
    * For the NB  to auto-download the data, you need a kaggle.json auth key from Kaggle.
    * You can mostly run it end-to-end, but see my minor fixes.
