```
Create a Cloud Server in less than a minute with 1 command:

   ./bitmana cs

Usage:
  bitmana [command]

Available Commands:
  cs          Create scalable Cloud servers
  exec        Run remote commands on a server. For example ("cd /var/www; ls -lah") on NODE_ID 12345:
                > bitmana exec 12345 "cd /var/www; ls -lah"
  expose      Expose endpoints to your server. For example (Expose MySQL on NODE_ID 12345 port 3306):
                > bitmana expose 12345 3306
  help        Help about any command
  info        Display information on current account, default region, servers,...
  link        Link your system with bitmana.io
  scp         Secure copy files between local and remote. For example (NODE_ID 12345):
                > bitmana scp {LOCAL_PATH} 12345:{REMOTE_PATH}
                > bitmana scp 12345:{REMOTE_PATH} {LOCAL_PATH}
  selfupdate  Update to the latest version on Github
  set         Change default region (as|eu|us). For example (set default region to US):
                > bitmana set --region=us
  ssh         SSH to a remote server. For example (ssh to NODE_ID 12345):
                > bitmana ssh 12345
  start       Start a server.
                > bitmana start NODE_ID
  stop        Stop a server.
                > bitmana stop NODE_ID
  unlink      Unlink your system from bitmana.io
  version     Print version

Flags:
  -h, --help   help for bitmana

Use "bitmana [command] --help" for more information about a command.
```
