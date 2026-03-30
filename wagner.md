## Filtro de veículos

**Como será feito:**
Campos de filtro (preço, tipo e modelo) implementados em HTML com apoio de JavaScript para refinar os resultados dinamicamente.

**Para que serve:**
Permitir que o usuário encontre veículos de forma rápida e personalizada, de acordo com suas preferências.


## Visualizar detalhes do veículo

**Como será feito:**
Página de detalhes que exibe informações completas do veículo (modelo, preço, descrição, imagens), carregadas do banco de dados.

**Para que serve:**
Permitir que o usuário veja todas as informações antes de tomar a decisão de aluguel ou compra.


## Sistema de reserva de veículos

**Como será feito:**
Formulário de reserva com seleção de datas, veículo e dados do cliente, integrado ao banco de dados para registrar e gerenciar as reservas.

**Para que serve:**
Permitir que o usuário agende a utilização de um veículo de forma prática e organizada.


## Seleção de datas de retirada e devolução

**Como será feito:**
Campos de data (date picker) em HTML com validação via JavaScript para garantir períodos válidos e disponibilidade do veículo.

**Para que serve:**
Permitir que o usuário escolha o período de uso do veículo de forma correta e evitar conflitos de reservas.


## Cálculo automático do valor do aluguel

**Como será feito:**
Script em JavaScript que calcula o valor com base no período selecionado, preço diário do veículo e possíveis taxas adicionais.

**Para que serve:**
Exibir ao usuário o custo total do aluguel em tempo real, facilitando a tomada de decisão.


## Verificar disponibilidade do veículo

**Como será feito:**
Consulta ao banco de dados para checar se o veículo está livre no período selecionado, considerando reservas já existentes.

**Para que serve:**
Garantir que o usuário só possa reservar veículos disponíveis, evitando conflitos e reservas duplicadas.


## Status da reserva (ativa, concluída, cancelada)

**Como será feito:**
Campo de status no banco de dados atualizado automaticamente conforme o andamento da reserva (criação, finalização ou cancelamento).

**Para que serve:**
Permitir o controle e acompanhamento das reservas tanto pelo sistema quanto pelo usuário.


## Ordenação de veículos (preço, popularidade)

**Como será feito:**
Opções de ordenação implementadas com JavaScript ou no backend para organizar a lista de veículos por preço ou popularidade.

**Para que serve:**
Facilitar a navegação, permitindo que o usuário visualize os veículos de acordo com seus critérios de preferência.


## Notificação de reserva confirmada

**Como será feito:**
Envio automático de notificação (e-mail ou mensagem) após a confirmação da reserva, utilizando integração com serviços de comunicação.

**Para que serve:**
Informar o usuário que a reserva foi realizada com sucesso, garantindo mais segurança e confiança no sistema.


## Integração com pagamento (simulado)

**Como será feito:**
Simulação de pagamento via formulário, validando dados básicos e confirmando a transação sem uso de gateways reais.

**Para que serve:**
Permitir testar o fluxo completo de reserva com pagamento, sem necessidade de integração com serviços financeiros reais.


## Compartilhamento de veículos favoritos

**Como será feito:**
Botão de compartilhamento que gera link ou opção de envio via redes sociais ou e-mail, utilizando identificador do veículo favorito do usuário.

**Para que serve:**
Permitir que o usuário compartilhe veículos de interesse com amigos ou familiares, facilitando decisões de compra ou aluguel.
