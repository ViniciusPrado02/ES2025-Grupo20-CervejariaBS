1. Definição dos Papéis do Grupo (Scrum)
Nome: Anderson


Cargo/papel: Product Owner (PO) 


Responsabilidade: Ser o "Você" mencionado no exercício. É responsável por definir os itens do Product Backlog (como as 5 funcionalidades prioritárias) , organizá-los por prioridade e garantir que o time entregue o máximo de valor para a Cervejaria BeboSim.




Nome: Vinicius

Cargo/papel: Scrum Master

Responsabilidade: Garantir que o grupo siga a metodologia ágil (Scrum). Facilita as reuniões (como o planejamento do Sprint ) e remove quaisquer impedimentos que o Time de Desenvolvimento possa ter.

Nome: Igor

Cargo/papel: Time de Desenvolvimento

Responsabilidade: Analisar, projetar, codificar e testar os itens do backlog. Por exemplo, implementar o cadastro de produtos ou o registro de pedidos.


Nome: Vinicius

Cargo/papel: Time de Desenvolvimento


Responsabilidade: Colaborar com os outros membros do time para entregar um incremento funcional do software ao final de cada Sprint, como o "Sistema de Controle de Versão" (SCV).

Nome: Igor 

Cargo/papel: Time de Desenvolvimento (Especialista em GCS/Qualidade)

Responsabilidade: Focar nos aspectos de qualidade e configuração, gerenciando os "Itens de Configuração" e garantindo que o controle de versão no GitHub seja mantido corretamente.

2. Liste 5 itens iniciais do Product Backlog
Aqui estão 5 funcionalidades iniciais (itens do Product Backlog) baseadas nos requisitos do sistema :


Gestão de Produtos: Permitir o cadastro dos produtos líquidos (cerveja, guaraná, etc.), armazenando nome, quantidade em estoque, preço, comissão e fórmula de produção.


Gestão de Clientes: Permitir o cadastro de clientes (apenas Pessoas Jurídicas), armazenando razão social, CNPJ, endereço, telefone e pessoa de contato.


Gestão de Pedidos de Venda: Permitir que o vendedor emita e registre pedidos de venda, armazenando número, data, vendedor responsável, cliente e os produtos/quantidades vendidos.


Gestão de Unidades de Produção: Permitir o cadastro das fábricas, armazenando nome, endereço, CNPJ e os produtos que ela pode fabricar.


Gestão de Campanhas Publicitárias: Permitir o controle das campanhas, armazenando nome, datas, produtos participantes, preços promocionais e garoto-propaganda.

3. Organize-os em uma ordem de prioridade
Abaixo está a lista anterior, organizada por ordem de prioridade (do mais alto para o mais baixo), para entregar valor funcional o mais rápido possível.

Gestão de Produtos:

Prioridade: 1 (Altíssima)

Justificativa: É o item central do sistema. Sem produtos cadastrados , nenhuma venda ou controle de produção  pode ocorrer.



Gestão de Clientes:

Prioridade: 2 (Alta)


Justificativa: É um requisito essencial para a funcionalidade de vendas, já que todo pedido precisa estar associado a um cliente.


Gestão de Pedidos de Venda:

Prioridade: 3 (Alta)

Justificativa: Esta é a funcionalidade de venda principal. Ela depende diretamente dos itens 1 (Produtos) e 2 (Clientes) para existir.

Gestão de Unidades de Produção:

Prioridade: 4 (Média)

Justificativa: Importante para o controle de produção e para dar contexto ao estoque (mencionado no item 1), mas a venda (item 3) pode ser registrada antes da gestão de fábrica estar 100% implementada.

Gestão de Campanhas Publicitárias:

Prioridade: 5 (Média-Baixa)


Justificativa: Embora importante, é uma funcionalidade de marketing  que complementa as vendas, mas não é um bloqueio para que a venda principal (item 3) ocorra.

4. Proponha uma duração para o primeiro Sprint e justifique sua escolha.
Duração Proposta: 2 semanas (quinzenal).

Justificativa: A escolha de duas semanas é baseada diretamente na restrição de projeto definida no seu documento de especificação (ES2025-Grupo20-CervejariaBS). A seção 2.4 afirma explicitamente: "O desenvolvimento seguirá Sprints quinzenais.".

Essa duração é ideal pois:

Permite um ciclo rápido de planejamento, execução e entrega.

Garante "entregas incrementais", permitindo que a equipe receba feedback do cliente (PO/Professor) em curtos intervalos.

É tempo suficiente para o "ES2025–Grupo 20" desenvolver uma funcionalidade completa e testada, como a "Gestão de Produtos".

5. Descreva como você aplicaria os princípios ágeis no decorrer desse Sprint.
Abaixo está como os princípios ágeis seriam aplicados no primeiro Sprint de duas semanas focado, por exemplo, em entregar a "Gestão de Produtos".

Entregas Frequentes: Alinhado com a "Sprint quinzenal" e o objetivo de "entregas incrementais", ao final das duas semanas, o time não entregará apenas código, mas sim um módulo funcional. Por exemplo, o módulo de "Gestão de Produtos"  pronto, permitindo que um usuário (como o Gerente de Produção) cadastre, edite e liste os produtos da cervejaria.

Colaboração com o Cliente: No exercício, "Você é o Product Owner" (PO). Você atua como o representante direto do cliente (o "gerente-geral da Cervejaria BeboSim" ). A colaboração será diária: o time de desenvolvimento terá acesso direto a você (PO) para tirar dúvidas sobre os requisitos, como "O 'preço normal de venda' pode ser zero?" ou "Como a 'fórmula de produção'  deve ser armazenada?".



Feedback: Ao final do Sprint quinzenal, o time realizará a Sprint Review. Nesta reunião, eles apresentarão o módulo de "Gestão de Produtos" funcionando. Você (PO) e outros stakeholders (como o "Professor: Radamés Pereira") irão interagir com o software e fornecer feedback imediato, validando se os requisitos  foram atendidos.

Adaptação a Mudanças: Suponha que, durante a Sprint Review, o feedback mostre que o controle de "preços promocionais"  (do módulo de Campanhas) é mais urgente do que a "Gestão de Unidades de Produção". Como PO, você usará esse feedback para se adaptar: você irá re-priorizar o Product Backlog antes do próximo Sprint começar, movendo a funcionalidade de "Gestão de Campanhas" para o topo da lista, garantindo que o time trabalhe no item de maior valor a seguir.
