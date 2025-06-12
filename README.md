# ⚔️ Kali Linux - Hands-on (FutureIntern Cybersecurity Internship Task 1)

Hey! I'm Prajwal Sharma, currently pursuing B.Tech in Computer Science and working as a Cybersecurity Intern at FutureIntern.

This is my first hands-on project in Kali Linux where I practiced essential Linux commands, installed tools from GitHub, and executed some basic attacks ethically on the test site `http://testphp.vulnweb.com`.

---

## 🧠 What I Did:
- Practiced Linux commands (`ls`, `cat`, `ip a`, etc.)
- Installed and used tools like **SQLMap** & **Dirsearch**
- Targeted a legal vulnerable site for testing (no actual harm done)

---

## 🛠️ Tools Used:
- Kali Linux
- SQLMap
- Dirsearch
- GitHub

---

## 🔍 Commands I Practiced

```bash
# Linux Commands
pwd
ls -la
cat /etc/passwd
ip a
whoami

# SQLMap (SQL Injection)
sqlmap -u "http://testphp.vulnweb.com/listproducts.php?cat=1" --dbs

# Dirsearch (Directory brute-forcing)
git clone https://github.com/maurosoria/dirsearch.git
cd dirsearch
python3 dirsearch.py -u http://testphp.vulnweb.com/



