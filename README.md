# Email sender

This is a python script for sending emails.

## Appendix

**Used virtualenv**


To check if virtual env is installed:  
```bash
pipenv --version  
```

To create a virtualenv:  
```bash
pipenv shell
```

installed dotenv:  
```bash
pipenv install python-dotenv
```


**Packages**  

virtualenv   
dotenv 


## Acknowledgements

 - [README](https://readme.so/)  
 - [Writing a good README - Medium article](https://medium.com/analytics-vidhya/writing-github-readme-e593f278a796)


## Run Locally

Clone the project

```bash
  git clone https://github.com/adrianbaltag/email_sender.git
```

Go to the project directory

```bash
  cd email_sender_python
```

Install dependencies

```bash
  pip install -r requirements.txt

```  
You can also use pipenv or conda to install dependencies, depending on your environment.  

 - This command will install all packages from pipfile.lock
```bash
pipenv install
```

 - This command will create a new conda environment with all the dependencies specified in the environment.yml file.
```bash
conda env create -f environment.yml
```

Please make sure to use the appropriate command according to your environment and the tool you have used for managing the dependencies.