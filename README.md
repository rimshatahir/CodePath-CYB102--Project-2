# CodePath-CYB102--Project-2  
**Project monitoring file modifications using the Linux Audit daemon to detect unauthorized changes.**  

## **Let's wget This Bread!**  

### **Project Overview**  
In this project, we use the Linux Audit daemon (`auditd`) to monitor file changes, execute attack scripts, and analyze system logs to identify unauthorized modifications in a protected directory.  

### **Goals**  
- Configure audit rules to track file modifications in `/protected_files`.  
- Execute attack scripts to simulate unauthorized changes.  
- Analyze audit logs to determine which attack altered which file.  

### **Steps Taken**  
1. Downloaded and unzipped the project repository.  
2. Set up execution permissions for the attack scripts.  
3. Configured `auditd` rules to monitor the `/protected_files` directory.  
4. Executed three attack scripts that modified files.  
5. Used `ausearch` to analyze audit logs and identify modified files.  

### **Results**  
- **Modified Files:**  
  - `/protected_files/file1.txt`  
  - `/protected_files/file2.txt`  
  - `/protected_files/file3.txt`  
- **Attack vs. File Pairings:**  
  - `attack-a` → `file1.txt`  
  - `attack-b` → `file2.txt`  
  - `attack-c` → `file3.txt`  


