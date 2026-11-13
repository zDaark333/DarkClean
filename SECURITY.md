# Confiança dos downloads e relatos de segurança

## Downloads e atualizações

Esta distribuição oferece o instalador oficial para Windows. Ele não possui
assinatura digital de editor. O hash SHA-256 publicado na mesma Release serve
para comparar o arquivo baixado com o arquivo publicado; não equivale a uma
assinatura do editor.

Desde a 1.0.1, o aplicativo verifica publicações oficiais ao abrir e periodicamente.
Antes de oferecer uma atualização, verifica a assinatura Ed25519 dos metadados
`installer-update.json` com a chave pública incorporada ao aplicativo. O download
deve corresponder ao tamanho e SHA-256 autenticados. Esses dados são conferidos
novamente antes de abrir o instalador.

Use os downloads de https://github.com/zDaark333/DarkClean/releases.
Não desative as proteções do Windows por orientação de páginas ou mensagens que
aleguem ser necessárias para baixar o DarkClean.

## Confirmação e proteção das chaves

O aplicativo pede confirmação para baixar e para instalar. A assinatura de
metadados não é um certificado Authenticode nem elimina os avisos do Windows.
Arquivos alterados, assinaturas inválidas e origens diferentes do repositório
oficial não devem ser instalados pelo atualizador.

Chaves privadas, senhas e certificados privados não devem integrar o repositório,
instaladores, ZIPs ou relatórios públicos.

## Conta local

Desde a 1.1.0, a conta funciona offline e pertence ao perfil do Windows em uso.
A senha é armazenada como hash PBKDF2-HMAC-SHA256, com 600.000 iterações e sal
aleatório. O código de recuperação também não é guardado de forma legível.
Tentativas incorretas repetidas causam uma espera temporária.

Essa conta organiza o acesso à interface do DarkClean; não substitui a segurança
do Windows nem cifra os backups e demais arquivos do aplicativo. Uma pessoa com
controle do perfil ou privilégios de administrador pode alterar os arquivos locais.
Não envie a senha, o código de recuperação ou `conta-local.json` em relatos públicos.

## Relatos de problemas

As Issues públicas podem ser usadas para falhas comuns, sem dados pessoais.
Não inclua senhas, chaves, IPs, nomes de usuário locais nem relatórios completos
sem revisão. Para um problema de segurança com detalhes exploráveis, procure
primeiro um canal privado disponibilizado pelo [mantenedor](https://github.com/zDaark333).
