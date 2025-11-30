Immagina di essere un assistente DevOps/Windows super esperto di WSL, Claude Desktop e MCP filesystem.  
Voglio configurare Claude Desktop in modo che possa accedere a un progetto che si trova dentro WSL, usando il percorso `\\wsl$` come filesystem di Windows.

Questi sono i dettagli del mio ambiente:

- Sistema operativo host: Windows 10/11
    
- Distro WSL: verificare distro attuale
    
- Path del progetto in WSL: `\\wsl.localhost\Ubuntu\home\brusc\Projects`
    
- Editor che già uso: VS Code e/o Cursor su quella cartella in WSL
    
- Claude: Claude Desktop installato su Windows
    

Obiettivo:

1. Ottenere il path Windows corretto (in stile `\\wsl$\...`) corrispondente alla cartella del progetto in WSL.
    
2. Configurare Claude Desktop perché veda quella cartella come workspace / cartella autorizzata nel suo Filesystem.
    
3. (Opzionale) Preparare anche una configurazione MCP “filesystem” o un MCP server dedicato al filesystem WSL, da aggiungere al file di configurazione di Claude Desktop, così che Claude Code possa navigare e modificare file in quella cartella.
    

Ti chiedo di:

- Darmi i comandi esatti da lanciare in WSL (compreso l’uso di `wslpath -w`) per tradurre il path Linux in path Windows.
    
- Restituirmi esplicitamente il path `\\wsl$\...` da incollare in Claude Desktop.
    
- Descrivere i passaggi clic‑per‑clic dentro Claude Desktop per aggiungere quella cartella al Filesystem.
    
- Fornirmi, se opportuno, uno snippet completo di configurazione MCP in JSON o YAML per Claude Desktop, con campi tipo `command`, `args`, `env`, `basePath`, ecc., usando valori realistici basati sul mio setup.
    
- Evidenziare eventuali problemi tipici (permessi, performance, path strani con spazi) e come risolverli.
    

Quando rispondi:

- Assumi che io sia in grado di modificare file di configurazione e usare la shell WSL senza problemi.
    
- Non limitarti a descrivere in astratto: voglio path e snippet di configurazione pronti da copiare e adattare.
    