<div align="center">

<img src="banner.svg" width="100%" alt="João Rabelo banner"/>

[![GitHub](https://img.shields.io/badge/GitHub-rabelojp41-8B5CF6?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0014)](https://github.com/rabelojp41)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-João_Rabelo-C026FF?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0014)](https://www.linkedin.com/in/joao-rabelo-a30b56257/)
[![Gmail](https://img.shields.io/badge/Gmail-jprabelo41-FF2ECB?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0014)](mailto:jprabelo41@gmail.com)

</div>

---

Ooooi 👋 eu sou o **Rabelo**, da área de cyber! Curto muito **JJK** e **Hunter x Hunter**, e sou apaixonado por **roxo**: é a cor que atravessa os meus designs e boa parte das minhas inspirações (dá pra perceber por aqui).

### `whoami`

Assistente Jr. de Red Team na **AuditSafe** e estudante de **Defesa Cibernética** na FIAP. Trabalho na interseção entre **Cyber Threat Intelligence**, **Red Team** e **Pentest**: estudo quem ataca e como (TTPs, malware, campanhas) e uso isso pra atacar melhor, do reconhecimento OSINT ao relatório. No dia a dia também conduzo avaliações **PCI DSS v4.0.1**.

```
> foco atual:   Cyber Threat Intelligence · Red Team · Pentest (PTES)
> estudando:    análise de malware, threat research, emulação de adversários, Active Directory
> stack diária: Maltego · MITRE ATT&CK · Ghidra · FLOSS · YARA · Burp Suite · Nmap · Nessus
```

<div align="center">

| 🕵️ **Cyber Threat Intelligence** | 🩸 **Red Team** | 🎯 **Pentest** |
|:---:|:---:|:---:|
| OSINT com Maltego, perfil de threat actors, mapeamento de TTPs no MITRE ATT&CK e na Kill Chain, engenharia reversa com Ghidra e FLOSS, enriquecimento de IOCs (VirusTotal, Shodan, MISP, OpenCTI) e regras YARA, Sigma e Snort. | Pensar como o adversário: reconhecimento passivo e ativo, ataques a Active Directory e SMB, escalada de privilégio em Windows e Linux e estudo de emulação de APTs a partir de CTI. | Pentest interno e externo seguindo PTES, testes web/API (OWASP Top 10), varreduras credenciadas, validação de falsos positivos, priorização por CVSS e relatório técnico com remediação. |

</div>

---

### `experience.log`

**🟣 Assistente Jr. de Red Team — AuditSafe** · `05/2026 → atual`
- Pentest interno e externo (PTES) em Windows e Linux: OSINT com Maltego, enumeração e exploração controlada com Nmap, Burp Suite e Metasploit
- Testes web e de APIs com Burp Suite e OWASP ZAP, baseados no OWASP Top 10
- Varreduras credenciadas com Nessus (SMB/WMI, SSH) e Outpost24; triagem de findings, separação de falsos positivos e priorização por CVSS
- Validação de falsos positivos em scans ASV (bypass por CDN, cadeia SSL, flags de cookie, CORS)
- PCI DSS v4.0.1: segmentation testing entre o CDE e demais zonas em AWS (Security Groups, NACLs) e Azure (NSGs), com parecer PASS/FAIL/OBS
- Apoio em investigação de incidentes e análise de malware
- Automação em Python de relatórios, apresentações e certificados de treinamento

**🟣 Estagiário de Segurança da Informação e Infraestrutura — Pulnet** · `2025 → 2026`
- Apoio a pentests com reconhecimento e análise de vulnerabilidades (Nessus, Burp Suite, Nmap)
- Engenharia reversa com Ghidra e FLOSS e estudo educacional de um RAT (técnicas de ataque e evasão)
- Implantação por iniciativa própria do Wazuh (SIEM/XDR) pra enxergar os ataques pelo lado do defensor

---

### `projects // threat intel`

- 🧬 **[Nutshell Mapper](https://github.com/rabelojp41/NutShell-Mapper)** — framework de CTI em Python (18 módulos, ~8.000 linhas, 370 testes): extrai strings e IOCs com FLOSS, reverte ofuscação (Base64/XOR/hex), mapeia 40 técnicas do MITRE ATT&CK e a Kill Chain, sugere atribuição de grupo, enriquece via VirusTotal e Shodan, gera regras YARA validadas contra a amostra e exporta em STIX 2.1 e MISP. Tem resumo por IA local, conferido contra os achados.
- 🦠 **Backdoor.Win32.Tyupkin** — relatório de CTI sobre malware de jackpotting em ATMs: análise estática e dinâmica, engenharia reversa no Ghidra, regras YARA, Sigma e Snort e TTPs mapeadas no ATT&CK
- ⛓️ **IcedID → Cobalt Strike → Nokoyawa** — kill chain de ransomware mapeada no ATT&CK Navigator, com regras YARA pra classificação
- 🇰🇵 **Kimsuky** — investigação de threat actor no Maltego (FIAP, em grupo): campanhas, vítimas e setores-alvo, técnicas, malware e ferramentas mapeados no ATT&CK

### `projects // red team & pentest`

- 💀 **Labs black-box documentados** (relatório, remediação e mapeamento ATT&CK):
  - **HidricaNova** — Nmap → FTP anônimo → OSINT interno → credential stuffing com Hydra → sudo/GTFOBins → root, com containers vulneráveis descobertos
  - **Tempest** — SQL Injection em MariaDB, sqlmap e quebra de hashes SHA-256 com John the Ripper
  - **Constant** — FTP anônimo, reuso de senha e sudo irrestrito
- 🏰 **Active Directory** — TryHackMe Intro to AD Breaching, ataques AD/SMB com NetExec e Evil-WinRM
- 🪜 **Privesc Windows** — WinPEAS, PowerUp, SharpUp e PrintSpoofer
- 🌐 **Web exploitation** — SQL Injection, Command Injection e SSTI em laboratório
- 📚 **Base de conhecimento de vulnerabilidades** (Notion + GitHub) com scripts Python de validação: TLS 1.0/1.1, BEAST, CORS, clickjacking, flags de cookie, open redirect, source maps, cadeia SSL e bypass por porta de origem TCP/UDP
- 🎮 TryHackMe e Hack The Box (Cap, Facts)

### `projects // outros`

- 🕹️ **OBL1VION** — jogo de conscientização em cibersegurança desenvolvido para a Leroy Merlin: roteiros, direção de arte e documentação técnica

---

### `stack.json`

<div align="center">

**Threat Intelligence & OSINT**

![Maltego](https://img.shields.io/badge/Maltego-2D0A4E?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-2D0A4E?style=flat-square)
![Cyber Kill Chain](https://img.shields.io/badge/Cyber_Kill_Chain-2D0A4E?style=flat-square)
![STIX 2.1](https://img.shields.io/badge/STIX_2.1-2D0A4E?style=flat-square)
![MISP](https://img.shields.io/badge/MISP-2D0A4E?style=flat-square)
![OpenCTI](https://img.shields.io/badge/OpenCTI-2D0A4E?style=flat-square)
![VirusTotal](https://img.shields.io/badge/VirusTotal-2D0A4E?style=flat-square&logo=virustotal&logoColor=C026FF)
![MalwareBazaar](https://img.shields.io/badge/MalwareBazaar-2D0A4E?style=flat-square)
![AlienVault OTX](https://img.shields.io/badge/AlienVault_OTX-2D0A4E?style=flat-square)
![Shodan](https://img.shields.io/badge/Shodan-2D0A4E?style=flat-square)
![Censys](https://img.shields.io/badge/Censys-2D0A4E?style=flat-square)

**Malware & Engenharia Reversa**

![Ghidra](https://img.shields.io/badge/Ghidra-2D0A4E?style=flat-square)
![FLOSS](https://img.shields.io/badge/FLOSS-2D0A4E?style=flat-square)
![PEStudio](https://img.shields.io/badge/PEStudio-2D0A4E?style=flat-square)
![Detect It Easy](https://img.shields.io/badge/Detect_It_Easy-2D0A4E?style=flat-square)
![Any.Run](https://img.shields.io/badge/Any.Run-2D0A4E?style=flat-square)

**Detecção & Regras**

![YARA](https://img.shields.io/badge/YARA-2D0A4E?style=flat-square)
![Sigma](https://img.shields.io/badge/Sigma-2D0A4E?style=flat-square)
![Snort](https://img.shields.io/badge/Snort-2D0A4E?style=flat-square&logo=snort&logoColor=FF2ECB)
![Wazuh](https://img.shields.io/badge/Wazuh-2D0A4E?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-2D0A4E?style=flat-square&logo=wireshark&logoColor=8B5CF6)

**Red Team & Pentest**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-2D0A4E?style=flat-square&logo=kalilinux&logoColor=8B5CF6)
![Nmap](https://img.shields.io/badge/Nmap-2D0A4E?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-2D0A4E?style=flat-square&logo=burpsuite&logoColor=C026FF)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-2D0A4E?style=flat-square&logo=owasp&logoColor=8B5CF6)
![Metasploit](https://img.shields.io/badge/Metasploit-2D0A4E?style=flat-square&logo=metasploit&logoColor=FF2ECB)
![sqlmap](https://img.shields.io/badge/sqlmap-2D0A4E?style=flat-square)
![Hydra](https://img.shields.io/badge/Hydra-2D0A4E?style=flat-square)
![John the Ripper](https://img.shields.io/badge/John_the_Ripper-2D0A4E?style=flat-square)
![NetExec](https://img.shields.io/badge/NetExec-2D0A4E?style=flat-square)
![Evil-WinRM](https://img.shields.io/badge/Evil--WinRM-2D0A4E?style=flat-square)
![WinPEAS](https://img.shields.io/badge/WinPEAS-2D0A4E?style=flat-square)
![GTFOBins](https://img.shields.io/badge/GTFOBins-2D0A4E?style=flat-square)

**Scanning & Compliance**

![Nessus](https://img.shields.io/badge/Nessus-2D0A4E?style=flat-square)
![Outpost24](https://img.shields.io/badge/Outpost24-2D0A4E?style=flat-square)
![PCI DSS v4.0.1](https://img.shields.io/badge/PCI_DSS_v4.0.1-2D0A4E?style=flat-square)
![CVSS](https://img.shields.io/badge/CVSS-2D0A4E?style=flat-square)

**Ambientes**

![Windows](https://img.shields.io/badge/Windows-2D0A4E?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-2D0A4E?style=flat-square&logo=linux&logoColor=8B5CF6)
![Active Directory](https://img.shields.io/badge/Active_Directory-2D0A4E?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-2D0A4E?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-2D0A4E?style=flat-square)

**Dev & Automação**

![Python](https://img.shields.io/badge/Python-2D0A4E?style=flat-square&logo=python&logoColor=C026FF)
![Bash](https://img.shields.io/badge/Bash-2D0A4E?style=flat-square&logo=gnubash&logoColor=FF2ECB)
![PowerShell](https://img.shields.io/badge/PowerShell-2D0A4E?style=flat-square)
![Git](https://img.shields.io/badge/Git-2D0A4E?style=flat-square&logo=git&logoColor=8B5CF6)
![Node.js](https://img.shields.io/badge/Node.js-2D0A4E?style=flat-square&logo=nodedotjs&logoColor=8B5CF6)

</div>

---

### `certifications // education`

- 🎓 **Tecnólogo em Defesa Cibernética** — FIAP (previsão 2026)
- 📜 **ISC2 Certified in Cybersecurity (CC)**
- 📜 **FIAP Certified Penetration Testing Professional** (jun/2026)
- 📜 **FIAP Certified Information Security Officer** (dez/2025)
- 📜 **Pentester na Era da IA** — IBSEC
- 📜 **Red Hat RH124 / RH134** — System Administration I e II
- 📜 **Inglês C1** — EF SET
- ⏳ **CompTIA Security+** — prova agendada pra 10/12/2026
- ⏳ **SYCP** — Solyd One (em andamento)

---

<div align="center">

```
[ osint ] — [ profile actor ] — [ map TTPs ] — [ recon ] — [ exploit ] — [ emulate ] — [ report ]
```

<sub>construído em ambiente isolado · aprendendo em público</sub>

</div>
