# j0k3r

```
- 🌎 Python developper
- 🔥 I code sometimes in HTML. CSS. Batch, Bash, VBS or C
- 🤖 I love making Discord bots or automatization scripts
- 💎 Learning pentesting & cibersecirity
- 💻 I have the best info leaks and databases
- 📷 View, star and fork my GitHub proyects!
- 👀 I like OSINT!
- 🥰 Contact me with me Discord (you can view it in my profile)
```

```
PROGRAMMING LANGUAJES
  ├── 🐍 Python
  ├── ⚙️ HTML
  ├── 🛠️ CSS
  ├── 🌐 BATCH
  ├── ☘️ Bash
  ├── ✏️ MarkDown
  └── 📌 VBS

OPERATIVE SYSTEMS
  ├── 📂 Windows
  └── 🐧 Linux (Debian)

WORKSPACES
  ├── ✨ Visual Studio Code
  ├── 📝 Windows Notepad
  ├── 🛡️ Nootepad ++
  ├── 🏆 GitHub
  └── 💼 Canva

MY REPOS
  ├── 🤖 snusbase-bot
  ├── 🔔 python-obfuscator
  ├── 🎀 proxy-scrapper
  ├── 👀 intelx-searcher
  └── 😈 shodan-email


CONTACT ME
  ├── 💎 Discord: j0k3r_s3rv1c35
  └── 📚 Mail: hidden
```

```python
import sqlite3

connection = sqlite3.connect('database.db') 

cursor = connection.cursor()

user_id = 1  
cursor.execute("SELECT email FROM usuarios WHERE id = ?", (user_id,))

result = cursor.fetchone()

if result:
    print(f"The mail of the user with ID {user_id} is: {result[0]}")
else:
    print(f"Not foudn the email of the user with the ID {user_id}")

cursor.close()
connection.close()
```

![scaler-create-impact](https://github.com/user-attachments/assets/05c2a37f-647e-431c-92aa-4ef6fee372d0)

