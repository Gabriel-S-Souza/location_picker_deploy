# location_picker_deploy

Repositório de deploy para o app Location Picker.

Este repositório contém os arquivos necessários para distribuição de atualizações do app via GitHub.

## Estrutura

- `version.json` - Arquivo com informações da versão atual e URL de download do APK

## Como usar

1. Atualize o `version.json` com a nova versão e URL do APK
2. Crie uma Release no GitHub com o arquivo `app-release.apk` anexado
3. O app verificará automaticamente este repositório quando o usuário clicar em "Verificar Atualizações"

