# Device Guard

Device Guard is a new Window 10 enterprise feature for locking down a system so that only trusted applications can execute. The enforcement of Device Guard is provided by the Hyper-V hypervisor code integrity policy. 

The SHB does not require Device Guard, however it is highly recommended to use Device Guard at least on administrator workstations to provide additional protection for privileged credentials. NSA Information Assurance has a security guide for [Implementing a Secure Administrator Workstation Using Device Guard](https://www.iad.gov/iad/library/ia-guidance/security-configuration/operating-systems/windows-10-device-guard.cfm).

Scripts for helping with the deployment of Device Guard can be found in the [scripts folder](./Scripts).

## Guidance

NSA Information Assurance has a security guide for [Implementing a Secure Administrator Workstation Using Device Guard](https://www.iad.gov/iad/library/ia-guidance/security-configuration/operating-systems/windows-10-device-guard.cfm).

## Links

* [Microsoft Device Guard Deployment Guide](https://technet.microsoft.com/en-us/itpro/windows/keep-secure/device-guard-deployment-guide)
* [Device Guard and Credential Guard hardware readiness tool](https://www.microsoft.com/en-us/download/details.aspx?id=53337)
* [Securing Privileged Access](https://technet.microsoft.com/en-us/windows-server-docs/security/securing-privileged-access/securing-privileged-access)
* [Privileged Access Workstations](https://technet.microsoft.com/en-us/windows-server-docs/security/securing-privileged-access/privileged-access-workstations)