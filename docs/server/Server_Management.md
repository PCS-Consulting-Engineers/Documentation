# Managing the server

Under most circumstances, the server should continue to operate as normal, however you may want/need to do a few simple tasks as desscribed below.

## Connecting to the server

To be able to change any settings on the server, you need to be able to login as an admin user. To do this:

1. Go to either [192.168.1.106](https://192.168.1.106) (if either connected to the VPN or on site) or [pcsconsultingengineers.quickconnect.to](https://pcsconsultingengineers.quickconnect.to) otherwise.
2. Sign in with the admin credentials (username is PCS)

## Restarting or shutting down the server

1. Connect to the server as described above
2. Click the user icon in the top right
3. Click Restart or Shutdown

## User Management
### Adding Users

To add a user, connect to the server as above, then:

1. Click Control Pannel
2. Click Users
3. Click Create
4. Assign a username and password (other fields aren't necessary)
5. Users should normally only be in the user group "Users"
6. Assign permissions for the Projects share (the main files on the server). Typically should be read/write permissions

### Changing User Passwords
#### Forgotten Password
If the user has forgotten the password, you can connect to the server as above and then follow the below steps:

1. Click Control Pannel
2. Click Users
3. Right click on the user
4. Click edit
5. Assign a new password

#### Changing Passwords

If the user has not forgotten their password, but want to change it, get them to connect to the server as above, **using their credentials, *not* the PCS admin**.

1. Click the user icon in the top right
2. Click Personal
3. Enter existing password in the *password* field, and new password in the 2 fields below

### Deleting A User

1. Connect to the server as above
2. Click Control Pannel
3. Click Users
4. Right click on the user
5. Click delete
