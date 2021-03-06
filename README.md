# BasicSIRModel
This project contains a basic SIR model, with build in plotting. A companion blog post for this project can be found <a href="https://mattravenhall.github.io/2018/01/02/SIR-Model.html">here</a>.

## Running the model

Simplified from the original. Set verbose to true for more detail.

```
$ python model.py
Generating model
Now running
Now plotting to output.png
```

## Model Parameters


Changable parameters include:

* 'eons' (number of time points to model, default 1000)
* 'Susceptible' (number of susceptible individuals at time 0, default 950)
* 'Infected' (number of infected individuals at time 0, default 50)
* 'Resistant' (number of resistant individuals at time 0, default 0)
* 'rateSI' (base rate 'beta' from S to I, default 0.05)
* 'rateIR' (base rate 'gamma' from I to R, default 0.01)

More complex alterations of the model will require specific engineering of the code. Feel free to dive in.

## Example Output.png
<img width="600" alt="portfolio_view" src="https://raw.githubusercontent.com/mattravenhall/BasicSIRModel/master/example.png">
