# app-test-github-action
To create a simple CI/CD workflow and prototype them to understand


# purpose
- To test a simple CI/CD workflow and test it for my understanding
- A practice repository

## Version-1: src folder approach
- To test the pytest and perform simple automated CI, we have utilized the folder.
    - If the pytest has to executed:
        - Need to create folder called `tests`
        - the test files has to start with `test_sample.py` or `sample_test.py` --> this enables the pytest to identify and execute.
        

## Version-2: Outside src folder
- creating main.py
- creating app.py


## Few unavoidable steps
1. adding `.github/workflow/cicd.yml`
2. add `.gitignore`
3. add `uv init` package manager for easy migration and export
4. add `DockerFile`




