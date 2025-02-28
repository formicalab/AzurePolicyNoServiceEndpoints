Parameters:

* subnetId: subnet resource Id of the subnet controlled by the policy. Format: /subscriptions/<guid>/resourceGroups/<resource group name>/providers/Microsoft.Network/virtualNetworks/<vnet name>/subnets/<subnet name>
* allowedServiceEndpoints: array of allowed service points; the policy will not block them. Format (example): ["Microsoft.EventHub","Microsoft.KeyVault"]
