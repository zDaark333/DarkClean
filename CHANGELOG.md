# Histórico do DarkClean

## 1.0.2

- Mantém o botão de verificação utilizável quando uma consulta é recusada porque
  outra operação de atualização está em andamento.
- Preserva a atualização já preparada quando a nova consulta não pode começar.
- Descarta instaladores antigos autenticados do cache após a versão correspondente
  estar instalada, sem remover downloads futuros nem arquivos desconhecidos.
- Adia a limpeza de um instalador ainda em uso pelo Windows e tenta novamente depois.

## 1.0.1

- Ativa a verificação ao abrir o aplicativo e periodicamente em segundo plano.
- Avisa sobre novas versões e pede confirmação para baixar e instalar.
- Autentica os metadados e confere a integridade do instalador.
- Padroniza aplicativo, executável, atalhos e instalador como DarkClean.
- Remove atalhos e o executável antigo durante a atualização.
- Preserva preferências, inicialização com o Windows e ferramentas NVIDIA.

## 1.0.0 — primeira versão pública

Marco inicial da numeração pública do DarkClean no GitHub.

- Limpeza, monitoramento de hardware e ferramentas de diagnóstico.
- Configurações de Windows, energia, rede e jogos.
- Ferramentas NVIDIA com perfil por jogo e restauração correspondente.
- Mitigações de CPU acessíveis na área de Otimização.
- Rolagem preservada entre páginas e atualizações das listas.
- DDU e NVCleanstall passam a abrir páginas oficiais para download; seus
  instaladores não são redistribuídos neste pacote.
- Inclui avisos e licenças de componentes de terceiros.
- Retira componentes gráficos não utilizados pela interface distribuída.
- Versão unificada no aplicativo, no relatório de suporte e no instalador.

## Próximas versões

Correções seguirão 1.0.1, 1.0.2 e seguintes. Conjuntos de novos recursos poderão
usar 1.1.0, mantendo um registro de mudanças para cada entrega.

## Limites desta distribuição

Desde a 1.0.1, a verificação é automática, com instalação somente após confirmação.
Quem está na 1.0.0 precisa instalar a 1.0.1 manualmente uma vez.
Os resultados de desempenho dependem do computador e das opções escolhidas.
