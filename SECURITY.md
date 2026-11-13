# Confiança dos downloads e relatos de segurança

## Prévia pública 11.2.2

Esta distribuição oferece um instalador manual para Windows. Ele não possui
assinatura digital de editor. O hash SHA-256 publicado na mesma Release serve
para comparar o arquivo baixado com o arquivo publicado; não equivale a uma
assinatura do editor.

O atualizador do aplicativo está desabilitado nesta prévia. Não há `manifest.json`,
`manifest.sig` ou ZIP de atualização automática para esta entrega. Não trate
arquivos com esses nomes enviados por terceiros como parte desta Release.

Use os downloads de https://github.com/zDaark333/DarkClean-Updates/releases.
Não desative as proteções do Windows por orientação de páginas ou mensagens que
aleguem ser necessárias para baixar o DarkClean.

## Futuras atualizações gerenciadas

O mecanismo gerenciado só deverá ser divulgado após gerar e testar o layout de
instalação correspondente, o manifesto assinado com Ed25519, a verificação de
tamanho e SHA-256 e a recuperação da versão anterior. A disponibilidade desse
código no projeto local não significa que ele esteja ativo na prévia atual.

Chaves privadas, senhas e certificados privados não devem integrar o repositório,
instaladores, ZIPs ou relatórios públicos.

## Relatos

As Issues públicas podem ser usadas para falhas comuns, sem dados pessoais.
Não inclua senhas, chaves, IPs, nomes de usuário locais nem relatórios completos
sem revisão. Para um problema de segurança com detalhes exploráveis, procure
primeiro um canal privado disponibilizado pelo [mantenedor](https://github.com/zDaark333).
