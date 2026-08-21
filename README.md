8043 / 20000 characters (1275 words)
E.C.H.O  
A J.A.R.V.I.S. style personal assistant for Windows

This project gets a boost from AI. If that bugs you, well… go ahead and complain.

E.C.H.O is a J.A.R.V.I.S project. You can launch apps, manage files, chat on Discord, handle email, keep an eye on your system, control Windows, run background commands, and a whole lot more—just by typing simple instructions.

⚠️ Heads up: E.C.H.O is still under heavy development. Not everything has been tested yet. If something breaks or acts weird, please open an issue and give as much detail as you can.

✨ What Can E.C.H.O Do?  
🖥️ Apps & Games  

- open <app> — Launch apps like Chrome, Firefox, Discord, VS Code, Equibop, Obsidian, OBS, and others  
- install <app> — Pulls up the download page if the app isn’t installed  
- play <game> — Fire up Steam games like CS2, GTA V, Rust, Minecraft, etc.  
- apps — See which apps are available  
- search <query> — Google search  
- image <query> — Google Images search  
- url <url> — Open any website  
- youtube <query> / yt <query> — Search YouTube  
- youtube open <query> — Open the first YouTube result

💬 Discord  

- discord send <msg> — Send a message to a set channel  
- discord dm <id or name> <msg> — DM support, with ID/name mappings  
- discord status — Check if the bot’s connected  
- discord set userid <ID> name <NAME> — Map usernames to user IDs  
- discord users — List all saved mappings  
- discord remove userid <ID> — Remove a user mapping  
- discord help — Get help with Discord commands

📧 Email  

- email / inbox — Read your inbox  
- email unread — See emails you haven’t read yet  
- email search <query> — Search emails  
- send email to <address> — Write and send an email

📅 Calendar, Tasks & Notes  

- event add <title> on YYYY-MM-DD at HH:MM — Add a calendar event  
- today / tomorrow / week / upcoming — See what’s on your schedule  
- event complete <id> — Mark an event done  
- event delete <id> — Delete an event  
- task add <title>#high due YYYY-MM-DD — Add a task with priority and due date  
- tasks — List your to-dos  
- task done <id> / task undo <id> — Mark a task complete, or bring it back  
- overdue — Check for overdue stuff  
- note save <name>: <content> — Save a quick note  
- note read <name> — Read your note  
- notes — List all notes

📊 System Monitoring  

- hardware / pc specs — Show detailed hardware stats  
- system / sysinfo — Quick system overview  
- gpu / graphics — See your GPU details  
- disks / drives — List disk drives  
- cpu / memory / battery — Check system resources  
- processes / top — See top processes by CPU  
- dashboard — Get a full system dashboard  
- health / health summary — Run a system health check  
- health trend <metric> / health chart <metric> — Graph health metrics

⚙️ Process & Service Management  

- kill <process> — End a process by name or PID  
- kill tree <process> — End a process and its children  
- kill all <name> — End every matching process  
- services — List all Windows services  
- startup — What starts with Windows?

🌐 Network Tools  

- ip — Show public and local IPs  
- ping <host> — Ping a host  
- wifi / wifi password [ssid] — Show Wi-Fi info or saved passwords  
- wifi audit — Run a quick Wi-Fi security check  
- dns <domain> — DNS lookup  
- ports [host] — Scan common ports

📁 File Management  

- find <name> — Search for files  
- read <path> — Read a file or check a folder  
- write <path> <content> — Write to a file  
- info <path> — Info about any file  
- rename — Rename files  
- delete — Remove files  
- copy — Copy files  
- mkdir — Make new folders  
- large files [dir] — Track down big files  
- duplicates [dir] — Spot duplicate files  
- drives — See disk usage  
- clean temp — Find temp files  
- empty recycle — Nuke the recycle bin

🔌 USB  

- usb / list usb — List plugged-in USB drives  
- usb scan [drive] — Scan files on a USB drive  
- usb search <query> — Search for files on USB drives  
- usb usage — Check USB disk usage

📋 Clipboard  

- clipboard — Read what’s on the clipboard  
- copy <text> — Copy some text  
- clipboard history — See your clipboard history  
- parse clipboard — Analyze clipboard contents

🪟 Windows Management  

- windows — List open windows  
- focus <title> — Bring a window to the front  
- snap <window> left/right/center/maximize — Snap windows around  
- window left/right/center/maximize/restore/close <title> — Move and manage windows  
- window pos <title> — Get a window’s position  
- minimize all — Hide everything at once

🔐 Security  

- generate password / generate passphrase — Make strong passwords  
- analyze password <pwd> — Check password strength  
- save/get/list passwords — Manage your vault  
- encrypt / decrypt — Encrypt or decrypt files

🧵 Background Tasks  

- bg run <name> <cmd> — Run a task in the background  
- bg admin <name> <cmd> — Run a background command as admin  
- bg script <name> <code> — Run a script in the background  
- bg list / bg output <id> — List or inspect background jobs  
- bg kill <id> / bg kill all — Stop background jobs

👑 Administration  

- admin run <cmd> — Run commands as admin  
- elevate — Restart E.C.H.O as admin  

🛠️ Fun & Utilities  

- calc <expression> — Calculate math  
- convert <value> <from> <to> — Convert units  
- dice / coin / color — Random fun  
- uuid / quote / fact — Generate stuff  
- banner <text> — Make ASCII art  
- palette <color> — Create a palette  
- qr <text> — Generate a QR code  
- timer <time> — Set a timer  
- remind me <msg> in <time> — Set a reminder  
- pomodoro — Pomodoro sessions  
- focus mode on/off — Toggle focus mode  
- quick note <text> — Jot a note  
- wallpaper — Change your wallpaper

🖥️ HUD Overlay  

- hud on/off — Toggle the HUD  
- hud mini — Mini HUD mode  
- hud network — Show network info  
- hud 3d — 3D HUD  
- hud clock — Clock overlay  
- 3d desktop — Visualize open windows on a 3D map

👨‍💻 Text & Development  

- translate <text> — Translate text  
- env [name] — Show environment variables  
- git <args> — Run Git commands

🤖 AI  

E.C.H.O is powered by Groq’s AI.  

- hello — Say hi  
- who are you — Learn about E.C.H.O  
- what time — Find out the current time  
- what date — Get today’s date  
- Everything else? The AI agent handles it

🔊 Text-to-Speech  

- voice on / voice off — Enable or disable TTS  
- say <text> / speak <text> — Read text out loud  
- stop speaking / quiet — Shut up (nicely)  
- voices — See available voices  
- voice <name> — Change the active voice  
- speech rate <rate> — Adjust speaking speed

📢 Update Notifications  

Want to know when something new drops? Add E.C.H.O’s Discord bot to your account, then DM your Discord user ID to @x4byss on Discord.
[Don’t know your Discord user ID?](https://discord.com/oauth2/authorize?client_id=1540150541160812675)
[Here’s how to find it.](https://letmegooglethat.com/?q=how+to+find+discord+user+ID)

🐛 Found a Bug?  

E.C.H.O isn’t finished. Expect some rough edges.

If something doesn’t work:

- Double-check if the command behaves like in this readme  
- Try repeating it  
- If it’s still busted, open a new issue, include the command, what happened, and what you expected

Pull requests, ideas, and improvements are always welcome.

🚧 Development in Progress  

E.C.H.O is still growing and learning. Some things above are new or still experimental, so don’t be shocked if you uncover a bug before I do.
This project was assisted by ai.
