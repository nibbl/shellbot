# shellbot

Simple Telegram bot on bash that execute commands in shell remotely.
You can send commands to your server without SSH access, or open SSH port,
or passthrough ssh-tunnel, or something like this. Support many master ID's, so you can provide access
for others.

Requirements: bash, curl, jq

How to use:
1. Clone git repository
2. Rename config example to config.sh and insert bot token and your Telegram ID into config
3. Then:
   
   a) Run "shellbotd.sh" in tmux/screen

	or

   b) Run "./install.sh" for create, enable and start systemd unit (better way)

For checking connection send 'ping' in the chat.
