### Boston_House_Pricing

### Software and Tools requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VScodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new Environment

```
conda create -p venv python==3.7 -y
```
To run the model run the following code inside your virtual environment.
```
python app.py
```

This ML model is fully deployed on the web that uses Linear regression model and several other libraries mentioned in the "requirement.txt" file. Deployment can also be done using docker container and all the docker and yaml files are provided in the repository itself.