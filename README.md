## Setup

1. fork this repo
1. rename a few files
1. create secrets folder
1. in secrets folder, create scto_auth.txt
1. create service account
1. download json key, move it to secrets folder
1. for the project, give service account the role "bigquery user"
1. create bigquery datasets surveycto and surveycto_dev
1. for those two datasets, give service account the role "bigquery data editor"

1. update warehouse.yaml file, including auth_file based on name of json file
1. update surveycto.yaml file

- create secrets SCTO_AUTH and GOOGLE_TOKEN for GitHub Actions
- make sure GitHub secret SCTO_AUTH has no trailing line break
