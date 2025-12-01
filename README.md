# linux-handbook
linux basics, intermediate and advance

# level1 Linux Basic Fundamentl skills
## Set up users, groups for dev team
Create a user adduser Techie
Create a new group groupadd techie_horizon
Add user to the group usermod -aG techie_horizon  techie
Check the user added to group: groups techie
remove user from a group: gpasswd -d user groupname
delete group: groupdel groupname
