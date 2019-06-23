This directory will hold the agent/model itself. It needs to:

* accept the game state/environment, considering at least the current step and probably previous steps as well
* use the rewards policy to decide on the best action
* pass that action decison back to the environment
* record any data helpful for training
* train by updating the rewards policy
