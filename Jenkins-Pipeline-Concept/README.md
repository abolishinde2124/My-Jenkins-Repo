## Key Components of a Jenkins Pipeline:

Pipeline is Declarative Pipeline-specific syntax that defines a "block" containing all content and instructions for executing the entire Pipeline.<br>
Agent Defines where the pipeline or specific stages will run (e.g., any, docker, label).<br>

Stages:- Logical divisions in the pipeline (e.g., Build, Test, Deploy).<br>
Steps:- Individual tasks executed in each stage, like running a shell command or testing a script.<br>

## There are two types of pipelines in Jenkins:
1) Declarative Pipeline<br>
2) Scripted Pipeline<br>

## 1) Declarative Pipeline:<br>

Uses a simpler and more structured syntax.<br>
Enforces a specific structure, making it easier to write and maintain.<br>
Syntax example:<br>

## 2) Scripted Pipeline:<br>

More flexible but with complex Groovy-based syntax.<br>
Typically used by advanced users needing detailed control over the pipeline.<br>
Syntax example:<br>


