# IaC
Azure Infrastructure As Code

1. Create a service principle in you Azure subscription and create a srepo secret with the value as the out put of the following command.
  az ad sp create-for-rbac --name "myApp" --role contributor \
   --scopes /subscriptions/{subscription-id}/ --sdk-auth
