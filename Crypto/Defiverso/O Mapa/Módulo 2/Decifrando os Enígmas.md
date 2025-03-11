## Tópicos

- Altcoins – 03:08
- Trilema das Blockchains – 16:48
- Camadas Blockchains – 20:38
- Tipos de camadas 2 – 28:07
- Camadas Blockchains – 44:14
- Blockchains Monolíticas e modulares 47:07
- Criptomoedas Vs Tokens – 54:00

## Links e materiais

- **Material Módulo 2:** [https://drive.google.com/file/d/1T86QsNNPfxhz3cg–Rm-RDmZyg61Jr5T/view?usp=sharing](https://drive.google.com/file/d/1T86QsNNPfxhz3cg--Rm-RDmZyg61Jr5T/view?usp=sharing)
- **Relatório Gás Ethereum:** [https://app.defiverso.com/relatorios/ethereum-o-que-e-taxa-de-gas-e-como-reduzir-seu-custo-de-transacao/](https://app.defiverso.com/relatorios/ethereum-o-que-e-taxa-de-gas-e-como-reduzir-seu-custo-de-transacao/)

- **Withepaper Ethereum:** [https://ethereum.org/en/whitepaper/](https://ethereum.org/en/whitepaper/)
- **Yellow Paper Ethereum:** [https://ethereum.github.io/yellowpaper/paper.pdf](https://ethereum.github.io/yellowpaper/paper.pdf)
- **Glossário Defiverso:** [https://sleet-interest-eda.notion.site/GLOSS-RIO-CRIPTO-DEFIVERSO-6d5844c6fa834422a40638266ecf44bc?pvs=4](https://sleet-interest-eda.notion.site/GLOSS-RIO-CRIPTO-DEFIVERSO-6d5844c6fa834422a40638266ecf44bc?pvs=4)

## Live Tira-Dúvidas

**Live gravada tira dúvidas:** [https://app.defiverso.com/lives/live-tira-duvidas-mod-2/](https://app.defiverso.com/lives/live-tira-duvidas-mod-2/)

## O que é e como funciona a taxa de gás?

As taxas de gás nada mais são do que um valor cobrado para utilizar a rede ao fazer uma transação ou uma interação na blockchain.

Cada rede terá sua própria forma de calcular esse serviço, que pode variar desde a quantidade de usuários que estão utilizando determinada rede no momento da transação até a complexidade da interação que você está fazendo, pois essa pode ocupar mais espaço de blocos que uma transação simples, acarretando num valor maior de taxa durante o processo.

**ETHEREUM (Taxa de Gás)**

Gás: No Ethereum, as taxas de transação são chamadas de “gás”. Cada operação na rede (como enviar tokens ou executar contratos inteligentes) requer uma quantidade específica de gás.

Preço do Gás: O preço do gás é medido em “gwei” (1 gwei = 0.000000001 ETH) e pode ser ajustado pelos usuários. Quanto maior o preço do gás oferecido, mais rápida a confirmação da transação.

Limite de Gás: O limite de gás é a quantidade máxima de gás que o usuário está disposto a gastar em uma transação.

EIP-1559: Essa foi uma atualização que aconteceu em Agosto de 2021 onde as taxas de gás incluem uma “base fee” ajustada dinamicamente, que é queimada, e uma “priority fee” (gorjeta) opcional que incentiva os validadores.

**BITCOIN (Taxas de Transação)**

Taxa por Byte: As taxas no Bitcoin são calculadas com base no tamanho da transação em bytes. Transações maiores (com mais entradas e saídas) custam mais.

Oferta e Demanda: As taxas são determinadas pela oferta e demanda na rede. Em períodos de alta demanda, os usuários podem oferecer taxas mais altas para que suas transações sejam priorizadas pelos mineradores.

Modelo de Leilão: Os mineradores escolhem as transações com as taxas mais altas para incluir nos blocos, maximizando suas recompensas.

**Solana (Taxa de Transação)**

Baixas Taxas Fixas: Solana é conhecida por suas baixas taxas de transação. As taxas são fixas e geralmente uma fração de um centavo.

Escalabilidade e Eficiência: Devido à alta capacidade de processamento e baixa latência, Solana consegue manter as taxas de transação extremamente baixas.

Queima de Taxas: Parte das taxas de transação é queimada, ajudando a manter o valor do token SOL ao reduzir a quantidade total em circulação.

Cada rede tem seu próprio método para calcular e aplicar taxas de transação: Ethereum utiliza um modelo de gás com preços ajustáveis e mecanismos para gerenciar a demanda, como a queima de uma parte das taxas; Bitcoin varia as taxas com base no tamanho da transação e na demanda da rede, utilizando um modelo de leilão; e Solana oferece taxas fixas e muito baixas devido à sua alta eficiência e escalabilidade, incluindo a queima de parte das taxas de transação.

## Explicação das 3 camadas da blockchain

As blockchains têm três camadas principais: a Camada de Execução, que processa transações e contratos inteligentes; a Camada de Disponibilidade de Dados, que garante que todos os dados necessários estejam acessíveis para validação; e a Camada de Consenso e Liquidação, que assegura que todos concordem com o estado da rede e registra transações permanentemente.

**1- CAMADA DE APLICAÇÃO OU EXECUÇÃO (Execution Layer)**

**Execução de Transações**: A camada de execução é responsável por processar e validar transações. Esta camada inclui contratos inteligentes, que são programas auto executáveis que executam automaticamente quando certas condições são atendidas.

**Máquinas Virtuais**: No caso do Ethereum, a Ethereum Virtual Machine (EVM) é um exemplo de ambiente de execução onde os contratos inteligentes são executados.

**Aplicações Descentralizadas (dApps)**: As dApps operam na camada de execução, interagindo com contratos inteligentes para fornecer serviços descentralizados.

**Exemplo:**

**Ethereum**: Utiliza a EVM para executar contratos inteligentes.

**Solana**: Executa transações de alta velocidade diretamente em sua camada de execução.

**2- CAMADA DE CONSENSO E SEGURANÇA OU LIQUIDAÇÃO (Consensus and Settlement Layer)**

**Consenso**: Esta camada é responsável por garantir que todos os nós da rede concordem sobre o estado atual do blockchain. Algoritmos de consenso, como Proof of Work (PoW) e Proof of Stake (PoS), são usados para validar blocos e manter a segurança da rede.

**Segurança**: Fornece a segurança fundamental da rede, protegendo contra ataques como a dupla gastação e ataques Sybil.

**Liquidação**: A camada de liquidação finaliza e registra permanentemente as transações no blockchain. Ela garante a imutabilidade e a irreversibilidade das transações após serem confirmadas.

**Exemplo:**

**Bitcoin**: Utiliza PoW para consenso e liquidação.

**Ethereum 2.0**: Utiliza PoS para consenso e liquidação

**3- PROTOCOLO OU CAMADA DE DISPONIBILIDADE DE DADOS (Data Availability Layer)**

**Armazenamento de Dados**: Esta camada assegura que os dados necessários para a execução das transações estão disponíveis para todos os nós na rede. Ela garante que os dados são acessíveis e verificáveis por qualquer participante da rede.

**Compartilhamento de Dados**: Facilita o compartilhamento eficiente de dados entre os nós para garantir que todos tenham acesso aos mesmos dados de transação.

**Importância:**

**Integridade dos Dados:** Sem a disponibilidade de dados, seria impossível verificar a execução correta das transações.

**Escalabilidade:** A camada de disponibilidade de dados pode ser projetada para suportar grandes volumes de dados sem comprometer a performance da rede.

**Exemplo:**

**Rollups no Ethereum:** Mecanismos como Optimistic Rollups ou ZK-Rollups dependem da camada de disponibilidade de dados para armazenar e compartilhar dados de transações compactadas.

## É seguro holdar tokens em Layers 2?

