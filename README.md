# DarkClean

Aplicativo para Windows com limpeza, monitoramento de hardware, diagnóstico e
configurações de desempenho. Este repositório distribui instaladores e documentação;
o código-fonte próprio do DarkClean não é publicado aqui.

## Download

**11.2.2 — prévia pública, com instalação e atualização manuais.**

- [Baixar o instalador para Windows de 64 bits](https://github.com/zDaark333/DarkClean-Updates/releases/download/v11.2.2/DarkClean-Setup-v11.2.2.exe)
- [Notas da versão e arquivos de verificação](https://github.com/zDaark333/DarkClean-Updates/releases/tag/v11.2.2)
- [Histórico das versões](CHANGELOG.md)

## Instalação

1. Use Windows 10 versão 1809 ou posterior, ou Windows 11, de 64 bits.
2. Feche o DarkClean antes de instalar ou atualizar.
3. Baixe o instalador pela Release acima e execute-o. A instalação requer
   permissão de administrador.
4. Escolha os atalhos e os componentes opcionais apresentados pelo instalador.

Esta prévia mantém a pasta de instalação `DarkCleanTeste` e pode aparecer como
**DarkClean (teste)** nos atalhos. O atualizador dentro do aplicativo está
desabilitado nesta distribuição; novas versões são instaladas manualmente.

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

Os componentes de terceiros mantêm suas próprias licenças e avisos, acompanhados
na pasta `AVISOS-TERCEIROS` da instalação. Fontes de terceiros distribuídos
sob suas respectivas licenças não são o código-fonte próprio do DarkClean.
Consulte também o [resumo dos avisos de terceiros](AVISOS-DE-TERCEIROS.txt).

## Problemas e sugestões

Abra uma [Issue](https://github.com/zDaark333/DarkClean-Updates/issues) com a versão,
o Windows utilizado e os passos para reproduzir o problema. Remova dados pessoais
de capturas e relatórios. Para informações sobre confiança dos downloads, consulte
[SECURITY.md](SECURITY.md).
