## Netbox
This role provides a means to install Netbox. It makes a few assumptions on the setup:

- Accessing the application only happens via a Reverse Proxy (such as Apache) which is already set up
- The PostgreSQL database is already set up (local or otherwise)
- The system can access Github to download the desired version
- All media, reports and scripts are stored on the local machine

Check [defaults/main.yml](the default file) for all configurable options
