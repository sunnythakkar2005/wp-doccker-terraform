# GCP + Terraform + Docker + WP

This terraform stack will install WP and mysql db  docker image in GCP.


install Terraform from https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/gcp-get-started

Configure your GCP creds as per 

## Usage

Clone this repo
https://cloud.google.com/sdk/docs/initializing
```bash
cd wp-docker-terraform
```

```bash
#To see what will be deployed
terraform plan

#to deploy
terraform apply

#to destroy
terraform destroy
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)