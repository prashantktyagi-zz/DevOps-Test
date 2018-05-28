# Use Prod vars with group inventory
Env name will be used to distinguish UAT and PROD instances

# Reliablity
By using instance count to minimum 2 in single AZ

# Deployment strategies

web and app deploy is using rolling update in current playbook. However Blue Green deployment can be used in case of zero downtime.
