# Site Smith Project Setup

## 1. Configure Git Remote with SSH
```
# Change remote URL to SSH
git remote set-url origin git@github.com:manojbusam/site-smith-reactjs.git

# Verify SSH connection
ssh -T git@github.com
# Expected response: "Hi manojbusam! You've successfully authenticated..."
```

## 2. Run Ansible Playbook
```
npm --prefix react-app install && npm --prefix react-app start
```

