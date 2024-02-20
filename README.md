# System-anomaly-detection-using-ML-with-ui
> [!Note]
>_This task is given to one of my friend by a company's HR during the placement round._
## Problem Statement
> Develop an application capable of remotely monitoring processes, CPU, and memory usage on a target machine. The collected data should be stored in a MongoDB database. In the event of detecting abnormal patterns compared to standard behavior, the application should provide the option to take corrective actions, such as stopping the monitored application. The gathered information should be displayed in a web-based dashboard for easy access and analysis.

## Assumptions
We assumed the following Processes are running on a System maintaining Normal Behaviour
 

| Process          | Max CPU Usage (%) | Max RAM Usage (MB) |
|------------------|-------------------|--------------------|
| Search           | 1                 | 1                  |
| Service Host     | 0.5               | 30                 |
| Runtime Service  | 15                | 200                |
| Application      | 70                | 4096               |
| Sync Service     | 0.7               | 20                 |
| Network Host     | 5                 | 50                 |
| Client Server    | 30                | 150                |
| Container        | 2                 | 100                |
| Train            | 99                | 10240              |

> [!IMPORTANT]
>_This is not in actual case but assumed for generating the Synthetic Data for Training the ML model._
## Screenshots
----
Fig1: System Process Tests

![System Process Tests ](https://github.com/NITRR-Vivek/System-anomaly-detection-with-ui/blob/main/Screenshot-1.png)
----
Fig2: System generated data in MongoDB Database

![System generated data](https://github.com/NITRR-Vivek/System-anomaly-detection-with-ui/blob/main/Screenshot-2.png)
----
Fig3: Analysis using Scatter plot

![Analysis Scatter plot](https://github.com/NITRR-Vivek/System-anomaly-detection-with-ui/blob/main/Screenshot-3.png)
----
Fig4: Analysis using Pie plot

![Analysis Pie plot](https://github.com/NITRR-Vivek/System-anomaly-detection-with-ui/blob/main/Screenshot-4.png)
----
Fig5: Analysis using Box plot

![Analysis Box plot](https://github.com/NITRR-Vivek/System-anomaly-detection-with-ui/blob/main/Screenshot-5.png)
----
