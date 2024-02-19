# **Terraform**

- Official Site: https://developer.hashicorp.com/terraform
- Tutorials Link: https://developer.hashicorp.com/terraform/tutorials

---

### **Install Terraform**

|Command                            |Description|
|:-                                 |:-|
|```choco install terraform```      |Chocolatey is a free and open-source package management system for Windows. Install the Terraform package from the command-line|
|```terraform -help```              |Verify the installation|
|```terraform init```               |Initialize the project, which downloads a plugin called a provider that lets Terraform interact with Docker|
|```terraform apply```              |Provision the NGINX server container with apply. When Terraform asks you to confirm type yes and press ENTER|
|```docker ps```                    |Verify the existence of the NGINX container by visiting localhost:8000 in your web browser or running docker ps to see the container|
|```terraform destroy```            |To stop the container, run terraform destroy|

http://localhost:8000/

---

### **Build infrastructure**

|Command                            |Description|
|:-                                 |:-|
|```terraform fmt```                |Format your configuration|
|```terraform validate```           |Validate your configuration|
|```terraform apply```              |Provision the NGINX server container with apply. When Terraform asks you to confirm type yes and press ENTER|
|```terraform show```               |Inspect the current state|
|```terraform state list```         |Manually Managing State|

---

### **Define input variables**

|Command                                                        |Description|
|:-                                                             |:-|
|```terraform apply -var "container_name=YetAnotherName"```     |Apply the configuration using the -var flag|

---

### **Query data with outputs**

|Command                                                        |Description|
|:-                                                             |:-|
|```terraform init```                                           |Initialize the project, which downloads a plugin called a provider that lets Terraform interact with Docker|
|```terraform apply```                                          |Provision the NGINX server container with apply. When Terraform asks you to confirm type yes and press ENTER|
|```terraform output```                                         |Query the outputs|
|```terraform destroy```                                        |Destroy infrastructure|
