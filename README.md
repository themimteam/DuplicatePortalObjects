# DuplicatePortalObjects
Duplicate Portal Objects

# Author
Carol Wapshere

Duplicate an objects in the Potal. The new object will be named "Copy of " + the Display Name of the copied object.

Duplicate-Object.ps1

This script was not able to duplicate SynchronizationRule objects so I've written another one which just copies the flow rules. You'll need to create the new SR object and set everything except the flow rules, then run this script spcifying the source and target SRs.

Duplicate-SRFlows.ps1