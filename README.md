# Demystifying the Ignored: Exploring the Overlooked Performance Variance in Serverless Computing

* **Research papers**: In the file "**Collected research papers.xlsx**", there is detailed information about 59 research papers that we collected, including
  - CSRankings category
  - conference
  - publication year
  - paper title 
  - the labeled information regarding RQ1

* **Raw data**: We make raw data of cold-start/warm-start performance publicly available. Please refer to the file "**Raw data of performance results.xlsx**". We use the response latencies of each serverless function with 50 repetitions.

* **Invocation scripts**: Invocation scripts used in our study are in the directory "**Invocation scripts**", including the invocation code of AWS Lambda and Google Cloud Functions.
  - "invokeFunctionScript-run1.py" and "invokeFunctionScript-run2.py" for AWS Lambda
  - "invokeGoogleFunction.py" for Google Cloud Functions

* We have also curated and made publicly available a benchmark dataset about serverless functions for future performance testing and optimization of serverless computing.
  - In the file "**Executed serverless functions.xlsx**", there is detailed information about 65 serverless functions, including
    - input payload
    - executed serverless platform
    - programming language
    - timeout time
    - memory allocation size
    - original code link
    - functionality type
    - corresponding research papers
    
  - In the directory "**Deployment Packages for Serverless Functions**", there are deployment packages corresponding to Func1 to Func65. 
    - the code for each serverless function is packaged in a separate folder
    - the short input payload for some serverless functions is recorded in "**Executed serverless functions.xlsx**"
    - the long input payload for some serverless functions is stored in the directory "**input**", including func20, func29, func54, func56, func57, and func60.

* **Figures**:
  - RQ2: the normalized boxplot of warm starts
  - <img width="1053" alt="image" src="https://github.com/WWW24Work/Serverless_Variance/assets/121369770/a7570009-6b71-4ae7-9610-90baf8c2dd37">

    
