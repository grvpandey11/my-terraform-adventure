# How to Install Terraform

1. Download the Terraform binary from the official Terraform website: https://www.terraform.io/downloads.html
1. Choose the appropriate package for your operating system (Windows, Mac, Linux).
1. Extract the downloaded package to a directory of your choice.
1. Add the Terraform binary to your system's PATH variable so that you can run the 'terraform' command from anywhere in your terminal. You can do this by adding the directory containing the Terraform binary to your PATH environment variable.
    -  For Linux or Mac users, add the following line to your ~/.bashrc or ~/.zshrc file:
        ```bash
        export PATH="$PATH:/path/to/terraform/directory"
        ```

    - For Windows users, follow these steps:
        - Open Control Panel and go to System and Security > System > Advanced system settings.
        - Click on the 'Environment Variables' button at the bottom.
        - In the 'System variables' section, scroll down to the 'Path' variable and click 'Edit'.
        - Click 'New' and add the path to the directory containing the Terraform binary.
        - Click 'OK' to close the windows.
1. Verify the installation by running below command in your terminal. If everything is set up correctly, you should see the Terraform version number.
    ```
    terraform --version
    ```

That's it! You now have Terraform installed on your system and are ready to start using it to manage your infrastructure.