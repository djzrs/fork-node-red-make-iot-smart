# Node-RED Make IoT Smart

## 🌐 Idiomas

[![English](https://img.shields.io/badge/lang-English-blue.svg)](README.md) [![中文](https://img.shields.io/badge/lang-中文-red.svg)](README_ZH.md) [![Deutsch](https://img.shields.io/badge/lang-Deutsch-green.svg)](README_DE.md) [![Español](https://img.shields.io/badge/lang-Español-orange.svg)](README_ES.md) [![Français](https://img.shields.io/badge/lang-Français-purple.svg)](README_FR.md) [![日本語](https://img.shields.io/badge/lang-日本語-yellow.svg)](README_JA.md) [![한국어](https://img.shields.io/badge/lang-한국어-pink.svg)](README_KO.md) [![Português](https://img.shields.io/badge/lang-Português-cyan.svg)](README_PT.md) [![Русский](https://img.shields.io/badge/lang-Русский-brown.svg)](README_RU.md) [![繁體中文](https://img.shields.io/badge/lang-繁體中文-lightblue.svg)](README_TW.md)


---

Uma extensão de assistente de IA projetada especificamente para Node-RED, tornando o desenvolvimento IoT mais inteligente e eficiente.
[![npm version](https://badge.fury.io/js/@jhe.zheng%2Fnode-red-make-iot-smart.svg)](https://badge.fury.io/js/@jhe.zheng%2Fnode-red-make-iot-smart)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node-RED](https://img.shields.io/badge/Node--RED-2.0%2B-red)](https://nodered.org/)
## Visão Geral

O Node-RED Make IoT Smart é um agente de IA abrangente projetado especificamente para desenvolvimento Node-RED. Ele melhora a experiência de desenvolvimento IoT fornecendo suporte inteligente de código, otimização automatizada de fluxo e recursos de depuração inteligente. Esta extensão atualmente suporta 6 cenários principais: aprendizado, solução, integração, desenvolvimento, configuração e gerenciamento.

## Recursos

### 🤖 Assistente de IA

- **Sugestões Inteligentes de Código**: Recomendações de código com reconhecimento de contexto para fluxos Node-RED.
- **Análise Inteligente de Fluxo**: Analisa fluxos e fornece sugestões de otimização.
- **Interface de Linguagem Natural**: Interaja com o ambiente Node-RED usando comandos de linguagem natural.
- **Suporte Multilíngue**: Suporta chinês, inglês, japonês, coreano, etc. Adapta-se automaticamente às mudanças nas configurações de idioma do Node-RED.
- **Suporte Multi-Provedor**: Baseado no framework LangChain.js, suporta modelos de IA como OpenAI, Anthropic, Google, DeepSeek, etc.
- **Gerenciamento Inteligente de Memória**: Sistema de memória de curto e longo prazo baseado em SQLite, suporta armazenamento de histórico de conversas, configurações do usuário e padrões de fluxo.
- **Prompts Baseados em Cenários**: Gerenciamento de prompts baseado em cenários através de configuração JSON, suporta injeção dinâmica de parâmetros.
- **Integração de Ferramentas MCP**: Suporta chamadas de ferramentas do Model Context Protocol (MCP) para estender as capacidades do assistente de IA.


### 🔧 Ferramentas de Desenvolvimento

- **Análise de Código em Tempo Real**: Análise contínua de fluxos Node-RED.
- **Gerenciamento de Configuração**: Configuração centralizada de API para vários provedores de IA.
- **Barra Lateral Interativa**: Painel dedicado do assistente de IA integrado ao editor Node-RED.
- **Editor JSON**: Editor integrado de arquivos de configuração com destaque de sintaxe.
- **Integração de Ferramentas MCP**: Suporta chamadas de ferramentas do Model Context Protocol (MCP) para estender as capacidades do assistente de IA.
- **Gerenciamento de Ferramentas LangChain**: Framework unificado de gerenciamento de ferramentas, suporta ferramentas integradas e ferramentas MCP.
- **Suporte Baseado em Cenários**: Suporte personalizado para 7 cenários principais:
  - **Aprendizado**: Explica nós e conceitos, fornece fluxos de exemplo.
  - **Solução**: Fornece várias soluções IoT incluindo JSON de fluxo e guias de instalação de nós.
  - **Integração**: Suporta integração de protocolos (como MQTT, Modbus) e software.
  - **Desenvolvimento**: Otimiza fluxos existentes e código de nós de função.
  - **Configuração**: Orienta mudanças na configuração do Node-RED (como `settings.js`).
  - **Gerenciamento**: Suporta acesso remoto, integração Git e implantação em lote.

### 🚀 Recursos Futuros

- **Depuração Remota**: Depuração remota assistida por IA de fluxos Node-RED.
- **Gerenciamento de Equipe**: Desenvolvimento colaborativo com recursos de gerenciamento de equipe.
- **Análise Avançada**: Insights profundos sobre desempenho de sistemas IoT.
- **Implantação Inteligente**: Estratégias de implantação de aplicações IoT orientadas por IA.

## Instalação

### Instalar via npm

```bash
npm install @djzrs/node-red-iot-agent
```

### Instalar via Gerenciador de Paleta do Node-RED

1. Abra o editor Node-RED.
2. Vá para **Menu → Gerenciar Paleta**.
3. Procure por `@djzrs/node-red-iot-agent`.
4. Clique em **Instalar**.
5. Reinicie o Node-RED após a instalação.
6. Após a instalação, uma nova aba **Assistente de IA** aparecerá na barra lateral do Node-RED.
7. Clique no botão **Configurações** para configurar seu provedor de IA.
8. Escolha entre os provedores suportados:
   - **DeepSeek**: Opção econômica com fortes capacidades de codificação.
   - **OpenAI**: Modelos GPT líderes da indústria.
   - **Anthropic**: Capacidades avançadas de raciocínio através dos modelos Claude.
9. Insira sua chave de API e selecione o modelo apropriado.
10. Após a configuração, você pode começar a usar o assistente de IA. Note que após salvar as configurações, o NodeRED criará automaticamente um nó de configuração. O NodeRED mostrará as mudanças no fluxo e você só precisa clicar em mesclar.
11. Comece a interagir com o assistente de IA!

## Início Rápido
### Digite "Analisar nó atual"
<img src="https://github.com/djzrs/fork-node-red-make-iot-smart/raw/main/public/current-node.gif" width="800" height="450" alt="Animação de demonstração" />


### Digite "Criar fluxo de exemplo"
<img src="https://github.com/djzrs/fork-node-red-make-iot-smart/raw/main/public/create-flow.gif" width="800" height="450" alt="Animação de demonstração" />

### Digite "Verificação de saúde"
<img src="https://github.com/djzrs/fork-node-red-make-iot-smart/raw/main/public/health-check.gif" width="800" height="450" alt="Animação de demonstração" />

## Configuração

### Configuração de Depuração LangSmith (Opcional)

Você pode configurar o suporte LangSmith para melhor depuração e monitoramento de execuções LangChain:

1. Copie o arquivo `.env.example` para `.env`:
   ```bash
   cp .env.example .env
   ```

2. Edite o arquivo `.env` para inserir sua configuração LangSmith:
   ```env
   LANGCHAIN_TRACING_V2=true
   LANGCHAIN_API_KEY=your_langsmith_api_key_here
   LANGCHAIN_PROJECT=your_project_name
   ```

3. Reinicie o Node-RED para aplicar a configuração.

4. Acesse [LangSmith](https://smith.langchain.com/) para ver rastreamento detalhado de execução e informações de depuração.

**Nota**: A configuração LangSmith é opcional e não afeta a funcionalidade principal.

## Uso

### Interface de Chat Básica

- Abra a aba **Assistente de IA** na barra lateral.
- Digite suas perguntas ou instruções em linguagem natural.
- Receba respostas inteligentes com sugestões de código e explicações.

### Seleção de Cenário

- Selecione um cenário (aprendizado, solução, integração, desenvolvimento, configuração, gerenciamento) no menu suspenso da barra lateral.
- A IA adaptará suas respostas com base no cenário selecionado e fornecerá ferramentas relevantes e JSON de fluxo.

### Manipulação de JSON/Código

- Saídas grandes de JSON ou código são ocultadas atrás de botões **Ver JSON/Código** para manter a UI limpa.
- Edite JSON de fluxo no editor integrado com destaque de sintaxe e aplique mudanças diretamente.

### Cenários Suportados

#### Visão Geral dos Cenários

| Cenário | Nome em Português | Descrição | Ferramentas Suportadas |
|---------|-------------------|-----------|------------------------|
| learning | Modo de Aprendizado | Assistente de aprendizado Node-RED, fornece guias educacionais e respostas de conhecimento | get-flows, get-nodes, create-flow, update-flow |
| solution | Modo de Solução | Especialista em soluções IoT, fornece soluções técnicas e conselhos de arquitetura | create-flow, update-flow, get-flows, create-subflow |
| integration | Modo de Integração | Especialista em integração de sistemas, lida com conexão de dispositivos e integração de dados | create-flow, update-flow, install-node, get-node-info |
| development | Modo de Desenvolvimento | Assistente de desenvolvimento de código, suporta criação e otimização de fluxos Node-RED | create-flow, update-flow, create-subflow, get-node-info, install-node, get-flow |
| configuration | Modo de Configuração | Especialista em configuração de sistema, gerencia ambiente Node-RED e configuração de nós | get_settings, update_settings, install_node, get_node_info, get_diagnostics |
| management | Modo de Gerenciamento | Assistente de gerenciamento de projeto, suporta organização de fluxos e planejamento de projetos | get-flows, create-flow, update-flow, create-subflow |
| general | Modo Geral | Assistente de IA geral, lida com várias questões relacionadas ao Node-RED | Sem restrições específicas de ferramentas |

#### Exemplos de Prompts Pré-definidos

| Cenário | Prompts Pré-definidos |
|---------|------------------------|
| **Modo de Aprendizado** | • Sou novo no Node-RED. Por favor, apresente os conceitos básicos e principais recursos do Node-RED<br>• Por favor, explique fluxos, nós e conexões no Node-RED<br>• Como criar meu primeiro fluxo simples no Node-RED? Por favor, forneça passos detalhados<br>• Quais são os principais nós comumente usados no Node-RED? Quais são suas respectivas funções? |
| **Modo de Solução** | • Preciso projetar um sistema de controle de casa inteligente. Por favor, forneça uma arquitetura completa de solução IoT<br>• Como usar Node-RED para construir um sistema de coleta e monitoramento de dados da Indústria 4.0?<br>• Por favor, projete uma solução IoT agrícola incluindo coleta de dados de sensores e controle automático<br>• Quero construir uma rede de monitoramento ambiental de cidade inteligente, que soluções técnicas são necessárias? |
| **Modo de Integração** | • Como integrar dispositivos MQTT e APIs HTTP no Node-RED? Por favor, forneça uma solução de integração detalhada<br>• Preciso transmitir dados de sensores de dispositivos Modbus para um banco de dados na nuvem. Como implementar isso?<br>• Por favor, ajude a projetar um fluxo de transformação de dados que converta JSON para XML e envie para sistemas de terceiros<br>• Como implementar coleta e processamento integrado de dados de múltiplos dispositivos com diferentes protocolos no Node-RED? |
| **Modo de Desenvolvimento** | • Explicação e comentário detalhado do fluxo atual<br>• Explicação e comentário detalhado do nó atual<br>• Por favor, ajude a escrever código de nó Function que implementa filtragem de dados e conversão de formato<br>• Como criar nós personalizados no Node-RED? Por favor, forneça o procedimento completo de desenvolvimento |
| **Modo de Configuração** | • Qual é a configuração atual do NodeRED?<br>• Qual é o diagnóstico atual do NodeRED?<br>• Como configurar a configuração de segurança do Node-RED incluindo autenticação de usuário e HTTPS?<br>• Por favor, ajude a otimizar a configuração de desempenho do Node-RED para melhorar a eficiência de execução do sistema<br>• Como instalar e gerenciar pacotes de nós de terceiros no Node-RED?<br>• Preciso configurar logging e monitoramento do Node-RED. Como devo configurar? |
| **Modo de Gerenciamento** | • Por favor, ajude a criar um plano de desenvolvimento e marcos para projetos IoT<br>• Como organizar e gerenciar a estrutura de fluxos de projetos em larga escala no Node-RED?<br>• Preciso avaliar os riscos e qualidade do projeto atual. Por favor, forneça recomendações de análise<br>• Como estabelecer padrões de desenvolvimento Node-RED colaborativo em equipe e melhores práticas? |
| **Modo Geral** | • O que é Node-RED? Quais são suas principais características e cenários de aplicação?<br>• Encontrei problemas no Node-RED. Por favor, ajude com análise e soluções<br>• Por favor, recomende recursos de aprendizado Node-RED e melhores práticas<br>• Como escolher o modo de cenário Node-RED apropriado para resolver requisitos específicos? |

#### Ativação Inteligente por Palavras-chave

| Cenário | Palavras-chave | Ação de Ativação |
|---------|----------------|-------------------|
| **Modo de Desenvolvimento** | criar fluxo, gerar fluxo, fazer fluxo, novo fluxo | Muda automaticamente para modo de desenvolvimento para gerar código JSON completo de fluxo Node-RED e fornecer explicações detalhadas |
| **Modo de Configuração** | configuração atual, configuração do sistema, informações de configuração, configuração, configurações atuais | Chama automaticamente a ferramenta get_settings para buscar informações de configuração e exibir em formato de tabela |
| **Modo de Configuração** | diagnóstico atual, diagnóstico do sistema, informações de diagnóstico, verificação de saúde | Chama automaticamente a ferramenta get_diagnostics para executar diagnóstico do sistema |

#### Parâmetros de Entrada Dinâmicos

Todos os cenários suportam a seguinte injeção de parâmetros dinâmicos:
- `nodeRedVersion` - Informações da versão Node-RED
- `nodeVersion` - Informações da versão Node.js
- `currentTime` - Timestamp atual
- `selectedFlow` - Fluxo atualmente selecionado
- `selectedNodes` - Nós atualmente selecionados
- `lang` - Parâmetro de idioma atual
- `mcpTools` - Lista de ferramentas MCP disponíveis

Cada cenário também suporta parâmetros dinâmicos específicos:
- **Modo de Aprendizado**: `userLevel` (nível de habilidade do usuário)
- **Modo de Solução**: `projectRequirements` (requisitos do projeto)
- **Modo de Integração**: `integrationTargets` (alvos de integração)
- **Modo de Desenvolvimento**: `developmentTask` (tarefa de desenvolvimento)
- **Modo de Configuração**: `configurationNeeds` (necessidades de configuração)
- **Modo de Gerenciamento**: `projectStatus` (status do projeto)

#### Características dos Prompts do Sistema

Cada cenário é configurado com prompts de sistema profissionais para garantir que o assistente de IA possa:
1. **Definição de Papel**: Papel profissional claro em cenários específicos
2. **Formato de Saída**: Formato de resposta estruturado de acordo com requisitos do cenário
3. **Integração de Ferramentas**: Chamada inteligente de ferramentas MCP correspondentes e APIs Node-RED
4. **Reconhecimento de Contexto**: Recomendações personalizadas usando parâmetros dinâmicos


| Cenário | Descrição                                                                    |
| --------- | --------------------------------------------------------------------------- |
| Aprendizado | Explica nós/conceitos e fornece fluxos de exemplo para aprendizado.        |
| Solução | Fornece várias soluções IoT com JSON de fluxo e guias de instalação de nós. |
| Integração | Suporta integração de protocolo/software e gera fluxos correspondentes. |
| Desenvolvimento | Otimiza fluxos existentes e código de nós de função.                      |
| Configuração | Orienta mudanças na configuração do Node-RED (como `settings.js`).          |
| Gerenciamento | Suporta acesso remoto, integração Git e implantação em lote.                 |

## Provedores de IA Suportados


| Provedor | Modelos                                 | Características                |
| --------- | --------------------------------------- | ------------------------------ |
| OpenAI    | GPT-3.5, GPT-4, GPT-4o                 | Propósito geral, ampla compatibilidade |
| Anthropic | Claude-3, Claude-3.5                    | Raciocínio avançado, foco em segurança |
| Google    | Gemini Pro, Gemini Flash                | Multimodal, alto desempenho   |
| DeepSeek  | deepseek-chat, deepseek-coder           | Econômico, foco em codificação |
| Outros     | Todos os provedores LLM suportados pelo LangChain.js | Alta escalabilidade, configuração flexível |

## Configuração de API

- Chaves de API são armazenadas localmente com criptografia.
- Suporta configuração de múltiplos provedores.
- Fácil alternância entre diferentes provedores e modelos.
- Configuração separada de modelos para fases de planejamento e execução.

## Desenvolvimento

### Estrutura do Projeto

```
├── ai-sidebar.html          # Interface principal da barra lateral
├── ai-sidebar-config.json   # Configuração da UI
├── make-iot-smart.html      # Template de configuração do nó
├── make-iot-smart.js        # Implementação do nó backend
├── lib/
│   ├── langchain-manager.js # Gerenciador principal LangChain
│   ├── memory-manager.js    # Gerenciamento de memória SQLite
│   └── scenario-manager.js  # Gerenciamento de prompts baseado em cenários
├── config/
│   └── scenarios.json       # Arquivo de configuração de cenários
├── data/
│   └── memory.db           # Arquivo de banco de dados SQLite
└── package.json            # Configuração do pacote
```

### Arquitetura Técnica

Este projeto é baseado no framework **LangChain.js** e usa design de arquitetura modular:

- **LangChain Manager**: Gerenciamento principal de modelos de IA, suporta múltiplos provedores LLM
- **Memory Manager**: Sistema de memória inteligente baseado em SQLite, suporta memória de curto e longo prazo
- **Scenario Manager**: Gerenciamento de prompts baseado em cenários, suporta configuração JSON e parâmetros dinâmicos
- **Tool Manager**: Framework unificado de gerenciamento de ferramentas, integra ferramentas MCP e ferramentas integradas
- **API Layer**: Interface API RESTful, suporta chat em streaming e execução de ferramentas

### Contribuindo

1. Faça fork do repositório.
2. Crie uma branch de feature.
3. Faça suas mudanças e commit.
4. Envie um pull request.

## Roadmap

### Fase 1 (Concluída)

- ✅ Integração do assistente de IA
- ✅ Suporte multi-provedor
- ✅ Barra lateral interativa
- ✅ Gerenciamento de configuração
- ✅ Suporte baseado em cenários
- ✅ Migração da arquitetura LangChain.js
- ✅ Sistema de gerenciamento de memória SQLite
- ✅ Integração de ferramentas MCP
- ✅ Framework unificado de gerenciamento de ferramentas

### Fase 2 (Planejada)

- 🔄 Recursos de depuração remota
- 🔄 Recursos de colaboração em equipe
- 🔄 Análise avançada de fluxo
- 🔄 Ferramentas de implantação inteligente

### Fase 3 (Futuro)

- 📋 Sistema de gerenciamento de equipe
- 📋 Recursos empresariais
- 📋 Opções avançadas de segurança
- 📋 Treinamento de modelo personalizado

## Requisitos do Sistema

- Node.js >= 18.0.0
- Node-RED >= 2.0.0

## Licença

Licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## Suporte
O desenvolvimento de IA é mais uma arte do que uma tecnologia, e dominar LLMs não é uma tarefa simples, requerendo um entendimento profundo de modelos de IA, dados e cenários de aplicação. Cada sessão de Q&A pode produzir resultados diferentes, e versões iniciais são frequentemente insatisfatórias, mas através de melhorias na engenharia de prompts, gradualmente atenderão às necessidades diárias dos usuários Node-RED, sejam eles engenheiros de TI ou OT. Bem-vindos mais pessoas interessadas para participar do projeto.
- **Relatar Problemas**: [GitHub Issues](https://github.com/djzrs/fork-node-red-make-iot-smart/issues)
- **Documentação**: [Wiki](https://github.com/djzrs/fork-node-red-make-iot-smart/wiki)
- **Discussões**: [GitHub Discussions](https://github.com/djzrs/fork-node-red-make-iot-smart/discussions)

## Autor

**Zheng He**
- Email: jhe.zheng@gmail.com
- GitHub: [@jimmyfreecoding](https://github.com/jimmyfreecoding)
- Website: [https://www.makeiotsmart.com](https://www.makeiotsmart.com)
---

*Torne o desenvolvimento IoT mais inteligente com suporte de IA!*

---