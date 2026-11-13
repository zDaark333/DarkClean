# DarkClean

Aplicativo para Windows com limpeza, monitoramento de hardware, diagnóstico e
configurações de desempenho. Este repositório distribui instaladores e documentação;
o código-fonte próprio do DarkClean não é publicado aqui.

## Download

**1.0.2 — aviso de atualizações e limpeza do cache de instaladores antigos.**

- [Baixar o instalador para Windows de 64 bits](https://github.com/zDaark333/DarkClean/releases/download/v1.0.2/DarkClean-Setup-v1.0.2.exe)
- [Notas da versão e arquivos de verificação](https://github.com/zDaark333/DarkClean/releases/tag/v1.0.2)
- [Histórico das versões](CHANGELOG.md)

A sequência pública começou em 1.0.0 e continua com 1.0.1, 1.0.2 e seguintes.

## Instalação

1. Use Windows 10 versão 1809 ou posterior, ou Windows 11, de 64 bits.
2. Feche o DarkClean antes de instalar ou atualizar.
3. Baixe o instalador pela Release acima e execute-o. A instalação requer
   permissão de administrador.
4. Escolha os atalhos e os componentes opcionais apresentados pelo instalador.

O aplicativo, o executável e os atalhos usam o nome **DarkClean**. O instalador
reconhece a instalação anterior e mantém as preferências do usuário.

## Atualizações

Nas Configurações, mantenha **Verificar atualizações automaticamente** marcado.
O DarkClean consulta novas versões ao abrir e periodicamente enquanto estiver
rodando. Ao encontrar uma versão nova, pergunta se você deseja baixar; depois
de conferir o arquivo, pede confirmação antes de abrir o instalador. Nada é
instalado silenciosamente. Você também pode usar **Verificar atualizações**.

**Quem usa a 1.0.0 precisa instalar a versão mais recente manualmente uma vez**, pois a versão
anterior não tinha a verificação ativa. Depois disso, os próximos avisos aparecem
no próprio aplicativo. O DarkClean precisa estar aberto ou rodando na bandeja.

Instaladores de versões já instaladas são removidos do cache local quando podem
ser descartados com segurança. Downloads de versões futuras e arquivos
desconhecidos são preservados.

## Recursos

- Limpeza com escolha de categorias e revisão das ações.
- Informações de hardware, sensores e diagnóstico.
- Configurações de Windows, energia, rede e jogos.
- Ferramentas NVIDIA, incluindo perfil por jogo e restauração correspondente.
- Mitigações de CPU disponíveis na área de Otimização.

A disponibilidade depende do Windows, do hardware e dos drivers. Consulte o efeito
e a restauração de cada opção antes de aplicar. Não há promessa de ganho universal
de FPS ou redução de latência.

## Distribuição

O pacote público não inclui os instaladores DDU e NVCleanstall. Seus botões abrem
as páginas oficiais para que o usuário escolha o download diretamente do fornecedor.
As ferramentas NVIDIA próprias do DarkClean e o Profile Inspector continuam no pacote.

O instalador não possui assinatura digital de editor. O arquivo `SHA256SUMS.txt`
da Release permite conferir a integridade do download. Ele não substitui uma
assinatura digital nem deve ser usado como instrução para desativar proteções do Windows.

As atualizações pelo aplicativo também exigem metadados assinados pelo publicador
e conferência de tamanho e SHA-256 antes de permitir a instalação.

Os componentes de terceiros mantêm suas próprias licenças e avisos, acompanhados
na pasta `AVISOS-TERCEIROS` da instalação. Fontes de terceiros distribuídos
sob suas respectivas licenças não são o código-fonte próprio do DarkClean.
Consulte também o [resumo dos avisos de terceiros](AVISOS-DE-TERCEIROS.txt).

## Problemas e sugestões

Abra uma [Issue](https://github.com/zDaark333/DarkClean/issues) com a versão,
o Windows utilizado e os passos para reproduzir o problema. Remova dados pessoais
de capturas e relatórios. Para informações sobre confiança dos downloads, consulte
[SECURITY.md](SECURITY.md).
