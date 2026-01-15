# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 25/01/2026

**Empresa:** Abstergo Industries  
**Responsável:** gpinheir0

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por gpinheir0. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1
- **Nome da ferramenta:** Amazon EC2 Auto Scaling  
- **Foco da ferramenta:**  Migração inicial - computação sob demanda e escalabilidade horizontal
- **Descrição de caso de uso:** Iniciar o processo de adoção de nuvem focando em flexibilização da capacidade computacional, utilizando o EC2 Auto Scaling para ajustar automaticamente a quantidade de instâncias EC2 de acordo com a demanda do negócio e padrões de consumo observados. O principal benefício é evitar o custo associados A infraestruturas superdimensionadas, com servidores ociosos, redundâncias desnecessárias ou recursos provisionados para cenários de uso pouco frequentes. 

### Etapa 2
- **Nome da ferramenta:** Amazon Simple Queue Service (SQS)
- **Foco da ferramenta:**  Evolução da migração – desacoplamento de sistemas locais e processamento assíncrono
- **Descrição de caso de uso:**  Evoluir a arquitetura inicial para um modelo mais resiliente e eficiente em custo, utilizando o Amazon SQS para desacoplar os sistemas envolvidos nos processos de redistribuição. A fila de mensagens permite absorver variações de carga, processar requisições de forma assíncrona e reduzir falhas em cascata entre sistemas integrados. O principal benefício é diminuir o custo operacional e o risco, evitando a necessidade de superdimensionar recursos computacionais para lidar com picos momentâneos de demanda.

### Etapa 3
- **Nome da ferramenta:** AWS Lambda
- **Foco da ferramenta:** Conclusão da migração – computação orientada a eventos e pagamento por uso
- **Descrição de caso de uso:** Atingir um estágio mais maduro da adoção de nuvem ao implementar computação sem servidor com AWS Lambda, executando código somente em resposta a eventos específicos do negócio, como recebimento de pedidos, validações ou integrações pontuais. Essa abordagem elimina a necessidade de provisionar e manter servidores para tarefas intermitentes, permitindo que a empresa pague apenas pelo tempo de execução efetivo, otimizando ainda mais os custos e aumentando a eficiência operacional.

## Conclusão

A implementação de ferramentas na empresa *Abstergo Industries* tem como resultados esperados a otimização dos custos operacionais, a continuidade dos processos e escalabilidade, permitindo atender com agilidade ao crescimento do negócio, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- N/A.

---

**Assinatura do Responsável pelo Projeto:**  
gpinheir0
