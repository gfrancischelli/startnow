# Implementation Bootcamp

--- 

## StartNow

+++

### START

Strategic Alignment and Rapid Transformation

+++ 


## Licença StartNow

**Requer uma licença adicional**. Se não comprar, o acesso é apenas durante
implantação + 30 dias após o Go-Live. Depois do prazo os registros vão travar
apenas read-only.

+++

### SAIF

- Disponível com a licença do PPM |

---

*Plan* -> *Discovery* -> *Prepare* -> *Deploy* -> *Operate* -> *Transform*

+++

![Image](./assets/methodology.png)

+++

**Plan**
- Kickoff
- Explicar ao cliente de acordo com o que foi acordado no contrato
- Começa a planear o projeto.

+++

**Discover**
- Mapeamento dos requerimentos como stories.

+++

**Prepare**
- Preparar o setup da instância, preparação do projeto
- LDAP(s) integration
- Common Data
- Scrum planning para as releases e sprints
- Security e Compliance

+++

**Deploy**
- Começa a implantar de fato o que foi mapeado
- Construir a funcionalidade definida no Scrum
- Project management
- Sprint planning, stand up reviews
- ACE report reviews

+++

**Operate**
- Testar o que foi feito, checklist
- Acceptance testing
- US Validation
- GO-Live

--- 

## O Que contêm

- Plugin Agile Development (SCRUM)
- Project Plan Templates |
- RIDAC (Risks, Issues, Decisions, Actions, Changes) |

+++

#### Como são organizadas as histórias

+++

### Product -> Release -> Sprint -> (Epic) -> Stories

**Exemplo**: Cliente quer ITSM, CMDB, RH.
- O que podemos fazer são workshops para incidentes, problemas, mudanças e isso fazem parte dos requerimentos de um produto (ITSM) |
- Uma release para incidente, problema, mudança, catálogo de serviço. |

+++

### RIDAC

Risk Issues Decisions Actions Changes

+++

Risk 

  - podem ou nao acontecer
  - impacto no escopo

+++

Issue

 - Já aconteceu ou está acontecendo
 - Identificar a correção

+++

### Scrum

Create and PPM -> Requirements Workshop Output (stories) -> Organize Srpint -> Scrum activities
-> Ready for testing and Go-Live

+++ 


**Project Management**
- EM
- Customer PM

+++

**Scrum**
- EM
- TCs
- Customer Process Owner
- Customer Product Owner

+++

**Risk**
- EM
- TC
- Some Customers

---

## Plan Stage Guidelines

- Setup do time
- Onde treinar os ssadmins
- Abordagem gerenciamento de instâncias, muito importante
- Configurar o StartNow.
- Como fazer reunião de kickoff

+++

### Atividades no Plan Stage

- Configurar o StartNow
- Setup release teams definir as equipes de implantação |
- Plano de projeto |
- Pré propular RIDAC |

+++

**DEPOIS DO KICKOFF**

- Review do plano de projeto
- Review do plano de treinamento |
- Review Onboarding plans |
- Muito importante obter compromisso do cliente para o projeto. Um cliente que |
  nao ajude durante a implantação é muito complicado. | 

---

### Quem pertence às equipes

+++

#### Da parte do Parceiro implementador

- Engagement Manager / Scrum Master
- Business Process Consultant (BPC) |
- Technical Consultant |
- Integration Consultant |
- Specialists |

+++

#### Da parte do cliente

- Project Manager
- Executive Sponsor
- Sysadmins
- Platform Owner
- Quality Assurance
- Product Owner e Process Owner

+++

Dependendo do contrato o cliente tem pelo menos 2 vagas gratuitas em
treinamentos. Costumam ser 2 pessoas no sysadmin.

No [servicenow.com/training](http://servicenow.com/training) é possível ver os treinamentos e certificações
disponíves.

--- 

#### Maneiras adicionais de engajamento
- Community user groups
- Product docs  |
- **Developer Site** |
- Partner Portal |
- ServiceNow training |
- Social Media |
- Youtube Channel |
- Servicenow Share |
- Application Showcase |
- Champions Community |

+++

#### Instance Provisioning

Dependendo da licença vai se ter 2 ou 3 instâncias.

+++

#### Clones

Pode ser feito de prod para test ou do backup de prod para dev.

+++

#### Update Set

Um update set é um grupo de customizações que pode ser movido de uma instância
para outra.

---

**Develop Solution** -> **Test* Solution** -> **Go-Live**

+++

##### Primeira Estratégia - Menos que Ideal

1. Clonar Dev para Teste
2. Clonar Test para Prod |
3. Clonar Prod de volta para Dev e Test para sincronizar as instâncias. |


##### Segunda Estratégia - Um pouco mais Ideal

1. Desenvolver em Prod antes do Go-Live
2. Após clonar para Dev e Test. |


##### Terceira Estratégia - Via US - Ideal

Começar a desenvolver em dev com Update Sets e move-los individualmente.

Utliizar o módulo de stories e numerar os cards para fazer o update set.

**Testes devem ser feitos em QA**

### StartNow Implementation Group - Local

Módulo StartNowGroup para adicionar todas as pessoas que **vão** trabalhar na
implementação. O grupo garante a role necessária para ter acesso à StartNow.

+++

#### Formulário da release
- Acesso aos produtos inclusos na release
- Sprints inclusos na release
- Stories inclusos na release
- Equipes incluido na release

---

### Prepare and Run Kickoff Meeting

Declaração clara e objetiva das expectativas e suposições.

#### O que deve ser mencionado ?

- Vender a empresa e objetivos
- Apresentar a filosofia da empresa sucintamente
- Falar sobre metodologia StartNow
- Rever como  o projeto será gerenciado
- Importante que o cliente se apresente

+++ 

#### Template de slides do kickoff

- **Falem da sua empresaa, porque estão aqui.**
- Agenda
 - O que vai ser dicutido
- Introdução
- Apresenta a nossa equipe ServiceNow
- Escopo
- Objetivos do workshop e sua importância
- Getting Started: possibilidades de como começar no ServiceNow (opcional)
  - TODO List -> conta da wiki, logar no user group etc
- Customer satisfaction program: um questionário sera enviado ao final da
  implementação para os clientes para definir o score do time de implementação
- **Apresentar metodologia StartNow**
  - Explicar o que acontece em cada um dos planos
  - O que ocorre em cada um das fases
- Project Plan
- SCRUM
  - Como é a dinâmica
  - Personagens envolvidos
  - Como scrum se encaixa no startnow
  - Hierarquia: release, produto , etc
- RIDAC
- Good Stories: explicar o que são, como fazer.
- Próximos passos
- Q&A
