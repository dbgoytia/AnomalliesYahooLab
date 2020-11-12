# A benchmark datasets for time series anomaly detection, by Yahoo Labs.

As seen on: https://yahooresearch.tumblr.com/post/114590420346/a-benchmark-dataset-for-time-series-anomaly


## Overview

It is the middle of an anomaly. It's March Madness and there's a lot of traffic into 'Yahoo Fantasy Sports'. 

There are some obvious abnormalities that we can expect, like spike usage from the servers, and maybe some slowness in the service that we can anticipate for. But, what other anomalies can you detect that no one could anticipate? What are those anomalies that indicate a potential security threat to our user's data?



## The dataset

Yahoo made this dataset public through it's webscope sharing program: https://webscope.sandbox.yahoo.com/. It's interesting because it is a refernece of interesting and scientifically useful datasets, in this case, in the terms of server performance and anomaly detection.

You can access the dataset in:

https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70

It is a **labeled** dataset, in the sense that it is labeled with known anomalies.

It is part synthetic (or simulated), and part of the dataset is real traffic to Yahoo services. 

Synthetic traffic was labeled automatically, and real traffic was labeled by humans, thus prone to error, that's why this is a very interesting dataset.

## Concepts

* Outlier / anomaly: 

  Is a data point that is _significantly_ different from the rest of the given data.

* Time series forecasting:

  It is a way to predict future values based on previously observed values, using a mathematical model (statistics). Read more about this over here, and check out my **AI-Zero-2-Hero**  repository for lab examples of what this is. 
  
## See also

For other interesting datasets, see this: http://odds.cs.stonybrook.edu/

