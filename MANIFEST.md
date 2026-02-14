# Manifesto Técnico — Projeto TaskForge

## 1. Propósito do Projeto

Este projeto existe para simular a evolução de um backend real ao longo do tempo.

Ele não busca começar perfeito.
Busca começar funcional e evoluir conforme surgem problemas reais de arquitetura, escala e manutenção.

O objetivo é demonstrar, de forma prática, como sistemas de software amadurecem no mundo real.

---

## 2. Filosofia de Engenharia

Este projeto segue alguns princípios centrais:

### Construir antes de abstrair

Começamos simples.
A complexidade só é introduzida quando um problema real exige.

### Arquitetura orientada a problemas

Nenhuma tecnologia é adotada por tendência.
Cada decisão arquitetural deve responder a uma dor concreta do sistema.

### Clareza acima de genialidade

Código deve ser legível e compreensível por novos contribuidores.
Soluções sofisticadas são aceitas apenas quando necessárias.

### Evolução contínua

Este sistema é intencionalmente vivo.
Ele mudará de forma, estrutura e arquitetura ao longo do tempo.

---

## 3. Objetivo Didático

O projeto existe para:

* demonstrar decisões de backend no mundo real
* mostrar trade-offs arquiteturais
* expor falhas comuns de sistemas em crescimento
* ensinar como resolver problemas progressivamente

Ele não é um template perfeito.
Ele é um laboratório de evolução de software.

---

## 4. Relação com a Comunidade

Contribuições são bem-vindas, desde que respeitem os princípios do projeto.

Todo Pull Request deve:

* explicar o problema que resolve
* justificar a decisão técnica
* manter o sistema compreensível
* incluir testes quando aplicável

O objetivo não é apenas melhorar o código, mas melhorar o entendimento coletivo sobre engenharia de backend.

---

## 5. Diretrizes Arquiteturais Iniciais

* O sistema começa como um monólito intencionalmente simples
* Separações arquiteturais surgem conforme o domínio cresce
* Microserviços só serão introduzidos quando houver necessidade real
* Observabilidade, filas e cache surgem como resposta a problemas concretos

---

## 6. Regra de Ouro do Projeto

Nenhuma decisão técnica deve ser tomada por moda.
Toda decisão deve responder a um problema observável do sistema.

---

## 7. Compromisso

Este projeto não promete perfeição.
Promete transparência na evolução, nas decisões e nos erros.

Porque sistemas reais não nascem ideais.
Eles se tornam robustos ao longo do tempo.

---
