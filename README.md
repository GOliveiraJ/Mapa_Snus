# Mapa_Snus

# 🌍 Painel de Inteligência Regulatória Global

Um *dashboard* interativo e estático desenvolvido para mapear e visualizar o status legal de produtos de nicotina (Snus, Sachês de Nicotina/Pouches e Vapes) em diversos países. 

O projeto consolida legislações complexas em uma interface visual limpa, permitindo consultas rápidas por região e fornecendo Indicadores-Chave de Desempenho (KPIs) dinâmicos com base no cenário global atualizado (2026).

## 🚀 Principais Funcionalidades

- **Mapa Interativo (Google GeoChart):** Visualização geoespacial com sistema de cores que categorizam o status regulatório (Permitido, Proibido, Lacuna, Restrito, Medicinal ou Projeto de Lei).
- **KPIs Dinâmicos:** Contadores em tempo real que se atualizam automaticamente ao alternar a visualização entre diferentes categorias de produtos.
- **Dossiê por País:** Painel lateral detalhado que exibe o contexto jurídico, regras específicas e observações de mercado ao clicar em um país no mapa ou utilizar a barra de busca.
- **Arquitetura Estática (Serverless):** Alta performance e segurança nativa, com o banco de dados de inteligência embutido diretamente na camada de *frontend* (JavaScript).

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Estruturação semântica e estilização com design responsivo, variáveis nativas (`:root`) e interface moderna.
- **JavaScript (Vanilla):** Lógica de estado, manipulação do DOM e estruturação do banco de dados em formato de objeto para rápido acesso temporal.
- **Google Charts API:** Renderização do mapa-múndi e *tooltips* customizados.

## 💻 Como Executar e Hospedar

Por ser uma aplicação 100% estática, não há necessidade de instalar dependências, servidores ou configurar bancos de dados.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
   Dê um duplo clique no arquivo index.html para abri-lo em qualquer navegador web moderno.
   Hospedagem Gratuita: O painel está otimizado para ser publicado rapidamente utilizando o GitHub Pages.
