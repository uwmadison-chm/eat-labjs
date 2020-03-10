# Empathic Accuracy Task

An implementation of Tammi Kral's empathic accuracy task in lab.js.

Used by QET and PTE studies, linked from qualtrics because the stimuli videos 
we are using must be behind a login/password.

## Files

* [eat.json](eat.json): A version of the task configured like the original fMRI task, with 3 different response valences
* [simon.json](simon.json): The short 6-trial single-valence run for Simon Goldberg's PTE study, later also used for QET
* [demo.json](demo.json): A short demo, much like the original fMRI task, used to demo to the World Bank folks?

## Use

To configure, load the JSON file into lab.js. Export for whatever hosting 
strategy you plan to use.

To analyze the data, see [uwmadison-chm/eat-analysis](https://github.com/uwmadison-chm/eat-analysis).
