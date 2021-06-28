
MLOps: Andrew Ng's course


## Week 1

Main challenges when going from POC to production:
	- handling data drift (key challenge), at a minimum we need to learn that data is drifting.
	- software engineering: extra code and handling around the core model. 

- deploying the model is just half the work done, you will have to make many changes once you see how it performs in the real world
- focus for research: model + hyperparameters, production: hyperparameters + data
	- doing error analysis can tell us how to systematically improve the data.
	- you need to judge "what type of data" to collect

- real world problems:
	- a lot of fraud detection systems were triggered by covid19 becuase of sudden change in data distribution of people's buying patterns.

- types of drift:
	- data drift: non iid samples coming in
	- concept drift: the mapping function itself changed (eg. due to inflation, house prices go up)

- software engineering considerations:
	- real time vs batch
	- cloud vs edge / browser
	- compute resources
	- latency, throughput
	- logging
	- security / privacy

- blue green deployment
	- have the old model (blue) ready, so that you can switch quickly if the present model (green) fails. (MLops tools help you do this easily)

- degrees of automation:
	- human
	- shadow mode (model doesn't make any decisions, just makes predictions)
	- ai assistance (helps humans make each decision quickly)
	- partial automation (yes, no, maybe predicitons)
	- full automation

- Monitoring:
	- monitor things on a dashboard: server metrics (load, cpu usage, etc.,), input data stats (average input length), output metrics (bad predicitons), etc., these metrics are based on "all the things that can possibly go wrong" (MLOps softwares come with tools to track these metrics). these metrics can be improved using experience in the real world.

- Pipeline monitoring:
	- A big issue is when you have multiple blocks in your pipeline. Chaning a small thing in the initial block can affect all subsequent systems. 

- Misc
	- Google's recent idea: track the performance of the baselines in real world too. helps give us better insights.

## Week 2: Modeling

- Two ways to develop production models: model-centric and data-centric. Data-centric is often better.  

- We generally train models quickly, do an error analysis and retrain this model. We need to do this loop as quickly as possible. 

- Just having low test set error is not enough. 
	- Some queries might be more important than others. 
	- It might fail to consider discrimination. 
	- Accuracy on rare classes might be ignored.
	- ML might ignore obvious things to humans.
	- Solution: error analysis on slices of data
	