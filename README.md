# Creating the script file `kubectl-kubeplugin.sh`
touch kubectl-kubeplugin.sh

# Editing the script using the `nano` text editor
nano kubectl-kubeplugin.sh

# Granting executable permission to the script
chmod +x kubectl-kubeplugin.sh

# Moving the script to the /usr/local/bin/ directory for access via the `kubectl` command
sudo mv kubectl-kubeplugin.sh /usr/local/bin/kubectl-kubeplugin 

# Calling the `kubectl` command to execute the plugin
kubectl kubeplugin

# Calling the `kubectl` command to execute the plugin with parameters
kubectl kubeplugin kube-system pods get

