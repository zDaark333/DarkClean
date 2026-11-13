# DarkClean

Aplicativo para Windows com limpeza, monitoramento de hardware, diagnóstico e
configurações de desempenho. Este repositório distribui instaladores e documentação;
o código-fonte próprio do DarkClean permanece fechado.

## Download atual

**1.1.0 — tema roxo, logo DC e acesso online com sessão lembrada.**

- [Baixar para Windows de 64 bits](https://github.com/zDaark333/DarkClean/releases/download/v1.1.0/DarkClean-Setup-v1.1.0.exe)
- [Publicação atual e arquivos de verificação](https://github.com/zDaark333/DarkClean/releases/tag/v1.1.0)
- [Alterações](CHANGELOG.md)

Somente a publicação atual fica disponível para download. Esta revisão substitui
os arquivos da própria 1.1.0. **Quem já instalou a 1.1.0 anterior deve baixar e
reinstalar manualmente**, pois a numeração permanece igual.

## Instalação e entrada

1. Use Windows 10 versão 1809 ou posterior, ou Windows 11, de 64 bits.
2. Feche o DarkClean, baixe o instalador acima e execute-o como administrador.
3. Entre com o usuário e a senha fornecidos pelo administrador do DarkClean.

O aplicativo preserva as preferências da instalação anterior. Não há cadastro
público: somente o proprietário cria os acessos. A tela de entrada oferece
**usuário, senha, Entrar e Recuperar acesso**.

Depois da primeira entrada, a sessão é lembrada neste perfil do Windows. A senha
não fica salva. Ao abrir novamente, o aplicativo confirma a sessão online sem
pedir a senha. A sessão expira após 90 dias sem uso, ao sair da conta, quando o
administrador redefine a senha ou revoga o acesso.

É necessária internet para entrar e confirmar o acesso durante o uso. Se a conexão
falhar, o aplicativo pausa e permite tentar novamente; a sessão continua salva.
Um bloqueio remoto é aplicado na próxima verificação, feita a cada minuto.

**Recuperar acesso** envia uma solicitação ao administrador, que define uma nova
senha e a entrega diretamente ao usuário. Não há envio automático por e-mail.
Não publique suas credenciais em Issues ou mensagens públicas.

## Recursos

- Limpeza com escolha de categorias e confirmação das ações; correção da lixeira.
- Informações de hardware, sensores e diagnóstico.
- Configurações de Windows, energia, rede e jogos.
- Full NVIDIA por jogo, backups de restauração e Profile Inspector.
- Mitigações de CPU na área de Otimização.
- Tema roxo, logo com D e C, cartões renovados e rolagem que preserva a posição.
- DDU portátil e abertura de uma cópia pessoal verificada do NVCleanstall.

A disponibilidade depende do Windows, do hardware e dos drivers. Consulte o efeito
e a restauração de cada opção antes de aplicar. Não há promessa de ganho universal
de FPS ou redução de latência.

## Atualizações

Mantenha **Verificar atualizações automaticamente** marcado em Configurações.
O DarkClean consulta novas versões ao abrir e periodicamente enquanto estiver
rodando. Baixar e instalar exigem confirmação. Também é possível usar
**Verificar atualizações**. A verificação considera apenas versões superiores;
por isso a substituição desta 1.1.0 exige reinstalação manual.

Instaladores antigos autenticados são removidos do cache quando podem ser
descartados com segurança. Downloads futuros e arquivos desconhecidos são preservados.
Retirar publicações antigas não bloqueia cópias já baixadas anteriormente.

## Ferramentas e distribuição

O DDU portátil **18.1.6.1**, de Wagnardsoft / Ghislain Harvey (Wagnard), acompanha
o pacote com licença MIT e créditos. **Abrir DDU** verifica a integridade e abre
a ferramenta em sua própria janela, sem remover drivers automaticamente.

O NVCleanstall não é redistribuído. Baixe a versão **1.19.0** pelo
[site oficial da TechPowerUp](https://www.techpowerup.com/download/techpowerup-nvcleanstall/)
e use **Selecionar arquivo** em Ferramentas NVIDIA. O DarkClean verifica a cópia
original antes de abri-la. O backup de perfis não restaura drivers removidos.

O instalador não possui assinatura digital de editor. Compare seu hash com
`SHA256SUMS.txt`. As atualizações pelo aplicativo exigem metadados assinados
e conferência de tamanho e SHA-256 antes de permitir a instalação.

Os componentes de terceiros conservam suas licenças na pasta `AVISOS-TERCEIROS`.
Consulte o [resumo dos avisos](AVISOS-DE-TERCEIROS.txt) e [SECURITY.md](SECURITY.md).

## Problemas e sugestões

Abra uma [Issue](https://github.com/zDaark333/DarkClean/issues) com a versão,
o Windows e os passos para reproduzir. Remova dados pessoais de capturas e relatórios.
