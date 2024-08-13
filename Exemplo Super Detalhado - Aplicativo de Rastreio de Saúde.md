# Documento de Requisitos do Sistema (SRS) - Aplicativo de Rastreio de Saúde

## 1. Introdução

### 1.1. Visão Geral do Projeto
O Saúde Tracker é um aplicativo móvel projetado para ajudar os usuários a monitorar e gerenciar sua saúde e bem-estar. O aplicativo permitirá o rastreamento de atividades físicas, alimentação, sono e sinais vitais. Além disso, fornecerá recomendações personalizadas com base nos dados inseridos pelos usuários.

### 1.2. Objetivos do Documento
Este documento de requisitos define as funcionalidades e características esperadas do aplicativo Saúde Tracker. O objetivo é fornecer uma base clara para o desenvolvimento e garantir que todas as partes interessadas estejam alinhadas quanto às expectativas do produto final.

### 1.3. Escopo do Projeto
O aplicativo incluirá:

- Rastreamento de Atividades Físicas
- Monitoramento de Alimentação
- Controle de Sono
- Registro de Sinais Vitais
- Recomendações e Relatórios Personalizados
- Integração com Dispositivos de Monitoramento de Saúde

## 2. Requisitos Funcionais

### 2.1. Rastreamento de Atividades Físicas
Descrição: O aplicativo deve permitir que os usuários registrem suas atividades físicas diárias.

#### 2.1.1. Registro de Atividades
Descrição: O usuário deve poder registrar atividades como caminhada, corrida, ciclismo e natação.  
Campos Requeridos:
- Tipo de Atividade
- Duração
- Intensidade
- Distância  
Critério de Aceitação: As atividades registradas devem ser armazenadas e visíveis no histórico de atividades do usuário.

#### 2.1.2. Metas de Atividade
Descrição: O usuário deve poder definir metas diárias de atividade física.  
Campos Requeridos:
- Tipo de Atividade
- Meta de Duração
- Meta de Distância  
Critério de Aceitação: O aplicativo deve mostrar o progresso em relação às metas e enviar alertas quando as metas forem alcançadas.

### 2.2. Monitoramento de Alimentação
Descrição: O aplicativo deve permitir o registro de refeições e consumo de alimentos.

#### 2.2.1. Cadastro de Refeições
Descrição: O usuário deve poder registrar as refeições consumidas ao longo do dia.  
Campos Requeridos:
- Tipo de Refeição (café da manhã, almoço, jantar, lanche)
- Alimentos Consumidos
- Quantidade
- Calorias  
Critério de Aceitação: As refeições registradas devem ser armazenadas e exibidas no histórico alimentar do usuário.

#### 2.2.2. Análise Nutricional
Descrição: O aplicativo deve fornecer uma análise nutricional das refeições registradas.  
Dados Incluídos:
- Total de Calorias
- Distribuição de Macronutrientes (proteínas, carboidratos, gorduras)  
Critério de Aceitação: A análise nutricional deve ser precisa e fornecer recomendações para melhorias na dieta.

### 2.3. Controle de Sono
Descrição: O aplicativo deve permitir o rastreamento do sono dos usuários.

#### 2.3.1. Registro de Ciclos de Sono
Descrição: O usuário deve poder registrar o horário de início e fim do sono, bem como a qualidade do sono.  
Campos Requeridos:
- Horário de Início
- Horário de Fim
- Qualidade do Sono (boa, média, ruim)  
Critério de Aceitação: O aplicativo deve calcular a duração total do sono e exibir gráficos de tendência.

#### 2.3.2. Recomendações para Melhorias no Sono
Descrição: O aplicativo deve fornecer recomendações personalizadas para melhorar a qualidade do sono.  
Critério de Aceitação: As recomendações devem ser baseadas nas informações registradas e nas melhores práticas de sono.

### 2.4. Registro de Sinais Vitais
Descrição: O aplicativo deve permitir o registro de sinais vitais dos usuários, como pressão arterial e frequência cardíaca.

#### 2.4.1. Cadastro de Sinais Vitais
Descrição: O usuário deve poder registrar dados como pressão arterial e frequência cardíaca.  
Campos Requeridos:
- Pressão Arterial (sistólica/diastólica)
- Frequência Cardíaca
- Data e Hora  
Critério de Aceitação: Os sinais vitais registrados devem ser armazenados e visíveis no histórico de saúde do usuário.

#### 2.4.2. Alertas de Anormalidades
Descrição: O aplicativo deve alertar o usuário sobre possíveis anormalidades nos sinais vitais.  
Critério de Aceitação: Alertas devem ser gerados com base em valores fora da faixa saudável e fornecidos em tempo real.

### 2.5. Recomendações e Relatórios Personalizados
Descrição: O aplicativo deve gerar relatórios e recomendações baseadas nos dados inseridos pelo usuário.

#### 2.5.1. Relatórios de Saúde
Descrição: O aplicativo deve gerar relatórios sobre a saúde geral do usuário.  
Dados Incluídos:
- Resumo das Atividades Físicas
- Análise Nutricional
- Padrões de Sono
- Tendências de Sinais Vitais  
Critério de Aceitação: Relatórios devem ser exportáveis em PDF e Excel e fornecer insights úteis para a saúde do usuário.

#### 2.5.2. Recomendações Personalizadas
Descrição: O aplicativo deve fornecer recomendações personalizadas com base nas informações de saúde do usuário.  
Critério de Aceitação: Recomendações devem ser baseadas em dados inseridos e nas melhores práticas de saúde e bem-estar.

## 3. Requisitos Não Funcionais

### 3.1. Desempenho
Descrição: O aplicativo deve ser responsivo e eficiente em seu desempenho.  
Tempo de Resposta: As ações do usuário devem ser processadas em menos de 2 segundos.  
Capacidade de Dados: O aplicativo deve suportar grandes volumes de dados sem degradação do desempenho.

### 3.2. Segurança
Descrição: O aplicativo deve garantir a segurança e privacidade dos dados do usuário.  
Criptografia: Dados sensíveis devem ser criptografados utilizando padrões de segurança como AES-256.  
Autenticação: Implementar autenticação de dois fatores para acesso ao aplicativo e às informações de saúde.

### 3.3. Usabilidade
Descrição: O aplicativo deve ser intuitivo e fácil de usar.  
Design Responsivo: O aplicativo deve ser otimizado para diferentes tamanhos de tela e dispositivos móveis.  
Acessibilidade: Atender aos padrões de acessibilidade WCAG 2.1, incluindo suporte para leitores de tela e navegação por teclado.

## 4. Casos de Uso

### 4.1. Caso de Uso 1: Registrar Atividade Física
**Ator Principal:** Usuário

**Descrição:** O usuário deseja registrar uma nova atividade física.

**Fluxo Principal:**
1. O usuário seleciona "Registrar Atividade Física".
2. O usuário insere os detalhes da atividade, como tipo, duração, e intensidade.
3. O usuário salva a atividade.
4. O sistema confirma o registro e atualiza o histórico de atividades.

**Fluxo Alternativo:**
- Se o usuário inserir dados inválidos, o sistema exibe uma mensagem de erro e solicita correção.

### 4.2. Caso de Uso 2: Gerar Relatório de Saúde
**Ator Principal:** Usuário

**Descrição:** O usuário deseja gerar um relatório sobre sua saúde geral.

**Fluxo Principal:**
1. O usuário seleciona "Gerar Relatório de Saúde".
2. O usuário escolhe o período para o relatório.
3. O sistema processa os dados e gera o relatório.
4. O usuário visualiza e exporta o relatório em PDF ou Excel.

**Fluxo Alternativo:**
- Se ocorrer um erro ao gerar o relatório, o sistema exibe uma mensagem de erro e oferece uma opção para tentar novamente.

## 5. Requisitos de Integração

### 5.1. Integração com Dispositivos de Monitoramento de Saúde
Descrição: O aplicativo deve integrar-se com dispositivos como smartwatches e monitores de pressão arterial.  
Dispositivos Suportados:
- Apple Watch
- Fitbit
- Dispositivos de Medição de Pressão Arterial  
Critério de Aceitação: Dados coletados dos dispositivos devem ser sincronizados automaticamente com o aplicativo e exibidos corretamente.

### 5.2. Integração com Serviços de Saúde
Descrição: O aplicativo deve integrar-se com serviços de saúde para fornecer recomendações baseadas em dados de saúde pública.  
Serviços Integrados:
- APIs de Dados de Saúde Pública
- Serviços de Telemedicina  
Critério de Aceitação: As recomendações devem ser atualizadas com base em dados de saúde pública e refletidas nas análises do aplicativo.
