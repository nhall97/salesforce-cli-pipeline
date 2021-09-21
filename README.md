#  sf-cli-cloudbuild-pipeline
Using the new Salesforce CLI (Beta) to expirement with CI/CD pipelines
https://github.com/salesforcecli/cli

## Yarn
We're using a yarn workspace to install the new Salesforce CLI.

```yarn add @salesforce/cli```

## Run command
Yarn is installed locally, so we run our commands with yarn.

```yarn sf```


## Using monorepo structure
Deploy the source files in a directory:
```$sf deploy metadata --source-dir path/to/source```