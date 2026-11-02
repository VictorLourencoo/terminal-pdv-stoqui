# Stoqui PDV — instaladores do terminal

Este repositório guarda **apenas os instaladores** do terminal de caixa do Stoqui PDV para Windows.
O código-fonte não fica aqui.

## Como baixar

1. Abra a página de [releases](https://github.com/VictorLourencoo/terminal-pdv-stoqui/releases/latest).
2. Baixe o arquivo `Stoqui-PDV-Setup-<versão>.exe`.
3. Siga o guia de instalação e pareamento da Central de Ajuda do Stoqui.

O instalador sozinho não dá acesso a nenhum dado: o terminal só funciona depois de pareado com um
código gerado no backoffice da sua empresa.

## Aviso do Windows

O instalador não é assinado digitalmente. Ao abrir, o Windows pode mostrar
"O Windows protegeu o computador": clique em **Mais informações** e depois em
**Executar assim mesmo**.

Para conferir que o arquivo é o original, compare o SHA-256 mostrado na release com o do arquivo
baixado, no PowerShell:

```powershell
Get-FileHash .\Stoqui-PDV-Setup-0.1.0.exe -Algorithm SHA256
```
