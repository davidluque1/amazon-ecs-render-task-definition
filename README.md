# In addition to the original action, this forked version changes an environment variable (a variable in the "environment" field in task-definition.json), or appends it if does not yet exist. Usage: environment-variable-name, environment-variable-value. Names are obvious: environment-variable-name for the variable name that you want to change, environment-variable-value for its value. 

# If the "logconfiguration-options-awslogs-group" variable is set, modifies logConfiguration options awslogs-group as stage + _containers. # Done to set different logging configurations depending on environment. Code untested

# Code is untested. Works for me. PRs welcome

## Amazon ECS "Render Task Definition" Action for GitHub Actions

Inserts a container image URI into an Amazon ECS task definition JSON file and (optionally) modifies any existing container environment variables, adding it to the array if the variable does not already exist.



**Table of Contents**

## License Summary

This code is made available under the MIT license.

