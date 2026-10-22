Linux File Permissions Lab

Objective

Practice basic Linux file management and access control by inspecting file permissions and restricting access to a sample file.

Environment

Operating system: Ubuntu Linux

Virtualization: UTM on Apple Silicon Mac

Tools: ls, chmod, stat

Tasks Performed

Created a sample file named confidential.txt.

Inspected its initial permissions using ls -l.

Restricted file permissions using chmod 600.

Verified the resulting permissions using stat.

Results

The final permissions were 600 (-rw-------).

Owner: Read and write

Group: No permissions

Other users: No permissions

Security Takeaway

Restricting file permissions helps protect sensitive information from unauthorized access. This exercise demonstrates the Linux principle of least privilege: users should receive only the access they need.

Evidence

The screenshot below shows the file creation, permission change, and verification in the Ubuntu terminal.
