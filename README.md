# Dashboard de Clima Escolar — Rede Municipal de Joinville

Um aplicativo web interativo para análise e visualização de dados de pesquisa de clima escolar, desenvolvido pela Secretaria de Educação de Joinville/SC com base na **Escala Delaware de Clima Escolar** e metodologias consolidadas (PeNSE, PISA, GSHS).

## 📋 Sobre o Projeto

Este dashboard foi desenvolvido para auxiliar gestores e pesquisadores na análise do clima escolar da rede municipal de Joinville. O diagnóstico aborda as percepções de estudantes dos Anos Finais do Ensino Fundamental sobre:

- **Clima Escolar** — relações interpessoais, suporte, segurança e pertencimento
- **Engajamento Acadêmico** — motivação e envolvimento com a aprendizagem
- **Bem-Estar Psicológico** — saúde mental, pertencimento e mindfulness
- **Hábitos de Vida** — práticas de sono, exercício físico e comportamentos de risco
- **Apoio Familiar** — suporte e supervisão dos pais/responsáveis
- **Comparações por Escola** — identificação de padrões e diferenças entre unidades

Os resultados subsidiam **tomadas de decisão baseadas em evidências** para promoção de um ambiente educacional mais seguro, equitativo e propício ao desenvolvimento integral.

## 🚀 Como Usar

### Opção 1: Abrir Localmente
Baixe o arquivo `index.html` e abra-o diretamente no navegador (duplo clique).

### Opção 2: Acessar em GitHub Pages
1. Acesse o link `https://sed-ndi.github.io/clima-escolar`
2. Clique em `Carregar dashboard`


## 📊 Funcionalidades

- ✅ **Carregamento de dados via Google Sheets** — Cole um link público de uma planilha Google para análise automática
- ✅ **Upload de arquivo CSV** — Importe dados locais em formato CSV
- ✅ **8 abas de análise** — Visão geral, clima escolar, engajamento, hábitos, bem-estar, família, comparativo por escola e correlações
- ✅ **Filtros demográficos** — Escola, ano, turno e sexo
- ✅ **Gráficos interativos** — Barras, pizza, scatter plots e matriz de correlação
- ✅ **Cálculo automático de índices** — Scores padronizados para cada dimensão da pesquisa
- ✅ **Funciona offline** — Sem necessidade de backend ou servidor; roda 100% no navegador

## 🛠️ Especificações Técnicas

- **Linguagem:** HTML5 + JavaScript (vanilla)
- **Gráficos:** Chart.js 4.x
- **Parsing de CSV:** PapaParse 5.5.4
- **Estilos:** CSS3 responsivo
- **Compatibilidade:** Todos os navegadores modernos (Chrome, Firefox, Safari, Edge)
- **Tamanho:** ~450 KB (arquivo único, incluindo todas as dependências via CDN)

## 📚 Referências Teóricas

O projeto baseia-se em:
- **Delaware School Climate Scale** — Instrumento psicométrico de referência internacional
- **Pesquisa Nacional de Saúde do Escolar (PeNSE)** — IBGE
- **Programa Internacional para Avaliação de Alunos (PISA)** — OCDE
- **Global School-based Student Health Survey (GSHS)** — OMS/CDC

Para detalhes completos, consulte: *"Projeto de Pesquisa - Diagnóstico de Clima Escolar da Rede Municipal de Joinville"*


## 🔒 Privacidade e Segurança

- Todos os dados são processados **localmente no navegador do usuário**
- Nenhuma informação é enviada para servidores externos (exceto ao carregar via Google Sheets)
- O dashboard **não coleta, armazena ou rastreia dados pessoais**

## 🤝 Contribuindo

Sugestões de melhorias, correções e novas funcionalidades são bem-vindas! Abra uma issue ou pull request com suas propostas.

## 📄 Licença

Este projeto é desenvolvido pela **Secretaria de Educação - Área de Desenvolvimento Integral (U.E.F.)** da Prefeitura Municipal de Joinville/SC.

---

**Desenvolvido com foco em evidência, segurança e desenvolvimento integral dos estudantes joinvilenses.**
