# avr_system_interfaces
This contains 2 service types:

## SetNetworkConfig
Sends a network configuration name `name` and receives a bool `success`.

## SystemTrigger
Triggers an action in the system node while providing a bool `include_subsystem` indicating whether to chain the message to the subsystem system node.
Returns a bool `success` and a string `message`.
