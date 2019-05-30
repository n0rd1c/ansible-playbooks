# Ansible playbooks

These playbooks are to help automate tasks I do on a regular basis with my virtual servers.

### Update_Pi-Hole:
  This playbook runs the command 'sudo pihole -up' and updates the Pi-Hole to the latest version.

### Update_Plex:
  This playbook grabs the latest version of Plex from their website and installs the .deb package.  The URL will need to be updated every time a new version of Plex comes out.

### Update_VMs Playbook:
  This playbook runs the 'apt update/apt upgrade -y/apt autoremove/apt autoclean' commands for all your Linux hosts.
  

