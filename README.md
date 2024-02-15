# Make a directory for the app on your computer:
``` sudo mkdir  /usr/local/hermes/ ```
# Unzip the download, and copy its location to the folder you created:
``` sudo cp -r /path/to/dist/hermes /usr/local/hermes ```
# Open bashrc file:
``` nano ~/.bashrc  ```
# Add this line:
```export PATH="/usr/local/hermes:$PATH"```
# Activate changes:
``` source ~/.bashrc ```
# Set execute permission:
```chmod +x /usr/local/hermes/hermes```
