# nubevapoc
Nubeva Proof of Concept Files

## Usage
### Create Example 
`./nubeva-poc-install -n nubevapoc -r westus -p NubevaCustomPass!`

### Delete Example 
`./nubeva-poc-install -n nubevapoc -r westus -d`

### Arguments
```
-n|--name <name>
    REQUIRED
    The name of the POC resource group to create/delete
-r|--region <region>
    CONDITIONAL (Required for create only)
    The region to use for the POC resource group
-d|--delete
    Flag to schedule a delete of a POC environment, if not specified goes to
    create by default
-p|--password <password>
    Manually override the password for the bastion, default is 'GoNubeva1234'
-h|--help
    Display this help message
```
