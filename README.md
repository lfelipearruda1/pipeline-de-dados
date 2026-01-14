# Pipeline de Dados – Vendas e Cotações (Indústria de Máquinas Agrícolas)

Este repositório reúne o pipeline de dados desenvolvido para processar, padronizar e consolidar informações de vendas e cotações. O objetivo é gerar insights confiáveis e entregá-los de forma otimizada para consumo por ferramentas de BI.

## 🚀 Visão Geral do Projeto

- **Ingestão (Bronze):** captura automática de arquivos CSV (vendas e cotações) por meio do Auto Loader no Databricks.  
- **Limpeza e Padronização (Silver):** correção de tipos, padronização de nomes (como municípios), tratamento de nulos e marcação de registros críticos.  
- **União e Métricas (Gold):** consolidação de vendas e cotações em uma única tabela, com cálculo de métricas por cidade (total de vendas, número de cotações, taxa de conversão).  
- **Armazenamento Otimizado:** uso de tabelas Delta Lake para consultas rápidas, versionamento (time travel) e integração fácil com BI.  
- **Automação:** execução recorrente via Jobs do Databricks, com monitoramento, alertas e governança via Unity Catalog.  

## 🎨 Slides de Apresentação

Aqui está o link dos **slides do projeto**, que resumem as etapas, decisões técnicas e resultados obtidos:

👉 [Ver slides de apresentação no Canva](https://www.canva.com/design/DAGxkoI_w7o/tlSOrPiRSzOJZTCb76iwAw/edit?utm_content=DAGxkoI_w7o&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## 👤 Autor

**Luiz Felipe Arruda**  
📧 E-mail: lfelipearrudacc@gmail.com
