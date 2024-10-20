![Localhost API - Logo](https://github.com/user-attachments/assets/5d04e4d3-64c1-4890-b756-604a49fe3311)


![Objetivo](https://github.com/user-attachments/assets/c4fca693-63f8-4329-a0e8-4b103d9ab544)

O objetivo da aplicação é desenvolver um dashboard interativo para centralizar e visualizar dados do processo de recrutamento e seleção de uma empresa. A plataforma permitirá uma análise em tempo real de métricas como número de candidatos, tempo médio de contratação e custos, gerando relatórios dinâmicos que apoiam decisões estratégicas. Além disso, os usuários poderão personalizar relatórios conforme suas necessidades, filtrando informações por critérios relevantes. A ferramenta visa otimizar o processo de recrutamento, identificando padrões e tendências para melhorar a eficiência e alocação de recursos.

<div id="requisitos">
    <img src="https://github.com/user-attachments/assets/7c923995-da65-4006-b748-71be1a5f5b51" alt="Requisitos">
</div>

✅ Requisito 1 - Dashboard para visualizar os indicadores </br>
✅ Requisito 2 - Importar os dados com excel </br>
✅ Requisito 3 - Login via e-mail e senha com segurança </br>
✅ Requisito 4 – Documentação da API </br>
✅ Requisito 5 - Filtrar e segmentar os dados por vaga </br>
✅ Requisito 6 - Monitorar os custos associados ao processo seletivo </br>
✅ Requisito 7 - Taxa de retenção de novos funcionários </br>
✅ Requisito 8 - Layout responsivo para acessar via celular </br>
✅ Requisito 9 - Alterar de forma dinâmica as permissões </br>
✅ Requisito 10 - Gráficos com previsão de tendências </br>
✅ Requisito 11 - Exportar em PDF e CSV dos dados no Dashboard </br>
✅ Requisito 12 - Ter uma aplicação confiável </br>
</br>

![PropostaDeSolucao](https://github.com/user-attachments/assets/5dc4a1e7-4e19-429a-91ce-7b824780c50f)

Nossa proposta envolve o desenvolvimento de um painel interativo que centraliza as principais informações do processo de recrutamento. Esse painel oferecerá insights valiosos e permitirá uma análise detalhada e customizada das fases de seleção. As principais entregas. <br/>
    •  Dashboard para visualizar os indicadores <br/>
    •  Importar os dados com excel <br/>
    •  Login via e-mail e senha com segurança <br/>
    •  Documentação da API <br/>
    •  Filtrar e segmentar os dados por vaga <br/>
    •  Monitorar os custos associados ao processo seletivo <br/>
    •  Taxa de retenção de novos funcionários <br/>
    •  Layout responsivo para acessar via celular <br/>
    •  Alterar de forma dinâmica as permissões <br/>
    •  Gráficos com previsão de tendências <br/>
    •  Exportar em PDF e CSV dos dados no Dashboard <br/>
Essa solução oferece uma visão clara e abrangente do processo seletivo, permitindo uma tomada de decisão estratégica, melhor alocação de recursos e agilidade operacional.

![Produto](https://github.com/user-attachments/assets/350e2bd9-b395-4581-a352-d723fa62e332)

**Sprint 1**
<details>
  
[Screencast from 2024-09-29 22-07-52.webm](https://github.com/user-attachments/assets/030b4637-d812-46d1-9c0b-a8343941f8b8)

</details>


![Backlog](https://github.com/user-attachments/assets/94656158-8e74-4cf6-a2fc-fd1e2f8a6808)

**Sprint 1**
<details>

| Prioridade | História                                                                                              | Jira          | Requisitos                |
|------------|-------------------------------------------------------------------------------------------------------|---------------|---------------------------|
| 1          | Como usuário de RH, para acessar o dashboard e visualizar pelo menos 3 indicadores:                   | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-1)  | [Requisito 1](#requisitos) |
|            | - Indicador com o número de candidatos por vagas                                                      |               |                           |
|            | - Um card com o tempo médio de contratação                                                            |               |                           |
|            | - Filtrar por período                                                                                 |               |                           |
| 2          | Funcionalidade de import dos dados (ETL).                                                             | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-2)  | [Requisito 2](#requisitos) |
| 3          | Como usuário de RH quero acessar a plataforma via login de e-mail e senha.                            | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-3)  | [Requisito 3](#requisitos) |

</details>

**Sprint 2**
<details>

| Prioridade | História                                                                                              | Jira          | Requisitos                |
|------------|-------------------------------------------------------------------------------------------------------|---------------|---------------------------|
| 1          | Como usuário de RH, quero filtrar e segmentar todos os dados por tipo de vaga, na tela de dashboard.  | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-4)  | [Requisito 5](#requisitos) |
| 2          | Preciso monitorar os custos associados ao processo seletivo.                                          | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-6)  | [Requisito 6](#requisitos) |
| 3          | No dashboard quero visualizar um card com a taxa de retenção de novos funcionários.                   | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-5)  | [Requisito 7](#requisitos) |
| 4          | Quero ter uma aplicação estável e confiável (DevOps).                                                | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-48)  | [Requisito 12](#requisitos) |
| 5          | Como usuário quero ter um layout responsivo para acessar via celular nas reuniões.                    | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-43) | [Requisito 8](#requisitos) |

</details>

**Sprint 3**
<details>

| Prioridade | História                                                                                          | Jira          | Requisitos                |
|------------|---------------------------------------------------------------------------------------------------|---------------|---------------------------|
| 1          | Precisa melhorar o import dos dados validando a integridade dos mesmos.                           | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-47)                 | [Requisito 2](#requisitos) |
| 2          | Quero analisar pelo menos duas tendências e padrões no processo de seleção, e conseguir filtrar por cargo         | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-10) | [Requisito 10](#requisitos) |
| 3          | Como usuário de RH, preciso liberar o acesso de acordo com o cargo e poder alterar a forma dinâmica as permissões | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-8)  | [Requisito 9](#requisitos) |
| 4          | Quero ter uma aplicação estável e confiável (DevOps).                                             | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-68)                 | [Requisito 12](#requisitos) |
| 5          | Como usuário preciso ter uma senha segura.                                                        | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-45)                 | [Requisito 3](#requisitos) |

</details>

**Sprint 4**
<details>

| Prioridade | História                                                                                          | Jira          | Requisitos                |
|------------|---------------------------------------------------------------------------------------------------|---------------|---------------------------|
| 1          | Quero ter a opção de exportar em PDF e CSV dos dados no Dashboard.                                | [Ver no Jira](https://localhost305.atlassian.net/browse/LOC-9)  | [Requisito 11](#requisitos) |

</details>


![Modelagem](https://github.com/user-attachments/assets/b74c1529-06d5-449f-a6d0-b7909d026f00)

<details>

![MER](https://github.com/Localhost-305/localhost-database/blob/main/MER/MER.png)

</details>


![Time](https://github.com/user-attachments/assets/a3fa4a08-00aa-4f95-9947-5e6453eade2a)

| Aluno             | Função       | GitHub       | LinkedIn       |
|-------------------|--------------|--------------|-----------------|
| Lucas Oliveira    | Product Owner| [GitHub](https://github.com/LucasOliveira321) | [LinkedIn](https://www.linkedin.com/in/lucas-augusto-oliveira/)                                                                           |
| Lukas Fernando    | Scrum Master | [GitHub](https://github.com/LukasFernando)    | [LinkedIn](#)                                                                                                                             |
| Danilo Verginio   | Developer    | [GitHub](https://github.com/Daniloel)         | [LinkedIn](https://www.linkedin.com/in/daniloverginio)                                                                                    |
| Davi Gusmão       | Developer    | [GitHub](https://github.com/Davign10)         | [LinkedIn](https://br.linkedin.com/in/dgusm%C3%A3o)                                                                                       |
| Gabriel D'Epiro   | Developer    | [GitHub](https://github.com/GabrielDepiro)    | [LinkedIn](https://www.linkedin.com/in/gabriel-depiro/)                                                                                   |
| Laroy Prado       | Developer    | [GitHub](https://github.com/laroyprado)       | [LinkedIn](https://br.linkedin.com/in/laroyprado)                                                                                         |
| Vitor Lima        | Developer    | [GitHub](https://github.com/VilRL)            | [LinkedIn](https://www.linkedin.com/in/vitor-lima-dev?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) |


![Tecnologias](https://github.com/user-attachments/assets/74af18c3-3b53-48cd-b0eb-c0141b473b91)

