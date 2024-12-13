# Bash Script: Enhanced Command Utility

## Overview
This script provides a collection of utilities to manage services, monitor system performance, analyze logs, and back up files. It simplifies common administrative tasks using a command-line interface.

## Features
- **Service Management**:
  - List all running services.
  - Start or stop specific services.
- **System Monitoring**:
  - Display system load information.
- **Disk Management**:
  - Check disk usage statistics.
- **Process Monitoring**:
  - View active processes and their resource usage.
- **Log Analysis**:
  - Analyze recent system logs.
- **Backup**:
  - Backup specified files or directories.

## Usage
Run the script with the following syntax:

```bash
./script_name.sh [COMMAND] [OPTIONS]
```

### Commands
#### Service
- `service list`: Lists all active services.
- `service start <name>`: Starts the specified service.
- `service stop <name>`: Stops the specified service.

#### System
- `system load`: Displays the system load information.

#### Disk
- `disk usage`: Shows disk usage statistics.

#### Process
- `process monitor`: Monitors running processes and their resource usage.

#### Logs
- `logs analyze`: Analyzes the latest system logs.

#### Backup
- `backup <path>`: Creates a compressed backup of the specified path.

### Options
- `--help`: Displays help information for the script.
- `--version`: Shows the script version.

## Examples
1. List all services:
   ```bash
   ./script_name.sh service list
   ```

2. Start a service:
   ```bash
   ./script_name.sh service start apache2
   ```

3. Display system load:
   ```bash
   ./script_name.sh system load
   ```

4. Backup a directory:
   ```bash
   ./script_name.sh backup /path/to/directory
   ```

## Prerequisites
- Ensure the script is executable:
  ```bash
  chmod +x script_name.sh
  ```
- Requires Bash shell and necessary permissions to execute system commands (e.g., `systemctl`).

## Version
Current version: `0.1.0`

## License
This script is distributed under the MIT License.

