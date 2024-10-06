# SecAzure

<p align="center">
  <img src="./logo.png" alt="logo" width="300" />
</p>

SecAzure is a "REPL for detection engineering" that allows you to generate datasets of cloud audit logs for common attack techniques with supports Microsoft Azure.


## How it works

First, SecAzure detonates an attack. It injects a unique user agent containing a UUID. Then, it polls CloudTrail to retrieve the audit logs caused by the detonation, and streams the resulting logs to an output file or to your terminal.

Supported detonators:
- [Stratus Red Team](https://github.com/DataDog/stratus-red-team)
- AzureCLI interactive shell

Supported logs backend:
- Azure Activity Log

Currently, the project is under construction and testing.
