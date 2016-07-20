Notes
=====

You can stop after a stage as [described here](http://docs.prediction.io/resources/engine-development/).

For example, if you want to check things you can run

```sh
pio train --stop-after-prepare
```

[An example; it should look like this](http://docs.prediction.io/customize/troubleshooting/):

```sh
[INFO] [CoreWorkflow$] TrainingData:
[INFO] [CoreWorkflow$] ratings: [1501] (List(Rating(3,0,4.0), Rating(3,1,4.0))...)
...
[INFO] [CoreWorkflow$] Training interrupted by io.prediction.workflow.StopAfterReadInterruption.
```
