<HEAD
# Terraform AWS S3 Bucket Deployment

![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge\&logo=terraform\&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge\&logo=amazon-aws\&logoColor=white)

This project demonstrates how to use Terraform to create and manage an AWS S3 bucket, including uploading files and configuring access controls.

## 📝 Project Overview

In this project, I:

* Created infrastructure as code using Terraform
* Provisioned a private S3 bucket in AWS
* Configured public access blocks for security
* Uploaded a sample file to the bucket using Terraform
* Learned Terraform workflow (`init`, `plan`, `apply`, `destroy`)

## 🛠️ Prerequisites

Before you begin, ensure you have:

* [Terraform](https://developer.hashicorp.com/terraform/downloads) installed
* [AWS CLI](https://aws.amazon.com/cli/) configured
* AWS IAM credentials with S3 permissions
* A unique S3 bucket name (globally unique across AWS)

## 🚀 Quick Start

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/terraform-aws-s3.git
   cd terraform-aws-s3
   ```
2. Initialize Terraform:

   ```bash
   terraform init
   ```
3. Review execution plan:

   ```bash
   terraform plan
   ```
4. Apply configuration:

   ```bash
   terraform apply
   ```
5. Destroy resources when done:

   ```bash
   terraform destroy
   ```

## 📂 Project Structure

```
terraform-aws-s3/
├── main.tf             # Main Terraform configuration
├── image.png           # Sample file to upload (optional)
├── .terraform.lock.hcl # Dependency lock file
└── README.md           # This documentation
```

## 🔧 Customization

Edit `main.tf` to:

* Change AWS region
* Modify bucket name (must be globally unique)
* Adjust public access settings
* Change the uploaded file

## 🛡️ Security

The configuration includes:

* Blocked public access by default
* Secure credential management (via AWS CLI)
* Clean resource destruction capability

## 📚 Learning Resources

* [Terraform AWS Provider Documentation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
* [AWS S3 Terraform Module](https://registry.terraform.io/modules/terraform-aws-modules/s3-bucket/aws/latest)
* [Terraform Best Practices](https://developer.hashicorp.com/terraform/tutorials)

## 🤝 Contributing

Contributions are welcome! Please open an issue or pull request for any improvements.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Made with ❤️ as part of my DevOps learning journey.


3ba1e567df99bbfff0e1a415740d65c56f726973
