# HomeAutomation
Various Home Automation Topics (IFTTT/NodeRed/MyStrom)

## IFTTT
### Polling 
    Typically Actors are polling IFTTT and are reacting on pending information in IFTTT. 
    This is the simple way to pass through all Firewalls and not being blocked 
### Push 
    Using a Webhook as the outgoing action allows to push the requests to a public reachable static IP address.
    Because most private mobile SIM cards do not get a public IP address, it is not possible to use this method unless
    a virtual private network is leveraged between a public static IP address and the router/gateway/computer using the mobile connection.
    A port forwarding on the public static IP adress reaching out over the VPN tunnel to the mobile device allows the communication from IFTTT  to the mobile device.
## NodeRed
    NodeRed can be used to implement a logic to control several devices.
    A sample API https://github.com/lumibaer/HomeAutomation/blob/master/flows.json with a Dashboard and 2 actors have been created
