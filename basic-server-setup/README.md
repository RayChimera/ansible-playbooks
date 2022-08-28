## Usage

This playbook sets up the server for personal use w/ more or less sane security in mind

You need to pass 2 variables:
* `variable_host` - the name of your host in `inventory.yaml`
* `admin_user` - the name of your admin user

So, the command will be something like: 
`ansible-playbook -i inventory.yaml basic-server-setup/basic-server-setup.yaml --extra-vars "variable_host=your_host admin_user=your_admin_user_name"`