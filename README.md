# How to use

This outputs an Ethereum address for a given AWS KMS key.

The easiest way to run this is via ts-node. The following environment variables are required:

```
# The access ID of the user to use for the API request
export ACCESS_KEY_ID=<redacted>

# The secret access key of the user to use for the API request
export SECRET_ACCESS_KEY=<redacted>

# The region where the key is, e.g. us-west-2
export REGION=<redacted>

# The ID of the key-- this is the big ugly string that's used to
# identify the key that isn't the alias, e.g. something like
# e2788a15-b8ef-4690-8fb1-f3613306ac99
export KEY_ID=<redacted>

ts-node index.ts
```
