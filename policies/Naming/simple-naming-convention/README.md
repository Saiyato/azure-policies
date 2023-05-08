# Apply simple naming convention

This policy enforces a simple naming convention for Resource Groups. You can define a custom format, but the policy implies a resource type (e.g., -vm, -aks, etc.) suffix to your format, if your convention is `<location>-<workload>-<instance>`, the policy will expect a user to provide that **plus** the resource type prefixed by a hyphen/dash. 

For example if your input is `westeu-datalake-01`, you will need to specify the resource type: `westeu-datalake-01-rg` (for Resource Group).

## Try on Portal

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#blade/Microsoft_Azure_Policy/CreatePolicyDefinitionBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSaiyato%2Fazure-policies%2Fmain%2Fpolicies%2Fnaming%2Fsimple-naming-convention%2Fpolicy.json)
