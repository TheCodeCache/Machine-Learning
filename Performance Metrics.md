
# Performance Metrics:

The below points on confusion metrics is for `binary classification`.  

In order to remember it easily:  
we must always think in this order: `True Class` (i.e. `a boolean indicator`) and then `Predicted Class`  
and then suddenly things will become too easy to understand as well as remember for a long time.  

True Class:  
T - `Booelan True`  
F - `Boolean False`  

Predicted Class:  
P - Positive  
N - Negative  

We've below 4 possible combinations:  

True CLass - Predicted CLass  
  T     P  
  T     N  
  F     P  
  F     N  

TP: HIT, i.e. prediction was right - boolean true  
TN: HIT i.e. prediction was right - boolean true  
FP: MISS i.e. we predicted positive but that was wrong - boolean false  
FN: MISS i.e. we predicted negative but that was wrong - boolean false  

![image](https://user-images.githubusercontent.com/26399543/145644851-cf5847bf-3122-4372-912b-84f63282b622.png)


**Accuracy** = `(TP+TN) / (TP+TN+FN+FP)`  

**Precision** = `TP / (TP+FP)`  
**Recall** = `TP / (TP+FN)`  

**F-score** : it's the harmonic mean of `precision` and `recall`  
F-score = `2*(precision * recall) / (precision + recall)`  

