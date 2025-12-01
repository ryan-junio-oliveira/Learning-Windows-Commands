# Comandos Importantes do Windows

## 1. Comandos via WIN + R (Executar)

### Administração e Configurações

-   **Gerenciar usuários:** `netplwiz`, `control userpasswords2`
-   **Gerenciamento de Computador:** `compmgmt.msc`
-   **Usuários e Grupos Locais:** `lusrmgr.msc`
-   **Editor de Diretiva Local:** `gpedit.msc`
-   **Editor de Registro:** `regedit`
-   **Serviços do Windows:** `services.msc`
-   **Monitor de Recursos:** `resmon`
-   **Gerenciador de Dispositivos:** `devmgmt.msc`
-   **Informações do Sistema:** `msinfo32`

### Ferramentas de Sistema

-   **Painel de Controle:** `control`
-   **Propriedades do Sistema:** `sysdm.cpl`
-   **Rede e Compartilhamento:** `ncpa.cpl`
-   **Configurações do Windows:** `ms-settings:`
-   **Limpeza de Disco:** `cleanmgr`
-   **Diagnóstico de Memória:** `mdsched`

### Interface

-   **Explorador de Arquivos:** `explorer`
-   **Calculadora:** `calc`
-   **Bloco de Notas:** `notepad`
-   **Teclado Virtual:** `osk`

------------------------------------------------------------------------

## 2. Comandos importantes no CMD

### Rede

-   `ipconfig /all`
-   `ipconfig /release && ipconfig /renew`
-   `ping google.com`
-   `tracert google.com`
-   `netstat -an`
-   `ipconfig /flushdns`

### Sistema

-   `systeminfo`
-   `tasklist`
-   `taskkill /IM nome.exe /F`
-   `query user`
-   `sfc /scannow`
-   `DISM /Online /Cleanup-Image /RestoreHealth`

### Arquivos e Diretórios

-   `dir`
-   `cd pasta`
-   `copy origem destino`
-   `move origem destino`
-   `del arquivo`
-   `mkdir nome`

------------------------------------------------------------------------

## 3. Comandos avançados

### Usuários

-   `net user nome senha /add`
-   `net localgroup administrators nome /add`
-   `net user`

### Energia

-   `shutdown /s /t 0`
-   `shutdown /r /t 0`
-   `shutdown /a`
