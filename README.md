<!-- Improved compatibility of back to top link: See: https://github.com/pull/73 -->
<a name="readme-top"></a>
<p align="center">
  <h2 align="center">Build Vmware VM with Ansible | Asking ChatGPT to Create Ansible Code</h2>
  <p align="center">
    The files in this repo supports the <a href="https://youtu.be/jLwyAqOeuK4">Build Vmware VM with Ansible - Youtube Video Tutorial</a> that asks the ChatGPT AI bot to create the ansible playbook. 
    <br />
  </p>
</p>

<!-- GETTING STARTED -->
## <a name="start"></a>Getting Started

To get the project up and running on your local system, follow these steps:
Also follow along in the video to get a better understanding as to what's going on.

### Setting up:

* Install the required tools:
  ```bash
  pip install -r requirements.txt

* setup python virtual environment
  ```bash
  python3.8 -m venv ~/python3env
  source ~/python3env/bin/activate

  # upgrade pip
  pip install --upgrade pip

* install ansible core
  ```bash
    pip install ansible

* install vmware ansible collection
  ```bash
    ansible-galaxy collection install community.vmware

* install more pip stuff for vmware
  ```bash
    pip install pyVmomi requests



