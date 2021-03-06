## thinking-simple example

Cost estimation problem for evaluating the minimum and maximum hourly cost (in dollars/hour) that would be paid with the planned deployment of the [Sock Shop application](https://microservices-demo.github.io).
* `sock-shop.yml` specifies the application deployment in TOSCA,
* `compositors.py` specifies the functions to be used to compose the costs associated with the components of the Thinking application, and
* `costs.py` specifies the costs associated with the components of the Thinking application.

To run the cost estimation problem, just go to the main folder of the project, and type

```
python evalto.py data\examples\sock-shop\thinking.yml data\examples\sock-shop\compositors.py data\examples\sock-shop\costs.py
```

Note: This cost estimation problem corresponds to the case study presented in the paper where EvalTo was first presented (see _About_ in main README).
