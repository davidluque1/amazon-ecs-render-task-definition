# In addition to the original action, this forked version changes an environment variable in a task-definition.json file. Usage: environment-variable-name, environment-variable-value. Names are obvious: environment-variable-name for the variable name that you want to change, environment-variable-value for its value

# Code is untested. Works for me. PRs welcome

## Amazon ECS "Render Task Definition" Action for GitHub Actions

Inserts a container image URI into an Amazon ECS task definition JSON file and (optionally) modifies any existing container environment variables, adding them to the array if these variables do not exist.

**Table of Contents**

## License Summary

This code is made available under the MIT license.

