# desafio-aws-dio

Cloud Solutions: Modernizando a Infraestrutura da Abstergo

Este projeto é um estudo de caso prático que simula a transição de uma empresa do modelo tradicional de infraestrutura local (on-premise) para a nuvem da Amazon Web Services (AWS). O foco é demonstrar como a tecnologia pode resolver problemas de negócio, otimizar custos e impulsionar o crescimento.

O cenário é de uma empresa fictícia, a Abstergo, uma distribuidora de produtos farmacêuticos que atua como hub B2B. A proposta foi elaborada para ser apresentada a um gestor financeiro, focando em retorno sobre o investimento (ROI) e valor estratégico.

O Desafio de Negócio
A Abstergo enfrenta desafios significativos com sua infraestrutura atual:

Processos Manuais: Pedidos e controle de estoque são ineficientes, gerando erros e atrasos.

Falta de Escalabilidade: A empresa não consegue lidar com picos de demanda, perdendo vendas e clientes.

Custos Operacionais Elevados: A manutenção de servidores físicos e a necessidade de compra de novo hardware consomem grande parte do orçamento.

Vulnerabilidade de Dados: A infraestrutura atual não garante a segurança dos dados sensíveis dos clientes, o que representa um risco financeiro e de reputação em um setor regulamentado.

A Solução Proposta
A proposta é migrar a infraestrutura de TI da Abstergo para a AWS. A arquitetura inicial será construída com serviços essenciais que abordam diretamente os desafios do negócio, garantindo uma solução escalável, segura e econômica.

Ferramentas e Serviços AWS Implementados
Para a solução, três serviços fundamentais da AWS foram selecionados, com foco na redução de custos e nos ganhos operacionais:

Amazon EC2 (Elastic Compute Cloud)
Propósito: Servidores virtuais na nuvem para hospedar a plataforma de e-commerce e os sistemas de processamento de pedidos da Abstergo.

Valor para o Negócio: Elimina a necessidade de comprar e manter servidores caros. A empresa paga apenas pelo tempo de uso, podendo ligar mais servidores automaticamente durante picos de demanda e desligá-los quando a demanda é baixa, evitando o gasto com capacidade ociosa.

Principal Ganho: Escalabilidade e Agilidade. A Abstergo se torna ágil para crescer e consegue processar um volume maior de pedidos sem gargalos, gerando mais receita.

Amazon RDS (Relational Database Service)
Propósito: Um serviço de banco de dados gerenciado para armazenar dados de clientes, pedidos e estoque de forma organizada e segura.

Valor para o Negócio: Reduz drasticamente os custos com mão de obra, pois automatiza tarefas complexas como backups e atualizações de segurança. Garante a alta disponibilidade do banco de dados, protegendo a empresa de interrupções que podem causar perdas financeiras.

Principal Ganho: Confiabilidade e Segurança. O banco de dados da Abstergo passa a ser robusto e protegido, garantindo que os dados críticos de negócio estejam sempre acessíveis.

Amazon S3 (Simple Storage Service)
Propósito: Um serviço de armazenamento de arquivos altamente durável e escalável, como um "disco rígido" ilimitado na nuvem.

Valor para o Negócio: Substitui servidores de armazenamento físicos, que são caros e têm capacidade limitada. Com o modelo de pagamento por uso, a Abstergo paga apenas pelo volume de dados armazenado, sendo ideal para guardar históricos de pedidos, relatórios financeiros e imagens de produtos.

Principal Ganho: Durabilidade e Conformidade. Garante a proteção dos dados contra perdas, o que é fundamental para a conformidade no setor farmacêutico.

Próximos Passos do Projeto
O projeto segue para a fase de detalhamento da arquitetura da solução e uma análise aprofundada de custo-benefício (ROI) para validar a proposta de investimento. A implementação será feita em fases, com um protótipo inicial para testar as funcionalidades principais antes de uma migração completa.
