# SSH-Connection
Establishes SSH connection to configure networking devices remotely

The application starts by taking user inputs, such as files containing - IP address, user credentials and commands to configure; thereby verifying the inputs provided, finally establishing an SSH connection with the router/switch (pre configured with IP address and reachable to the instance running this application) to dump configurations. 

Router/Switch can be made available via GNS3 or running as a separate VM.
