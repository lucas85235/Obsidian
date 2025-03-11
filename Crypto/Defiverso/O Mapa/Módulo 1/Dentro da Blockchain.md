## Tópicos

- Início – 00:00
- O dinheiro – 4:58
- O nascimento do Bitcoin – 15:21
- Criptografia – 22:07
- Blockchain – 26:58
- Função de Hash – 31:16
- Algoritmo de Consenso – 37:33
- Prova de Aposta – 48:45
- Transações – 53:13

## Links e materiais

- **Material Módulo 1:** [https://drive.google.com/file/d/1-2obvtDWl_7Qfa3SOk1Wj5kMe5C5DZ8K/view?usp=sharing](https://drive.google.com/file/d/1-2obvtDWl_7Qfa3SOk1Wj5kMe5C5DZ8K/view?usp=sharing)
- **Whitepaper Bitcoin em Portugûes:** [https://bitcoin.org/files/bitcoin-paper/bitcoin_pt.pdf?fbclid=IwAR0PlUR4ecdiIx0IUBR-793QLYoLVyQuq4Jz9dNLkIczT4vn_9CO2P5reb0](https://bitcoin.org/files/bitcoin-paper/bitcoin_pt.pdf?fbclid=IwAR0PlUR4ecdiIx0IUBR-793QLYoLVyQuq4Jz9dNLkIczT4vn_9CO2P5reb0)

- **Demo da Blockchain:** [https://andersbrownworth.com/blockchain/hash](https://andersbrownworth.com/blockchain/hash)

## Live Tira-Dúvidas

- **Live tira duvidas gravada:** [](https://app.defiverso.com/lives/live-tira-duvidas-mod-1/)[https://app.defiverso.com/lives/boas-vindas-modulo-1-tira-duvidas/](https://app.defiverso.com/lives/live-tira-duvidas-mod-1/)

# Como funciona a mineração de Bitcoin? Quem não consegue minerar o bloco recebe alguma coisa?

A mineração de bitcoin é o processo pelo qual novos bitcoins são criadas e as transações são verificadas e adicionadas a blockchain.

Os mineradores utilizam poder computacional para resolver complexos problemas matemáticos que garantem a segurança e a integridade da rede. Quando um minerador resolve um desses problemas, ele adiciona um novo bloco de transações ao blockchain e é recompensado com uma quantidade pré-determinada de bitcoins, conhecida como “recompensa de bloco”. Além disso, o minerador também recebe as taxas de transação incluídas nesse bloco, pagas pelos usuários que desejam que suas transações sejam processadas.

Aqueles que não conseguem minerar um bloco específico não recebem a recompensa de bloco. No entanto, alguns mineradores podem participam de pools de mineração, onde combinam seu poder computacional com outros mineradores. Quando o pool resolve um problema e minera um bloco, a recompensa é dividida entre todos os participantes com base na contribuição de cada um. Dessa forma, mesmo que um minerador individual não consiga resolver um bloco sozinho, ele ainda pode receber uma parte proporcional das recompensas ao contribuir para o esforço coletivo do pool.

## Qual a diferença de um minerador e um nó validador da rede?

Na rede do Bitcoin, mineradores e nós validadores desempenham diferentes papéis, embora complementares, vamos listar aqui as diferenças entre esses dois importantes personagens da rede.

**Mineradores**

A principal função desempenhada pelos mineradores na rede do Bitcoin é a adição de novos blocos à blockchain.

Para desempenhar o papel descrito acima, os mineradores competem entre si para resolver um complexo problema matemático através de tentativa e erro.

A recompensa que esses mineradores recebem nesta competição são bitcoins novinhos em folha (recompensa do bloco) e as taxas das transações presentes naquele bloco.

O processo de mineração requer a utilização de um hardware mais específico para essa finalidade com o objetivo de otimizar esse processo descrito acima.

**Nós Validadores**

A principal função dos nós validadores é garantir a integridade e a segurança da blockchain, verificando as transações e os blocos que estão circulando na rede.

Os nós validam as transações e os blocos recebidos, assegurando que todos seguem as regras impostas na rede do Bitcoin (como o não gasto duplo, validade das assinaturas, etc.).

Os nós também são os responsáveis pela propagação das transações e dos blocos verificados para o restante dos nós da rede.

Um nó validador, diferente de uma máquina para mineração, pode ter um hardware bem menos especializado (como verão no módulo 12), embora ainda seja necessário uma quantidade considerável de armazenamento e banda.

Nós não recebem recompensas da rede, eles operam para contribuir com a descentralização e segurança da rede.

Dito isso, é importante pontuar que ambos são elementos cruciais para o

bom funcionamento da rede do Bitcoin.

## Como nós e mineradores interagem na rede?

A interação entre nós validadores e mineradores acontecem das seguintes formas:

**Mineração e propagação**: Quando um minerador encontra uma solução válida para o bloco proposto, ele propaga o mesmo para o restante da rede, ao receber essa informação os nós validadores verificam a validade desta.

**Confirmação de blocos**: Se os nós confirmam que o bloco em questão é válido (contém transações legítimas e segue as regras da rede), eles o aceitam e adicionam uma cópia do mesmo em sua cópia local da blockchain.

**Consenso**: ****O consenso consenso na rede Bitcoin só é alcançado através da colaboração entre mineradores (criadores de blocos) e nós (que verificam e aceitam blocos)

## Qual a vantagem de se rodar um nó validador da rede?

Executar um nó validador em uma rede blockchain oferece diversas vantagens tanto para o indivíduo quanto para a rede como um todo. Vamos explorar alguns dos principais benefícios:

1. **Contribuição para a Segurança e Descentralização:**
    
    **Validação de Transações:** Validadores desempenham um papel crucial na verificação da validade das transações na rede.
    
    **Resistência à Censura:** A natureza distribuída da rede impede que qualquer entidade única controle ou censure transações.
    
    **Incentivos Econômicos:** Validadores são recompensados com criptomoedas por sua contribuição para a segurança da rede.
    
2. **Recompensas Financeiras:**
    
    Os validadores geralmente precisam fazer staking de uma quantia específica da criptomoeda nativa da rede. Em troca, eles recebem recompensas por bloco processado com sucesso e essas recompensas podem variar dependendo da atividade da rede e da taxa de inflação.
    
3. **Autonomia e Privacidade:**
    
    Executando seu próprio nó você não depende de serviços de terceiros para acessar a rede blockchain, e também tem mais controle sobre suas próprias chaves e dados.
    
4. **Apoiando o Crescimento da Rede:**
    
    Fortalecimento da Infraestrutura validadores contribuem para a robustez e resiliência da rede, contribuindo para o desenvolvimento da tecnologia blockchain.

## O que é slashing e como ocorre? Posso tomar slashing se eu colocar fundos em stake de algum protocolo?

O slashing um processo nas blockchains que utilizam o consenso Proof-of-Stake (PoS) para punir validadores que se comportam mal ou violam as regras. Esses validadores são responsáveis por verificar transações e manter a segurança da rede.

O slashing pode ocorrer por diversos motivos, incluindo:

1. **Offline:** Se um validador ficar offline por um período prolongado, ele pode ser punido
2. **Ataques:** Se um validador tentar atacar a rede ou validar transações inválidas, ele pode ser punido
3. **Negligência:** Se um validador não cumprir suas responsabilidades de forma adequada, ele pode ser punido.

**Slashing e Stake em Protocolos**

**Ao fazer stake em um protocolo, você não está atuando diretamente como um validador, mas sim “contratando” os serviços de um validador.** Se você colocar fundos em stake em um protocolo PoS, você corre o risco de perder seus fundos se o validador que você escolheu for punido por slashing. No entanto, o risco é geralmente baixo se você escolher um validador confiável e bem estabelecido.

É importante estar ciente dessa possibilidade e entender as regras de cada protocolo antes de participar do staking

Quando um validador é punido por slashing, ele geralmente perde parte ou todo o stake de criptomoedas que ele depositou como garantia para se tornar um validador. Isso serve como um incentivo para que os validadores não se comportem mal e ajuda a manter a segurança da rede.

## UTXO Explicado

Para explicar essa questão vamos para um exemplo prático de como funcionam os UTXOS, em um cenário hipotético onde uma pessoa receba como pagamento mensal 1 BTC pelo seu trabalho, ao completar um ano de trabalho essa pessoa teria 12 BTC em sua carteira, porém seriam vários “pedaços” de bitcoin, como demonstrado na imagem abaixo.

![](https://defiverso.nyc3.digitaloceanspaces.com/wp-content/uploads/2024/07/UTXO-1-1024x1024.png)

Como dito no módulo, pode-se imaginar UTXOs como moedas em um cofre, ou cédulas em uma carteira, sendo assim, trazendo o exemplo acima para esse cenário, se ao invés de 1 BTC a pessoa recebesse 1 nota de R$100 por mês trabalhado, ao final de 12 meses ela teria 12 notas de R$100 em sua carteira.

Agora vamos para outra questão, suponhamos que a pessoa acima tenha compra um carro do nosso querido @victor_alfa por 6.5 BTC, nessa transação, a rede selecionaria a quantidade de UTXOs necessária para alcançar esse valor como inputs (entradas) da transação, como é demonstrado na imagem abaixo.

![](https://defiverso.nyc3.digitaloceanspaces.com/wp-content/uploads/2024/11/UTXO-2-1024x1024-2.png)

Analisando a imagem acima temos que a rede utilizou 7 UTXOs de 1 BTC cada como inputs (entrada) da transação, e os outputs (saída) foram 3 UTXOS, o primeiro deles de 6.5 BTC, que é o que vai cair na conta do Victor pelo carro, o segundo UTXO é referente as taxas de rede pagas na transação e o terceiro e último seria o equivalente ao troco em uma transação nossa do dia a dia, sendo assim 0.49 BTC.