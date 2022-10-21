# ubuntu22-k8s-cluster
ansible playbooks for deploying kubernetes cluster on ubuntu22 

**Edits required:**

inventory.yaml 
- add hosts to right category

-deploy.play assumes the default ipv4 address is correct for the cluster controllers listen address if running multiple you may need to manually specify the address instead of using the variables in the intialize controller task

**Instructions**
run it and wait





tested on ansible 2.1 using ubuntu22 server cloud images
