🍄 Automação de Estufa para Fungicultura (Lógica Digital)
Projeto acadêmico de lógica combinacional desenvolvido para automatizar o controle ambiental e a segurança de uma estufa de cultivo de cogumelos (shimeji/champignon).

📋 Descrição do Projeto
O sistema monitora variáveis como temperatura, umidade e luminosidade para maximizar a produtividade, além de gerenciar a segurança do ambiente através de sensores de presença nas portas.

🛠️ Tecnologias e Metodologias
• Software de Simulação: Logisim.

• Lógica Combinacional: Álgebra de Boole e Mapas de Karnaugh para otimização.

• Hardware: Planejado para a família TTL 74LS (74LS04, 74LS08, 74LS32).

🚀 Destaques Técnicos
1. Otimização Lógica (Redução de Custos)
Utilizei a Álgebra de Boole para simplificar a lógica do alarme de invasão. A expressão original complexa foi reduzida a uma porta OR simples, economizando componentes e reduzindo o custo final do hardware:
A = P₁ + P₂

2. Integridade de Dados (Paridade Ímpar)
Implementei um gerador e verificador de paridade ímpar (Odd Parity) para garantir que os dados transmitidos pelos sensores cheguem sem erros ao sistema central. Se ocorrer um erro de bit na transmissão, o sistema sinaliza imediatamente através da saída ERRO_PARIDADE.

3. Sistemas Controlados
• Clima: Acionamento automático de umidificador, aquecedor e ventiladores.
• Iluminação: Controle de lâmpadas baseado no sensor de luminosidade alta (L/ALTA).
• Segurança: Ativação de câmera e alarme sonoro em caso de violação das portas.
