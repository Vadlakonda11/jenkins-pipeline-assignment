# Jenkins Declarative and Scripted Pipeline Assignment

## 1. Project Overview

This repository demonstrates Jenkins Declarative and Scripted Pipelines through hands-on implementation.

The objective is to understand the differences between the two pipeline approaches, learn their basic syntax, and execute pipelines using Jenkins.

## 2. Objectives

* Understand Jenkins Pipeline fundamentals.
* Implement a Declarative Pipeline.
* Implement a Scripted Pipeline.
* Organize pipeline execution into stages.
* Configure environment variables.
* Understand build execution and error handling.
* Learn how pipeline code can be maintained in GitHub.
* Extend the pipelines with advanced Jenkins features.

## 3. Technologies Used

* Jenkins
* Git
* GitHub
* Groovy-based Jenkins Pipeline syntax
* Linux shell commands

## 4. Repository Structure

```text
jenkins-pipeline-assignment/
├── README.md
├── declarative/
│   └── Jenkinsfile
└── scripted/
    └── Jenkinsfile
```

## 5. Declarative Pipeline

**File:** `declarative/Jenkinsfile`

The Declarative Pipeline demonstrates the following concepts:

* `pipeline` — defines the pipeline.
* `agent` — specifies where the pipeline executes.
* `environment` — defines environment variables.
* `options` — configures build options.
* `stages` — organizes pipeline activities.
* `steps` — contains the operations within each stage.
* `post` — defines actions based on the build result.

The initial implementation contains these stages:

1. Initialize
2. Checkout
3. Build
4. Test

The initial Checkout, Build, and Test stages print demonstration messages. Actual source-code checkout, compilation, and automated testing have not yet been implemented.

## 6. Scripted Pipeline

**File:** `scripted/Jenkinsfile`

The Scripted Pipeline demonstrates:

* `node` — allocates an execution node and workspace.
* `stage` — organizes pipeline activities.
* `env` — sets environment variables.
* `echo` — prints messages to the console.
* `try/catch/finally` — demonstrates exception handling and final logging.

The initial implementation contains these stages:

1. Initialize
2. Checkout
3. Build
4. Test

The initial Checkout, Build, and Test stages print demonstration messages. Actual application checkout, compilation, and automated testing have not yet been implemented.

## 7. Jenkins Jobs

The following Jenkins jobs have been created and executed:

| Job Name                          | Pipeline Type | Initial Result |
| --------------------------------- | ------------- | -------------- |
| `Declarative-Pipeline-Assignment` | Declarative   | SUCCESS        |
| `Scripted-Pipeline-Assignment`    | Scripted      | SUCCESS        |

Both initial pipelines executed successfully in Jenkins.

## 8. Execution Process

1. Store the pipeline code in GitHub.
2. Create a Jenkin
