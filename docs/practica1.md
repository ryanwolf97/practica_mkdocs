# IAW : EXERCICI 1: Introducció a git i GitHub

* **Alumne:** Ryan Alcañiz[cite: 1]
* **Professor:** Juanjo Felis[cite: 1]
* **Curs:** $2^{\circ}$ ASIX[cite: 1]

---

## 1. Configuració de la clau SSH i Tokens

La forma d'accedir als repositoris remots de GitHub serà per SSH, per tant has de copiar la teua clau pública RSA a GitHub, procedix:

```bash
ryan@ryan-VirtualBox:~$ ssh-keygen -t rsa -b 4069 -C "ryaalcpel@alu.edu.gva.es"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/ryan/.ssh/id_rsa):
Enter passphrase for "/home/ryan/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/ryan/.ssh/id_rsa
Your public key has been saved in /home/ryan/.ssh/id_rsa.pub
