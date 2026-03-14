# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 14/03/2026

Empresa: Abstergo Industries

Responsável: Ryan Henrique Alves Bezerra


---

# Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Ryan Henrique Alves Bezerra**.

O objetivo do projeto foi selecionar e implementar **três serviços da Amazon Web Services (AWS)** com a finalidade de promover **redução de custos operacionais imediatos**, além de melhorar a escalabilidade, segurança e disponibilidade da infraestrutura de dados da empresa.

A proposta consiste na migração da infraestrutura de banco de dados atualmente hospedada em servidores locais para a nuvem da AWS, utilizando serviços gerenciados que diminuem custos com manutenção de hardware, energia e suporte técnico.

---

# Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em **3 etapas**, cada uma com objetivos específicos relacionados à migração e otimização da infraestrutura de dados da empresa.

---

# Etapa 1

* **Nome da ferramenta:** AWS Database Migration Service (DMS)

* **Foco da ferramenta:**
  Migração segura e eficiente de bancos de dados para a infraestrutura da AWS.

* **Descrição de caso de uso:**
  A Abstergo Industries possui bancos de dados hospedados em servidores locais, o que gera custos elevados de manutenção e limita a escalabilidade da infraestrutura.

Para realizar a migração desses dados para a nuvem com segurança e baixo impacto nas operações da empresa, será utilizado o **AWS Database Migration Service (DMS)**.

Esse serviço permite migrar bancos de dados para a AWS com **mínimo tempo de indisponibilidade**, além de possibilitar **replicação contínua de dados**, garantindo a integridade das informações durante todo o processo de migração.

---

# Etapa 2

* **Nome da ferramenta:** Amazon RDS (Relational Database Service)

* **Foco da ferramenta:**
  Gerenciamento automatizado de bancos de dados relacionais na nuvem.

* **Descrição de caso de uso:**
  Após a migração dos dados, a Abstergo Industries utilizará o **Amazon RDS** para hospedar e gerenciar seus bancos de dados na AWS.

O serviço oferece diversos recursos automatizados, como:

* backups automáticos
* atualizações de segurança
* monitoramento da infraestrutura
* escalabilidade sob demanda

Com isso, a empresa reduz custos operacionais relacionados à administração de servidores e pode focar no desenvolvimento de suas aplicações e serviços.

---

# Etapa 3

* **Nome da ferramenta:** Amazon S3 (Simple Storage Service)

* **Foco da ferramenta:**
  Armazenamento escalável e de baixo custo para arquivos e backups.

* **Descrição de caso de uso:**
  Para armazenamento de arquivos corporativos, registros históricos e backups de banco de dados, será implementado o **Amazon S3**.

O serviço oferece **alta durabilidade e disponibilidade**, além de permitir a utilização de diferentes classes de armazenamento, como **S3 Standard**, **S3 Infrequent Access** e **S3 Glacier**, que ajudam a reduzir custos ao armazenar dados menos acessados em camadas mais econômicas.

Isso permite que a Abstergo Industries mantenha grandes volumes de dados de forma segura e com menor custo de armazenamento.

---

# Conclusão

A implementação das ferramentas **AWS Database Migration Service (DMS)**, **Amazon RDS** e **Amazon S3** na empresa **Abstergo Industries** tem como objetivo principal reduzir custos operacionais e modernizar a infraestrutura de dados da organização.

Esses serviços permitem:

* redução de custos com infraestrutura física
* maior escalabilidade dos sistemas
* maior segurança e disponibilidade de dados
* automação de processos de gerenciamento de banco de dados
* armazenamento eficiente de arquivos e backups

Com a adoção dessas soluções, espera-se um aumento significativo na eficiência operacional da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação de novos serviços da AWS que possam otimizar ainda mais os processos internos.

---

# Anexos

## Anexo A – Documentação Oficial dos Serviços AWS

As seguintes documentações oficiais da Amazon Web Services foram utilizadas como referência para o desenvolvimento deste projeto:

* Amazon S3
  https://docs.aws.amazon.com/s3/

* Amazon RDS
  https://docs.aws.amazon.com/rds/

* AWS Database Migration Service (DMS)
  https://docs.aws.amazon.com/dms/

Assinatura do Responsável pelo Projeto:

Ryan Henrique Alves Bezerra
