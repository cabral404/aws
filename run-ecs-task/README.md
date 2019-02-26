# run-ecs-task
Python script to run an ECS task using Fargate.

## Configuration
The script reads `config.ini` file with all the configuration needed
to execute the task. The configuration file path can be changed with the argument
`--config`.

## Running a task

To run a command there is a required argument `command`, which refers to a 
section in the `ini` file.

For example:
```run-ecs-task --command check --config ./config.ini```