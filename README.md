## InvenioRDM REST API Collection

### Usage
```bash
# Clone this repo
git clone https://github.com/slint/inveniordm-rest-api-collection.git
cd inveniordm-rest-api-collection

# Open this directory with Bruno...
# open -a Bruno.app .

# ...or run directly the collections using the bru CLI:
bru run --insecure --env Local --env-var "token=$TOKEN" "Create upload (minimal)/"
bru run --insecure --env Local "Retrieve records/"
```

ℹ️ Create an access token if you haven't already and add it to your environment as `access_token`.

[Bruno does not have workflows yet](https://github.com/usebruno/bruno/issues/87), so you will need to run 3 of the scripts (Create minimal/full, Add file, Publish) to create a record on sandbox. This is an example of what the full record looks like using all fields from the documentation https://sandbox.zenodo.org/records/48658

If you are developing locally, you should open the settings and disable SSL/TLS Certificate Verification
