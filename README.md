# ansible-manageiq-dev-setup
InstallsManageIQ VM and configures it for Red Hat's OPNFV Summit 2016 Demo

##Prerequisites


##Example Execution
##This deploys VM and installs manageIQ on that VM
ansible-playbook -i hosts site.yml 



##Connecting to ManageIQ

Simple steps to connect to the ManageIQ your local machine (change ports if needed):

1. ssh `<whoever>`@`<vm-host-ip>` -L localhost:3000:localhost:3000
2. ssh vagrant@`<vm-ip>` -L localhost:3000:localhost:443     (password is vagrant)
3. Hit https://localhost:3000 in your browser
4. Log in with admin//smartvm
