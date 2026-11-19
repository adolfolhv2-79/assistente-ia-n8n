# Cenários de teste sugeridos (dados fictícios)

Estes são **cenários propostos para evolução**, não uma declaração de testes já executados ou aprovados.

| Cenário | Entrada simulada | Comportamento esperado a validar |
| --- | --- | --- |
| Mensagem única | “Olá, gostaria de informações.” | Preparar entrada e produzir resposta contextual |
| Mensagens próximas | “Oi” + “Posso verificar um horário?” | Agrupar mensagens antes do processamento |
| Áudio | Arquivo de voz de teste autorizado | Transcrever e encaminhar como conteúdo textual |
| Imagem | Imagem de teste sem informações pessoais | Interpretar somente conteúdo pertinente |
| PDF | Documento fictício | Extrair texto e tratar erros de leitura |
| Consulta de horário | Pedido com dados simulados | Delegar a uma ferramenta compatível e lidar com ausência de resultados |
| Cancelamento | Pedido simulado de cancelamento | Conferir autorização e retorno do serviço antes de confirmar |
| Pausa humana | Estado simulado de atendimento por pessoa | Evitar resposta automática enquanto a pausa estiver ativa |
| Serviço indisponível | API de teste retorna erro | Não inventar resultado nem confirmar operação sem sucesso |

Para demonstrar esses cenários publicamente, criar uma **implementação independente** com serviços e pessoas fictícios.
