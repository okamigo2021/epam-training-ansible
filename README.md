# epam-training-ansible 

# Directory structure

/root/epam-training-ansible/  
├── files  
├── roles  
│   ├── apache  
│   │   └── tasks  
│   ├── mysql  
│   │   └── tasks  
│   ├── php  
│   │   └── tasks  
│   └── wordpress  
│       └── tasks  
└── vars  

# Install Playbook  
Run ansible-playbook playbook.yml -i hosts  

# Generate ssh key:  
Use private key for ansible SSH authentication  

ssh-copy-id -i ~/ssh/id_rsa.pub user@hostname
