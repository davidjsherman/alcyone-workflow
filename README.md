# Alcyone workflow

Example git history illustrating the interaction between
two entities:
1. a *provider* that defines validated specifications
1. a *user* that uses the specified environments

## Scenario

1. Based on interviews with the user, the provider develops an environment
1. The user provides test data and the specification is improved
1. The environment is provided to the user
1. The user deploys the environment and performs work that is committed
1. The user asks for some tools to be added
1. The provider validates the tools and updates the specification
1. The new specification is merged by the user
1. The user continues to work
1. The provider updates some tools
1. The user tries the new validated environment in a branch
1. The tests are successful so the new environment is merged by the user
