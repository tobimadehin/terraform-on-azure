# terraform-on-azure
A simple terraform infrastructure that provisions a static web page on an ubuntu Linux server on azure cloud

## Deployment steps
### Pre-requisites
1. An azure account
2. A terraform intallation   
```https://learn.hashicorp.com/tutorials/terraform/install-cli```

### Steps
1. Clone the project to your machine

2. Login to the azure cl ```az login``` 

3. Initialize terraform ```terraform init``` 

4. Check out infrastructure ```terraform plan```

5. Provision the vm ```terraform apply```

6. Check out your azure portal for the public ip address and paste in the browser   
```http://<-public ip->```

7. Clean up resources ```terraform destroy```

8. If you run into any issues while executing any of these steps, simply create a case

Cheers!
