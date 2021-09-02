Setup  :
1. Install node js and github desktop.
2. Open cmd.
3. Type : npm install -g bower
4. From cmd, browse to the folder where you would be working.
5. Type : bower install bootstrap
6. Type : bower install jquery
7. Type : bower install tether
8. Close cmd. Install Prepos(or other similar app).
9. Open prepos. Add the project folder to it.
10. File explorer. Browse to root folder of the project. Create a folder named "scss". another folder inside named "vendor". Browse to bootstrap folder. scss. Copy bootstrap.scss and _custom.scss (not available? create one later) to vendor.
11. Open the bootstrap.scss file. Alter the path. Only import the requirements.
12. Add @import "custom"; at the beginning of all the imports.

