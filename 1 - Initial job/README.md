# Step 1

Get a single job running on a VM


![alt text](job_diagram.png)

Common example: Install ssh on Ubuntu 24.4.01 (As it's not on by default)


Typical steps:

```bash
sudo apt upgrade
sudo apt update --fix-missing
sudo apt install ssh -y
```

