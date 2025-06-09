# Task 4: User and Group Management

### Purpose

Practice using user and group management commands to create a new user, group, set permissions, and explore user management.

### Commands Used & Outputs

```bash
# Create a new group
sudo groupadd testgroup

# Create a new user and add to the group
sudo useradd -m -s /bin/bash -g testgroup testuser

# Set password for new user (manual input required)
sudo passwd testuser

# Add user to sudo group (give admin rights)
sudo usermod -aG sudo testuser

# Delete the user
sudo userdel -r testuser

# Delete the group
sudo groupdel testgroup
