Step1: Create a repo in Git (Jenkins-Terraform-Integration)

Step 2: Clone the repository in VS-Code

Step 3: Create main.tf (Add resource to create Security group, EC2-instance, Create a file called userdata.sh and pass script to install jenkins, Terraform & Docker)

Step 4: terraforn init, terraform validate, terraform fmt, terraform plan, terraform apply --auto-approve

Step 5: Login to AWS console, grab public_Ip:8080 to access jenkins server)

Step 6: Install the Docker Pipeline plugin in Jenkins:
        -Log in to Jenkins.
        -Go to Manage Jenkins > Manage Plugins.
        -In the Available tab, search for "Docker Pipeline".
        -Select the plugin and click the Install button.
        -Restart Jenkins after the plugin is installed.
