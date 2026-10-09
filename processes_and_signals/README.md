# Shell, processes and signals

Bash scripts to inspect processes, find PIDs and send or handle signals.

| File | Description |
| ---- | ----------- |
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Lists all running processes, user-oriented, with hierarchy |
| `2-show_your_bash_pid` | Displays the process lines containing `bash` |
| `3-show_your_bash_pid_made_easy` | Displays PID and name of processes whose name contains `bash` |
| `4-to_infinity_and_beyond` | Displays `To infinity and beyond` indefinitely, every 2 seconds |
| `5-dont_stop_me_now` | Stops `4-to_infinity_and_beyond` using `kill` |
| `6-stop_me_if_you_can` | Stops `4-to_infinity_and_beyond` without `kill` or `killall` |
| `7-highlander` | Loops indefinitely and displays `I am invincible!!!` on SIGTERM |
| `67-stop_me_if_you_can` | Stops `7-highlander` |
| `8-beheaded_process` | Sends SIGKILL to `7-highlander` |
| `10-process_and_pid_file` | Writes a PID file and handles SIGTERM, SIGINT and SIGQUIT |
| `manage_my_process` | Writes `I am alive!` to `/tmp/my_process` every 2 seconds |
| `11-manage_my_process` | Init script to start, stop and restart `manage_my_process` |
