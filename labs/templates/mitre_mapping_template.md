# MITRE ATT&CK Mapping

| Тактика | Техника | Почему применимо |
|---|---|---|
| Credential Access | LLMNR/NBT-NS Poisoning and SMB Relay | Наблюдалась попытка перехвата/использования NTLM-аутентификации |
| Discovery | Network Service Discovery | Были признаки обращения к сетевым ресурсам |
| Lateral Movement | Remote Services: SMB/Windows Admin Shares | SMB использовался для дальнейшей активности |