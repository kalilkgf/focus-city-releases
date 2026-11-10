# Focus City — atualizações

Este repositório guarda só os arquivos que o Focus City baixa para se atualizar sozinho.
O código do jogo fica em um repositório privado.

- `latest.json`: versão mais nova, endereço do pacote e SHA-256 para conferir o download.
- `updates/app-<versão>.zip`: pacote do jogo (sem o Electron).

O jogo consulta `latest.json` ao abrir e a cada 3 horas. Nenhum dado da cidade ou do computador é enviado.
