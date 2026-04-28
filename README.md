# Install Terraform CLI
<details><summary>Bash Scripts</summary>
```bash
# 1. install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 2. Add HashiCorp Tap
brew tap hashicorp/tap\n

# 3. Install Terraform
brew install hashicorp/tap/terraform

# 4. Verify
terraform --version
```
</details>