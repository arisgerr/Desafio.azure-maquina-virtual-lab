## <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"> DESAFIO: Laboratório: Criação de Máquina Virtual no Microsoft Azure 🚀

Este repositório foi criado como parte do desafio proposto na plataforma [DIO](https://www.dio.me/) para documentar os conhecimentos adquiridos sobre computação em nuvem, com foco na criação e configuração de uma máquina virtual utilizando o Microsoft Azure.

## Autora ✍️

- [Valéria Baptista](https://github.com/valeriafarias)

## 🧠 Objetivos de Aprendizagem

- Aplicar conceitos práticos da computação em nuvem;
- Compreender e utilizar o Azure Portal;
- Criar uma máquina virtual com alta disponibilidade;
- Entender SLAs, elasticidade e escalabilidade;
- Documentar o processo técnico de forma clara.

---

## ☁️ Benefícios da Computação em Nuvem

- **Alta disponibilidade:** Garantia de tempo de atividade com base em SLAs (Service Level Agreement);
- **Escalabilidade:** Capacidade de aumentar recursos conforme o crescimento da demanda;
- **Elasticidade:** Redução ou ampliação automática de recursos conforme a necessidade;
- **Segurança:** Recursos nativos de proteção de dados e autenticação;
- **Redução de CapEx:** Sem necessidade de investimento inicial em infraestrutura física.

---

## 🛠️ Etapas do Laboratório

### 1. Acesso ao Portal Azure
Acesse o portal: [https://portal.azure.com](https://portal.azure.com)

### 2. Criação da Máquina Virtual
- Recurso: Máquina Virtual (VM)
- Sistema Operacional: Windows Server 2019
- Tamanho: Standard_B1s (ajustável conforme uso)
- Região: Brasil Sul
- Grupo de Recursos: `lab-vm-grupo`
- Nome da VM: `vm-desafio-dio`
- Usuário admin e senha configurados
- Porta RDP habilitada (porta 3389)

### 3. Configurações de Alta Disponibilidade
- Zona de disponibilidade: ativada
- Tipo de replicação: armazenamento com redundância geográfica (GRS)
- SLA: de 99,9% até 99,999%, dependendo da configuração (quanto mais “noves”, menor o tempo de inatividade).

---

### 🔹 SLA (Service Level Agreement)

O SLA representa o **nível de garantia de disponibilidade** de um serviço. No Azure, diferentes serviços oferecem SLAs diferentes, por exemplo:

| SLA       | Inatividade por ano | Por mês     | Por semana  |
|-----------|----------------------|-------------|-------------|
| 99%       | 3,65 dias            | 7,2 horas   | 1,68 horas  |
| 99.9%     | 8,76 horas           | 43,2 minutos| 10,1 minutos|
| 99.99%    | 52,56 minutos        | 4,32 minutos| 1 minuto    |
| 99.999%   | 5,26 minutos         | 25,9 segundos| 6 segundos |

Quanto **mais “9s”**, menor o tempo aceitável de inatividade.

---

## 📌 Conclusão

A nuvem pública como o Microsoft Azure oferece uma infraestrutura robusta, segura e flexível, ideal para ambientes que exigem disponibilidade, desempenho e escalabilidade. Este laboratório demonstrou na prática como iniciar essa jornada e preparar-se para desafios maiores na área de tecnologia em nuvem.

---

## 🔗 Referências

- [Documentação oficial da Microsoft Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [Criação de máquinas virtuais no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [Guia de Markdown do GitHub](https://guides.github.com/features/mastering-markdown/)


### 🔗 Desafio proposto por [Digital Innovation One - DIO](https://www.dio.me/)

- [Ariana Eger](https://github.com/arisgerr)
