# 🔧 Web Server Deployment with Ansible (AWS EC2)

This project automates the setup of a web server (Nginx) on an AWS EC2 instance using Ansible.  
It installs necessary packages, deploys a custom `index.html`, and starts the service — all with a single command.

---

## 🛠 Tech Stack

- 🔹 Ansible
- 🔹 AWS EC2 (Ubuntu)
- 🔹 Nginx
- 🔹 WSL (Ubuntu Terminal on Windows)

---

## 📁 Project Structure

```
ansible_playbooks/
├── inventory
├── playbook_webserver.yaml
├── files/
│   └── index.html
└── README.md
```

---

## 🚀 Features

✅ Installs and starts Nginx  
✅ Deploys custom HTML to `/var/www/html`  
✅ Secures SSH with private key  
✅ Runs entirely via Ansible automation

---

## 🖼 Screenshots

### ✅ Ansible Playbook Run
![Ansible Run Screenshot](https://i.imgur.com/x1YLVOS.png)

### ✅ Web Page Deployed via Ansible
![Web Output Screenshot](https://i.imgur.com/TvT8zOr.png)


---

## 📚 What I Learned

- Writing production-ready Ansible playbooks
- Handling SSH key permissions in WSL
- Debugging EC2 access and automation errors
- Nginx service management on Ubuntu
- Real-world deployment with Infrastructure as Code

---

## 🔗 Connect With Me

👨‍💻 Atharv Chawan  
🔗 [LinkedIn](https://www.linkedin.com/in/atharv-chawan-ab01152a7/)  
📫 atharvchawna@gmail.com  
