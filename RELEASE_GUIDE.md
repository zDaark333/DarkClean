# Publicação do DarkClean

## Distribuição atual

Este repositório é destinado a binários e documentação. O código-fonte próprio,
backups, ambientes de desenvolvimento, pesquisas e chaves privadas permanecem fora
dele. Os arquivos de fonte exigidos por componentes de terceiros conservam suas
licenças e não abrem o código próprio do aplicativo.

A numeração pública começou em 1.0.0. A versão atual é 1.1.0. As alterações devem
ser acumuladas e testadas localmente, mantendo a versão de trabalho até o fechamento.
Cada nova entrega e mudança de versão exigem autorização explícita do mantenedor;
a autorização de uma publicação anterior não vale para a próxima.

## Arquivos desta entrega

- `DarkClean-Setup-v1.1.0.exe`
- `SHA256SUMS.txt`
- `LEIA-ME.txt`
- `AVISOS-DE-TERCEIROS.txt`
- `installer-update.json`
- `installer-update.sig`

Antes de publicar, confira a versão, os hashes, os avisos que acompanham a
instalação e as verificações do executável. O instalador deve ser enviado para
Releases, sem adicionar o diretório de código local ao repositório.

O DDU 18.1.6.1 acompanha sua licença MIT e atribuição. O NVCleanstall pessoal,
as senhas, sessões e registros de autenticação não podem integrar os arquivos
enviados. Confira novamente essas exclusões antes de cada publicação.

## Atualizador

Cada publicação deve incluir o instalador e os metadados assinados pela mesma
chave de publicação incorporada ao aplicativo. Sem os metadados válidos, a versão
não será oferecida pelo atualizador. Os hashes de todos os assets ficam em
`SHA256SUMS.txt`.

O cliente ignora rascunhos e versões iguais ou inferiores à instalada. A instalação
exige confirmação do usuário e usa o instalador normal do Windows. Nunca publique
a chave privada ou altere-a entre versões sem planejar a migração de confiança.

## Revisão da mesma publicação 1.1.0

Esta substituição foi autorizada pelo mantenedor. Mantém a numeração e a publicação
existente; troca apenas os seis arquivos aprovados e a documentação. A versão
anterior é preservada em backup privado. As demais releases ficam como rascunho,
sem downloads públicos. A alteração não bloqueia cópias antigas já instaladas.

Não distribua código do servidor, dados de contas, arquivos DPAPI, credenciais
administrativas, segredos do serviço ou a chave de assinatura. O aplicativo inclui
apenas o endereço público do serviço e certificados públicos de confiança.
O mesmo número de versão exige reinstalação manual de quem já usa a 1.1.0 anterior.
