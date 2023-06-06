# Ansible--GitLabCI


такая конструкция будет вызывать основной CI
```.gitlabci.yml
---
include:
  - project: "ansible/main_config"
    file: ".gitlab-ci.yml"
```    
