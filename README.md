### Entidades de Domínio Identificadas:

1. **Produto**: Atributos: ID único, tamanho, cor, quantidade em estoque, quantidade mínima definida.
2. **Estoque**:  Relacionada a produto, com informações sobre quantidade atual, histórico de movimentações (entradas/saídas).
3. **Alerta**: Registra notificações de estoque baixo.
4. **Venda**: Detalhes como data, produto vendido, quantidade, lucro gerado.
5. **OrdemCompra**: Relacionada a produto e fornecedor, com status (ex: pendente, entregue).
6. **Fornecedor**: Informações de contato, prazos de entrega, produtos fornecidos.
---
### Casos de Uso Identificados:
1. **Gestão de Estoque**:
    - Definir quantidade mínima por produto.
        
    - Registrar entrada/saída de produtos (ex: vendas, reposições).
        
2. **Alertas Automáticos**
    - Gerar alerta quando estoque está abaixo do limite mínimo (notificação por e-mail e no sistema).
        
3. **Histórico e Relatórios**
    - Visualizar histórico de vendas (período específico, lucro por produto, produtos mais vendidos).
        
    - Analisar tendências de estoque (ex: gráficos de variação mensal).
4. **Ordens de Compra Automáticas**
    - Criar ordens de compra com base em estoque mínimo e tendências de vendas.
   
    - Gerenciar status de ordens (ex: aprovar, cancelar).
        
5. **Integração com Fornecedores**
    - Receber atualizações automáticas de prazos de entrega.
        
    - Sincronizar dados de produtos com fornecedores.
