# Manual SSH Brute-Force Attack (Educational Lab Demo)

This project documents a **manual SSH brute-force attack** against a vulnerable Metasploitable 2 target. This was done for educational and ethical hacking practice purposes only.

## 🎯 Target Details
- **Target IP**: `192.168.XXX.XXX`
- **Service**: SSH (port 22)
- **Machine**: Metasploitable 2
- **Operating System**: Linux 2.6.24-16-server
- **Successful Credentials**:
  - Username: `msfadmin`
  - Password: `msfadmin`

## ⚙️ Attack Method
- Custom-made wordlists were created:
  - `usertotest.txt` (5 usernames)
  - `passwordtotest.txt` (5 passwords)
- Manual brute-forcing was done (not using tools like `hydra`, `ncrack`, etc.)
- SSH login attempt was repeated across combinations until success.
- UID and group info was printed to confirm system access.

## 🧪 Result Snapshot
In Result Folder

