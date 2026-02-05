<div align="center">

<h1>
  <span style="color:#00ff88;">xDTaraZ</span>
</h1>

<p>
  <b>16 y/o Developer • Reverse Engineering • FiveM Systems</b>
</p>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&pause=900&color=00FF88&center=true&vCenter=true&width=520&lines=root%40xDTaraZ%3A~%24+whoami;building+tools+%7C+learning+internals;reverse+engineering+%26+binary+analysis;FiveM+systems+%26+server+tooling;clean+code+%7C+performance+first" />

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00ff88&height=110&section=header&text=&fontSize=0" />

</div>

---

<div align="center">

```txt
------------------- [ xDTaraZ@localhost ] -------------------
 > focus     : reverse engineering / tooling / FiveM systems
 > mindset   : clean code, fast execution, full control
 > currently : building private projects & improving internals
-------------------------------------------------------------
</div>

<div align="center">
; -----------------------------------------------------------
; bootlog: /dev/tty0
; -----------------------------------------------------------
push rbp
mov  rbp, rsp

; --- [ System Call: sys_write ] ---
mov  rax, 1                         ; syscall: write
mov  rdi, 1                         ; fd: stdout
lea  rsi, [rip + msg_bin]           ; buf: binary string
mov  rdx, msg_bin_len               ; count
syscall

lea  rsi, [rip + msg_txt]           ; buf: text string
mov  rdx, msg_txt_len
syscall

mov  rsp, rbp
pop  rbp
ret

msg_bin:     db "01001001 00100111 01101101 00100000 01101010 01110101 01110011 01110100 00100000 01100001 00100000 01101011 01101001 01100100", 0xA
msg_bin_len: equ $-msg_bin

msg_txt:     db "> I'm just a kid.", 0xA
msg_txt_len: equ $-msg_txt
; -----------------------------------------------------------
</div>

🧠 About Me
I’m a 16-year-old developer who enjoys building tools and understanding how software works under the hood.

- 🔍 Reverse engineering, debugging, binary analysis

- ⚙️ FiveM scripting, server systems, automation tooling

- 🛡 Security concepts (anti-tamper / anti-exploit style projects)

🛠 Tech Stack
<p align="left"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/lua/lua-original.svg" height="42" alt="Lua" /> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="42" alt="C++" /> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="42" alt="C#" /> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="42" alt="Python" /> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="42" alt="JavaScript" /> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" height="42" alt="Go" /> </p>

🔥 What I Build
⚙️ FiveM systems & server-side tooling

🧩 Reverse engineering utilities & experiments

🛡 Anti-tamper / detection concept projects

🧪 Debugging & automation tools

📡 Connect with me
<p align="left"> <a href="https://discord.com/users/1339675395892711455"> <img src="https://lanyard.cnrad.dev/api/1339675395892711455?theme=dark&bg=0d1117&borderRadius=12px&idleMessage=offline" /> </a> </p>

<div align="center"> <sub><i>"clean code • performance first • full control"</i></sub> </div>

<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff88,100:0d1117&height=110&section=footer&text=&fontSize=0" /> </div>
