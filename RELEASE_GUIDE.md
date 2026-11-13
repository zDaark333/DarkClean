# Publicação do DarkClean

## Distribuição atual

Este repositório é destinado a binários e documentação. O código-fonte próprio,
backups, ambientes de desenvolvimento, pesquisas e chaves privadas permanecem fora
dele. Os arquivos de fonte exigidos por componentes de terceiros conservam suas
licenças e não abrem o código próprio do aplicativo.

A 11.2.2 é uma prévia pública com atualização manual. Publique como prerelease,
com a tag `v11.2.2`, sem substituir o rascunho antigo da 11.0.0.

## Arquivos desta entrega

- `DarkClean-Setup-v11.2.2.exe`
- `SHA256SUMS.txt`
- `LEIA-ME.txt`
- `AVISOS-DE-TERCEIROS.txt`

Antes de publicar, confira a versão, os hashes, os avisos que acompanham a
instalação e as verificações do executável. O instalador deve ser enviado para
Releases, sem adicionar o diretório de código local ao repositório.

## Atualizador

Não reutilize a receita antiga de pacote gerenciado para esta distribuição.
O instalador atual usa `DarkCleanTeste`, enquanto o atualizador gerenciado espera
launcher, helper e diretórios de versão próprios. Um EXE anexado à Release não
habilita automaticamente esse mecanismo.

Uma futura entrega gerenciada exigirá preparação e validação próprias, incluindo
assinatura Ed25519, migração, manifesto, pacote compatível e recuperação. Nunca
publique chaves privadas ou senhas para tentar habilitá-la.
