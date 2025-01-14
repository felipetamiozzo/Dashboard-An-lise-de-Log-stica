
# Dashboard de Análise Logística

Este projeto consiste em um dashboard desenvolvido no Power BI para análise e monitoramento de métricas logísticas, como tempos de entrega, status de pedidos e desempenho regional. O objetivo é fornecer insights para otimizar operações logísticas e melhorar a satisfação dos clientes.

## 📊 Funcionalidades

- Total de Entregas no Prazo Por Canal de Entrega;
- Percentual de Entregas Antecipadas Por Equipe de Entrega.
- Total de Entregas Por Mês.
- Total de Entregas no Prazo.
- Percentual de Entregas Por Status de Entrega.

## 🗂️ Estrutura do Projeto

- **Arquivo PBIX**: Contém o dashboard no Power BI com visualizações interativas.
- **Dataset**: Um arquivo Excel (`dataset.xlsx`) que serve como base de dados para o dashboard.
  - Aba "Logistica":
    - `ID_Pedido`, `ID_Vendedor`, `ID_Cliente`: Identificadores dos pedidos, vendedores e clientes.
    - `Equipe_Entrega`: Região responsável pela entrega.
    - `Data_Pedido`, `Data_Entrega_Prevista`, `Data_Entrega_Realizada`: Informações temporais sobre os pedidos.
    - `Status_Entrega`: Status da entrega (e.g., Antecipado).

- **Medidas DAX**
   - Total de Entregas
   - Total de Entregas no Prazo

## 🚀 Como Utilizar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
