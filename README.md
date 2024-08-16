## Hi there 👋

Saya, Agus, telah menjelajahi dunia pemrograman sejak tahun 2018. Selama perjalanan ini, saya telah menciptakan berbagai jenis script—mulai dari yang ringan hingga yang kompleks. Setiap baris kode yang saya tulis adalah bagian dari dedikasi saya untuk terus berkembang dan menghadirkan solusi yang efektif.

```asm
section .data
    full_name db "Agus, The Fullstack Maestro", 0
    age db 17
    location db "Jakarta, the Heart of Indonesia", 0
    career db "Digital Artisan", 0
    role db "Architect of Web Ecosystems", 0
    skills db "HTML & CSS", 0
           db "JavaScript", 0
           db "Bootstrap", 0
           db "Tailwind CSS", 0
           db "Node.js", 0
           db "Express.js", 0
           db "PHP", 0
           db "Java", 0
           db "Python", 0
           db "Ruby", 0
           db "C", 0
           db "C++", 0
           db "C#", 0
           db "F#", 0
           db "Go", 0

section .text
global _start

_start:
    ; Display the full name with flair
    mov eax, 4            ; syscall: write
    mov ebx, 1            ; file descriptor: stdout
    mov ecx, full_name    ; message to write
    mov edx, 26           ; length of message
    int 0x80              ; interrupt to invoke syscall
    
    ; Display location, the stage of the journey
    mov eax, 4
    mov ebx, 1
    mov ecx, location
    mov edx, 30
    int 0x80

    ; Display career, the craft mastered
    mov eax, 4
    mov ebx, 1
    mov ecx, career
    mov edx, 16
    int 0x80

    ; Display role, the expertise defined
    mov eax, 4
    mov ebx, 1
    mov ecx, role
    mov edx, 26
    int 0x80

    ; Display skills, the tools of the trade
    mov eax, 4
    mov ebx, 1
    mov ecx, skills
    mov edx, 120          ; total length of all skill entries
    int 0x80

    ; Exit gracefully, leaving a mark
    mov eax, 1            ; syscall: exit
    xor ebx, ebx          ; exit code 0
    int 0x80              ; interrupt to invoke syscall

```

<h1 align="center"> Connect with me
<p align="center">
  <a href="https://instagram.com/randirmli"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/> 
  <a href="https://wa.me/message/5PJOOLKRSXXRP1"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
  <a href="https://www.facebook.com/RndyTech"><img src="https://img.shields.io/badge/Facebook-%234267B2.svg?&style=for-the-badge&logo=facebook&logoColor=white" />
  <a href="https://t.me/RndyTech"><img src="https://img.shields.io/badge/Telegram-%230088cc.svg?&style=for-the-badge&logo=telegram&logoColor=white" /> <br>
  <a href="https://github.com/randiramli"><img src="https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github" /> 
  <a href="https://youtube.com/channel/UCm9U8cThhUZnMYraQVmr2-Q"><img src="https://img.shields.io/youtube/channel/subscribers/UCdzWwbApjkyODby7_MoRYlA?style=social" /> <br>
</p>
