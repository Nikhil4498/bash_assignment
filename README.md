# Bash Scripting Assignment

## Objective
This assignment tests proficiency in writing and understanding Bash scripts. The scripts perform various tasks as outlined below.

## Scripts Included

1. **create_directories.sh**
   - **Description**: Creates a specific directory structure.
   - **Directory Structure**:
     ```
     /home/user/
         ├── projects/
         │   ├── project1/
         │   ├── project2/
         │   └── project3/
         ├── documents/
         └── downloads/
     ```
   - **Usage**: 
     ```bash
     ./create_directories.sh
     ```

2. **backup_txt_files.sh**
   - **Description**: Backs up all `.txt` files from a specified directory to a new directory named `backup` with a timestamp.
   - **Usage**:
     ```bash
     ./backup_txt_files.sh /path/to/directory
     ```

3. **user_info.sh**
   - **Description**: Displays information about the user (username, user ID, group ID, home directory, and shell being used).
   - **Usage**:
     ```bash
     ./user_info.sh
     ```

4. **disk_usage_alert.sh**
   - **Description**: Checks the disk usage of the root filesystem and sends an email alert if usage exceeds 80%.
   - **Usage**:
     ```bash
     ./disk_usage_alert.sh
     ```

5. **file_permission_checker.sh**
   - **Description**: Checks a file for read, write, and execute permissions and displays appropriate messages.
   - **Usage**:
     ```bash
     ./file_permission_checker.sh /path/to/file
     ```

6. **automated_backup.sh**
   - **Description**: Compresses the `/home/user/documents` directory into a tarball and moves it to the `/home/user/backup` directory. This script is scheduled to run daily using cron.
   - **Usage**:
     ```bash
     ./automated_backup.sh
     ```

7. **process_monitor.sh**
   - **Description**: Checks if a specific process (e.g., `apache2`) is running, starts it if not, and logs the action to a file.
   - **Usage**:
     ```bash
     ./process_monitor.sh
     ```

8. **text_file_analysis.sh**
   - **Description**: Analyzes a text file and counts the number of lines, words, and characters.
   - **Usage**:
     ```bash
     ./text_file_analysis.sh /path/to/textfile.txt
     ```

9. **system_report.sh**
   - **Description**: Generates a system information report including uptime, memory usage, CPU load, disk usage, and running processes. The report is saved to `system_report.txt`.
   - **Usage**:
     ```bash
     ./system_report.sh
     ```

10. **simple_calculator.sh**
    - **Description**: Acts as a simple calculator, prompting the user for two numbers and an operator (+, -, *, /), and displays the result.
    - **Usage**:
      ```bash
      ./simple_calculator.sh
      ```

## Installation
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/bash_assignment.git
