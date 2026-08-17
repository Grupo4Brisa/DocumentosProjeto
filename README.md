# ACIST-SL — Documentação do Projeto

Sistema de cadastro de associados da ACIST São Leopoldo, desenvolvido pelo **Grupo 4** como projeto de estágio (Unisinos / BRISA).

Este repositório reúne a documentação central do projeto. O código-fonte está dividido em dois repositórios separados (frontend e backend).

## Repositórios do projeto

| Repositório | Descrição | Link |
|---|---|---|
| **Backend** | API em NestJS + TypeORM + PostgreSQL | https://github.com/Grupo4Brisa/ACIST-SL-Backend |
| **Frontend** | Interface em React + TypeScript + Vite | https://github.com/Grupo4Brisa/ACIST-SL-Frontend |

Cada repositório tem seu próprio `README.md` com instruções completas de instalação, configuração de variáveis de ambiente e deploy.

## Aplicação em produção

| Ambiente | URL |
|---|---|
| Frontend | https://acist-sl-frontend.vercel.app |
| Backend (API) | https://acist-sl-backend.onrender.com |

## Sobre o projeto

O sistema digitaliza o processo de associação de novas empresas à ACIST São Leopoldo, cobrindo desde o cadastro inicial (landing page), pagamento da mensalidade via PIX, preenchimento completo dos dados da empresa, upload de documentos, aceite do termo de adesão, até a aprovação final por um colaborador da ACIST.

O projeto é **parametrizável**: a mesma base de código atende duas versões diferentes, alternando apenas variáveis de ambiente (sem alterar código):
- **Versão com login do associado** — usada pela ACIST São Leopoldo.
- **Versão sem login (acesso por link/token)** — usada na apresentação/demonstração para a Unisinos.

Mais detalhes sobre essas versões estão nos READMEs de cada repositório.

## Documentação técnica

- [x] Apresentações para banca — apresentações
- [x] Código-fonte do backend — [link acima](#repositórios-do-projeto)
- [x] Código-fonte do frontend — [link acima](#repositórios-do-projeto)
- [x] Instruções de instalação — README de cada repositório

## Equipe — Grupo 4

- Deyvid Richard de Azevedo
- Gabriela de Abreu Lima
- Giovanna Sehn Tomasi
- Richard de Avila Rodrigues
- Vitor Silva da Costa

## Orientação e Contatos

- **Contato da empresa:** Marco Prauchner
- **Orientadora:** Izabel Cristina da Rosa dos Santos
- **Coordenador:** Maurício de Santos Ferreira

## Instituições

- **ACIST São Leopoldo** 
- **Unisinos** 
- **BRISA** 
