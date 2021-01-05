# Kubernetes test project
This purpose of this repo is to test out a workflow in which a project versioned by semver,
wants to keep the two last major versions alive.
This is done by using the master number as a release identifier in the deployment and route to the correct workload based on the version.
It is also capable of deleting the no longer supported release by subtracting 2 of the current major part of the version.
See the flow below to get a better understanding.
![Alt text](/flow.PNG?raw=true "Flow scheme")
 
