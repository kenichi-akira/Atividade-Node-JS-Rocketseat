# Atividade-Node-JS-Rocketseat
Atividade sobre mapeação de domínio

# Como não foi pedido diretamente um código escrito vou apenas deixar no README o que se foi pedido sobre o trabalho

# Quais as entidades de domínio?

As entidades de domínio são os principais elementos ou objetos que compõem o sistema e são manipulados pelas ações da aplicação. Com base na conversa, as entidades de domínio identificadas são:

    Produto
        - ID único
        - Nome
        - Descrição
        - Quantidade em estoque
        - Quantidade mínima
        - Informações adicionais (tamanho, cor)

    Movimentação de Estoque
        - ID da movimentação
        - Produto (referência ao ID do produto)
        - Quantidade
        - Data da movimentação
        - Tipo de movimentação (entrada, saída)

    Venda
        - ID da venda
        - Produto (referência ao ID do produto)
        - Quantidade vendida
        - Data da venda
        - Preço unitário
        - Lucro

    Ordem de Compra
        - ID da ordem
        - Produto (referência ao ID do produto)
        - Quantidade
        - Data da ordem
        - Status da ordem (pendente, concluída)
        - Fornecedor (se aplicável)

    Fornecedor
        - ID do fornecedor
        - Nome
        - Informações de contato

# Quais as ações (casos de uso) que essa aplicação deve ter?

As ações ou casos de uso são as principais funcionalidades ou operações que a aplicação deve permitir. Com base na conversa, os casos de uso identificados são:

    Rastrear Produto Individualmente
        - Atribuir um número de identificação único a cada produto
        - Adicionar e editar informações adicionais (tamanho, cor, etc.)

    Definir Quantidades Mínimas de Estoque
        - Configurar quantidade mínima para cada produto
        - Receber alertas quando o estoque estiver próximo do mínimo (via e-mail e notificação no sistema)

    Visualizar Histórico de Vendas e Estoque
        - Exibir vendas por período
        - Calcular lucro por produto
        - Identificar produtos mais vendidos
        - Exibir tendências de estoque ao longo do tempo

    Gerenciar Ordens de Compra
        - Criar ordens de compra automaticamente com base nas quantidades mínimas de estoque e tendências de vendas
        - Atualizar status das ordens de compra
        - Integrar com fornecedores para receber atualizações automáticas sobre prazos de entrega

    Receber Alertas de Estoque
        - Configurar métodos de recebimento de alertas (e-mail, notificações do sistema)
        - Enviar alertas quando estoque estiver abaixo do mínimo


