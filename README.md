# DarkClean

Aplicativo para Windows com limpeza, monitoramento de hardware, diagnóstico e
configurações de desempenho. Este repositório distribui instaladores e documentação;
o código-fonte próprio do DarkClean não é publicado aqui.

## Download

**1.1.0 — conta local, nova interface, logo renovado e correção da lixeira.**

- [Baixar o instalador para Windows de 64 bits](https://github.com/zDaark333/DarkClean/releases/download/v1.1.0/DarkClean-Setup-v1.1.0.exe)
- [Notas da versão e arquivos de verificação](https://github.com/zDaark333/DarkClean/releases/tag/v1.1.0)
- [Histórico das versões](CHANGELOG.md)

A sequência pública começou em 1.0.0. Esta atualização de recursos avança para 1.1.0.

## Instalação

1. Use Windows 10 versão 1809 ou posterior, ou Windows 11, de 64 bits.
2. Feche o DarkClean antes de instalar ou atualizar.
3. Baixe o instalador pela Release acima e execute-o. A instalação requer
   permissão de administrador.
4. Escolha os atalhos e os componentes opcionais apresentados pelo instalador.

O aplicativo, o executável e os atalhos usam o nome **DarkClean**. O instalador
reconhece a instalação anterior e mantém as preferências do usuário.

## Conta local

No primeiro acesso, crie seu usuário e uma senha de pelo menos 10 caracteres.
Guarde o código de recuperação exibido: ele permite redefinir a senha sem internet.
Nos próximos acessos, entre com essa conta. A troca de senha fica em Configurações.

A conta pertence ao perfil atual do Windows e não sincroniza entre computadores.
Não é uma conta Microsoft ou uma assinatura online. O monitoramento e a consulta
de atualizações começam depois de entrar no aplicativo.

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
- Conta local com cadastro, entrada, troca de senha e recuperação offline.
- Nova identidade visual, cartões renovados e barras de rolagem mais fáceis de usar.

A disponibilidade depende do Windows, do hardware e dos drivers. Consulte o efeito
e a restauração de cada opção antes de aplicar. Não há promessa de ganho universal
de FPS ou redução de latência.

## Distribuição

O DDU portátil **18.1.6.1**, de Wagnardsoft / Ghislain Harvey (Wagnard), acompanha
o pacote com sua licença MIT e créditos. **Abrir DDU** verifica a integridade e
abre a ferramenta em sua própria janela, sem iniciar uma remoção automaticamente.

O NVCleanstall não é redistribuído no instalador. Baixe a versão **1.19.0** pelo
[site oficial da TechPowerUp](https://www.techpowerup.com/download/techpowerup-nvcleanstall/)
e use **Selecionar arquivo** na página Ferramentas NVIDIA. O DarkClean verifica
a cópia original antes de abri-la. As operações de drivers são escolhidas nas
próprias ferramentas. O backup de perfis do DarkClean não restaura drivers removidos.

As funções NVIDIA próprias do DarkClean e o Profile Inspector continuam no pacote.

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
