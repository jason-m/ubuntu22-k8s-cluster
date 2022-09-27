# ubuntu22-k8s-cluster
ansible playbooks for deploying kubernetes cluster on ubuntu22 

**Edits required:**

inventory.yaml 
- edit host addresses

step5-init-controller.play 
- control-plane-endpoint= to match your controllers ip address
- node-name= your controllers hostname without domain

**Instructions**

Run playbooks in order, thats all
tested on ansible 2.1 using ubuntu22 server cloud images
