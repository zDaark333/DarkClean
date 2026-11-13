# DarkClean

Aplicativo para Windows com limpeza, monitoramento de hardware, diagnóstico e
configurações de desempenho. Este repositório distribui instaladores e documentação;
o código-fonte próprio do DarkClean permanece fechado.

## Download atual

**1.1.1 — NVCleanstall incluído, visual roxo mais consistente e cabeçalho ajustado.**

- [Baixar para Windows de 64 bits](https://github.com/zDaark333/DarkClean/releases/download/v1.1.1/DarkClean-Setup-v1.1.1.exe)
- [Publicação atual e verificação dos arquivos](https://github.com/zDaark333/DarkClean/releases/tag/v1.1.1)
- [Alterações](CHANGELOG.md)

Somente a publicação atual fica disponível para download público. As fontes próprias
e os dados de autenticação não são publicados.

## Instalação e entrada

1. Use Windows 10 versão 1809 ou posterior, ou Windows 11, de 64 bits.
2. Feche o DarkClean, baixe o instalador e execute-o como administrador.
3. Entre com o usuário e a senha fornecidos pelo administrador do DarkClean.

O instalador reconhece a instalação anterior e preserva as preferências.
Somente o proprietário cria os acessos. A tela oferece usuário, senha, Entrar e
Recuperar acesso; não há cadastro público.

Depois da primeira entrada, a sessão é lembrada neste perfil do Windows, sem
salvar a senha. O aplicativo confirma o acesso online ao iniciar e a cada minuto.
Se a conexão falhar, a interface pausa e permite reconectar mantendo a sessão.
O bloqueio remoto passa a valer na próxima verificação. A sessão expira após
90 dias sem uso, ao sair da conta, redefinir a senha ou revogar o acesso.

Recuperar acesso envia uma solicitação ao administrador, que define e entrega
a nova senha diretamente. Não há envio automático por e-mail.

## Ferramentas NVIDIA

**NVCleanstall 1.19.0 — TechPowerUp:** agora acompanha o instalador. Use
**Abrir NVCleanstall**, sem precisar baixar nem selecionar outro arquivo.
O DarkClean verifica a integridade e abre a ferramenta original em sua própria
janela. O programa foi preservado sem modificações, com créditos e procedência.
O publicador do DarkClean confirmou possuir autorização da TechPowerUp para redistribuí-lo.
[Página oficial](https://www.techpowerup.com/download/techpowerup-nvcleanstall/).

**DDU portátil 18.1.6.1 — Wagnardsoft / Ghislain Harvey (Wagnard):** incluso com
licença MIT e créditos. Abrir DDU verifica os arquivos e abre a ferramenta original.

Abrir essas ferramentas não inicia remoção ou instalação de drivers automaticamente.
Você escolhe as operações nas próprias ferramentas. O backup de perfis NVIDIA do
DarkClean não restaura drivers removidos.

O Full NVIDIA por jogo, seus backups de restauração e o NVIDIA Profile Inspector
continuam disponíveis.

## Recursos preservados

- Limpeza com categorias e confirmação; consulta da lixeira corrigida.
- Informações de hardware, sensores e diagnóstico.
- Ajustes de Windows, energia, rede e jogos.
- Mitigações de CPU acessíveis na área de Otimização.
- Tema roxo, logo DC, cartões e controles com cores mais consistentes.
- Cabeçalho mais legível em notebooks e posição de rolagem preservada.
- Contas online do proprietário, sessão lembrada e bloqueio remoto.

A disponibilidade depende do Windows, do hardware e dos drivers. Leia o efeito e
a restauração de cada ajuste. Não há promessa de ganho universal de desempenho.

## Atualizações

Quem usa a 1.1.0 pode receber a 1.1.1 pelo aplicativo. Mantenha
**Verificar atualizações automaticamente** marcado em Configurações, ou use
**Verificar atualizações**. O DarkClean precisa estar aberto e conectado.
O download e a instalação exigem confirmação. O atualizador confere metadados
assinados, tamanho e SHA-256 antes de abrir o instalador.

O instalador não possui assinatura digital de editor. Compare os arquivos com
`SHA256SUMS.txt`. As licenças e atribuições dos componentes acompanham a instalação
em `AVISOS-TERCEIROS`. Consulte [SECURITY.md](SECURITY.md) e os
[avisos de terceiros](AVISOS-DE-TERCEIROS.txt).

Ocultar publicações antigas não desativa cópias já baixadas.

## Problemas e sugestões

Abra uma [Issue](https://github.com/zDaark333/DarkClean/issues) com a versão, o
Windows e os passos para reproduzir. Remova senhas, tokens e dados pessoais.
