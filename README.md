# Decontainer For Odoo
## Setup
1. Download folder
2. Copy Odoo into the folder by the name odoo
3. Open workspace file with vscode
4. Reopen in container
5. wait for setup to finish
6. Attach shell to postgres container and run 
  `su postgres -c "createuser -s vscode` 
7. Return to vscode and debug using f5