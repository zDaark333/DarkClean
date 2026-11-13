# Confiança dos downloads e dos acessos

## Downloads e atualizações

Use somente a [publicação oficial atual](https://github.com/zDaark333/DarkClean/releases).
O instalador não tem assinatura digital de editor. O SHA-256 publicado permite
comparar o arquivo, mas não equivale a uma assinatura de editor.

O atualizador verifica a assinatura Ed25519 dos metadados com a chave pública
incorporada ao aplicativo. Confere tamanho e SHA-256 antes de permitir a instalação,
que exige confirmação. As chaves privadas permanecem fora dos arquivos distribuídos.

## Contas online

Somente o proprietário do painel cria usuários, redefine senhas, define limites
de computadores e bloqueia acessos. O painel administrativo exige a identidade
ChatGPT autorizada do proprietário; o instalador não contém credenciais administrativas.
Não há cadastro público.

O servidor armazena hashes scrypt das senhas com sal aleatório e segredo privado
separado. As solicitações têm limite de tentativas. A comunicação exige HTTPS
com validação do certificado e do nome do servidor.

O computador guarda apenas uma sessão cifrada pelo Windows DPAPI, vinculada ao
perfil do Windows. A senha não fica armazenada. O servidor guarda apenas o hash
do token de sessão. Um identificador aleatório do perfil distingue os computadores;
o login não utiliza números de série do hardware. O nome do computador é exibido
ao administrador para reconhecer o acesso.

A sessão exige confirmação online ao iniciar e a cada minuto. Bloquear a conta,
revogar sessões ou redefinir a senha invalida o acesso na próxima verificação.
Se a internet falhar, a interface pausa até confirmar o acesso novamente.
Operações já iniciadas terminam antes do encerramento seguro.

**Recuperar acesso** registra uma solicitação para o proprietário. A resposta não
confirma publicamente se um usuário existe. O proprietário entrega a nova senha
diretamente ao usuário. Não há envio automático de mensagens.

O controle de entrada não cifra os backups do aplicativo nem substitui a segurança
do Windows. Não envie senhas, tokens, arquivos de sessão, chaves ou dados pessoais
em relatos públicos. Retirar releases antigas não revoga executáveis já baixados.

## Relatos

Use Issues para falhas comuns sem dados pessoais. Para detalhes de segurança
exploráveis, procure um canal privado disponibilizado pelo
[mantenedor](https://github.com/zDaark333).
