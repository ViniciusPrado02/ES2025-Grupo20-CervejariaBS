# ES2025-Grupo20-CervejariaBS
Especificação de Sistema de Controle para a Cervejaria BeboSim - Projeto da Disciplina de Engenharia de Software.

# Cervejaria BeboSim  
### Sistema de Controle de Produção e Vendas  
**Disciplina:** Engenharia de Software – 2025  
**Professor:** Radamés Pereira  
**Grupo:** ES2025–GrupoX  

---

## 1. Introdução

### 1.1 Propósito  
Este projeto tem como objetivo desenvolver um **Sistema de Controle de Produção e Vendas** para a **Cervejaria BeboSim**, aplicando **Princípios Ágeis** e **Gerência de Configuração de Software (GCS)**.  
O sistema visa otimizar processos de fabricação, logística, vendas e campanhas publicitárias, garantindo rastreabilidade e flexibilidade para futuras expansões.

### 1.2 Escopo  
O sistema será desenvolvido pela equipe **SF – Software do Futuro**, com entregas incrementais seguindo a metodologia **Scrum**.  
A solução deve permitir o **cadastro, controle e monitoramento** de produtos, unidades de produção, embalagens, equipes de vendas, clientes, pedidos e campanhas.

### 1.3 Definições, Acrônimos e Abreviações  
- **PO:** Product Owner  
- **GCS:** Gerência de Configuração de Software  
- **SCV:** Sistema de Controle de Versão (ex: Git)  
- **CI/CD:** Integração e Entrega Contínuas  
- **README.md:** Documento de introdução e diretrizes do projeto  

---

## 2. Descrição Geral

### 2.1 Perspectiva do Produto  
O sistema centraliza a gestão da Cervejaria BeboSim em um ambiente digital, integrando áreas de **produção, estoque, vendas e marketing**.  
Ele será implementado como uma aplicação web modular, com autenticação, dashboards e relatórios.

### 2.2 Funções Principais do Sistema  
- **Gestão de Produtos:** Nome, fórmula de produção, estoque, preço e comissão.  
- **Gestão de Unidades de Produção:** Fábricas com dados cadastrais e produtos associados.  
- **Gestão de Embalagens:** Nome, descrição, custo e volume, associáveis a múltiplos produtos.  
- **Gestão de Equipes de Vendas:** Times regionais com vendedores e gerentes.  
- **Gestão de Clientes:** Pessoas jurídicas com CNPJ e contato.  
- **Gestão de Pedidos:** Registro de pedidos com produtos, quantidades e responsáveis.  
- **Gestão de Campanhas:** Controle de campanhas, investimentos e retorno sobre vendas.  

### 2.3 Características dos Usuários  
Usuários principais:  
- **Gerentes de Produção e Vendas**  
- **Vendedores**  
- **Administradores do Sistema**  
- **Equipe de Marketing**  

Cada perfil possui permissões e telas específicas.  

### 2.4 Restrições  
- O sistema deverá ser **web responsivo**, acessível via navegador.  
- O banco de dados deve garantir **integridade referencial**.  
- O controle de versões será feito via **GitHub público**.  
- O desenvolvimento seguirá **Sprints quinzenais**.  

---

## 3. Requisitos Específicos  
Os **requisitos detalhados** e **diagramas do sistema** serão documentados na **Wiki** do repositório GitHub, incluindo:  
- Requisitos funcionais e não funcionais;  
- Casos de uso e diagramas UML;  
- Modelo lógico do banco de dados;  
- Regras de negócio e fluxos de processos.  

---

## 4. Arquitetura do Sistema  
A descrição completa da arquitetura (camadas, tecnologias, padrões e integrações) também estará disponível na **Wiki**, contendo:  
- Diagrama de arquitetura;  
- Estrutura de diretórios do código-fonte;  
- Descrição dos módulos principais;  
- Padrões adotados (MVC, REST, etc.).  

---

## 5. Gerência de Configuração de Software (GCS)

### 5.1 Itens de Configuração  
- Código-fonte do sistema  
- Documentos de requisitos  
- Diagramas e scripts de banco de dados  
- Planos de teste  
- Arquivo README.md e documentação técnica  

### 5.2 Sistema de Controle de Versão  
Será utilizado o **Git** como SCV, com o repositório hospedado no **GitHub**.  
Principais comandos utilizados:
```bash
git clone <URL>
git add .
git commit -m "mensagem descritiva"
git push origin main
git pull
