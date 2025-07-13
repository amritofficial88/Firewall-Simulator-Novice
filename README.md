### Firewall-Simulator-Python

A Python script that simulates a basic firewall by generating random IP addresses and checking them against a predefined set of rules to determine if they should be allowed or blocked.

## How It Works

- The script contains a hard-coded dictionary of firewall rules where certain IP addresses are set to be blocked.
- It generates 12 random IP addresses within the range 192.168.1.0 to 192.168.1.20.
- Each generated IP is checked against the rules.
- If an IP matches a rule, the action is block; otherwise, the default action is allow.
- The result (IP, action, and a random number) is printed to the console.
