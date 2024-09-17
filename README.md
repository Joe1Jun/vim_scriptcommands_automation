# System Information Script

This Bash script gathers and displays various pieces of system information. When executed, it runs a series of commands to provide a snapshot of the system's status, including the current date, hostname, system architecture, kernel information, uptime, user details, and active processes.

## Commands Included

- `date`: Displays the current date and time.
- `hostname`: Shows the system's hostname.
- `arch`: Prints the system's architecture.
- `uname -a`: Outputs detailed information about the kernel.
- `uptime`: Shows the system’s uptime.
- `whoami`: Displays the current logged-in user.
- `who`: Lists all currently logged-in users.
- `w`: Provides information on who is logged in and what they are doing.
- `top`: Gives a real-time overview of system processes.
- `history`: Shows the command history for the current user.

## Usage

1. **Create the Script:**
   - Open your terminal.
   - Create a new file named `system_info.sh` by running:
     ```bash
     vi system_info.sh
     ```

2. **Edit the Script:**
   - Enter insert mode by pressing `i`.
   - Copy and paste the following script into the file:
     ```bash
     #!/bin/bash
     date
     hostname
     arch
     uname -a
     uptime
     whoami
     who
     w
     top
     history
     ```
   - Exit insert mode by pressing `Esc`.
   - Save and exit by typing `:wq` and pressing `Enter`.

3. **Make the Script Executable:**
   - Run the following command to make the script executable:
     ```bash
     chmod +x system_info.sh
     ```

4. **Execute the Script:**
   - Run the script by typing:
     ```bash
     ./system_info.sh
     ```

## Notes

- The `top` command provides a real-time display of system processes, which may require manual intervention to stop.
- Ensure you have the necessary permissions to execute the script and access the commands.

## License

This script is provided as-is without any warranty. Feel free to modify or extend it according to your needs.

---
ç
