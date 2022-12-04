# Home Assistant Docs

![Home Assistant](https://esphome.io/_images/home-assistant.png)

Home Assistant is a group Project from Teamwork. click to access the codebase: [@Home_assistant_Matomi](https://git.teamwork.net/AWS/teamwork/tutorials/home-assistant/-/tree/home_assistant_matomi).

---

## Contents

- [Usage](#usage)
- [Development](#development)
- [Author](#author)

## Usage

### 1. Install dependencies

Dependencies installation docs next....

Everything is already prepared for you, Just launch the script with the command below and your aws instance will be created and home-assistant will be installed automatically:

```bash
sudo terraform init
sudo terraform plan --var-file=customeVariable.tfvars  // the '--var-file is optional else you input the variable(secret vals)  value always'
sudo terraform apply --var-file=customeVariable.tfvars  // the '--var-file is optional else you input the variables(secret vals) value always'


**NOTE: When your script is runing, remember to type 'yes' to enable ansible connect with your remote machine with ssh key.
```

### 2. Install bundler

You must have these installed. If you already have them installed, please skip this step.

```bash
# insall terraform
$ sudo apt install terraform -y
# install ansible
$ sudo apt install ansible -y
```

### 3. ### 4. Serving it up

if everything went fine. Wait for 2mins at most for the site to boot up
Open <http://ip:8123> in your broser, and voilà.



## Author

**Matomi Lucky EZEKIEL**

- <https://git.teamwork.net/mlezekiel>

<3
