# Roteiro da apresentação — 7 minutos
**Flaviane Cristina Pereira Marra · Projeto final DS-PY-018**

## 0:00–0:50 · Abertura e contexto
"Analisei 8.058 pedidos de 2024 em São Paulo, Rio e BH. Em uma frase: **a chuva atrasa as entregas, e o atraso derruba a avaliação.**"

## 0:50–1:30 · Hipóteses
"Das cinco hipóteses do roteiro, quatro deram SIM e a de pagamento por cidade deu NÃO. Eu criei uma sexta: **o cupom continua trazendo mais clientes novos mesmo fora do Julho de cupons?** A resposta foi SIM."

## 1:30–2:15 · Dificuldade encontrada
"720 pedidos vieram com a linha inteira numa coluna só, porque o valor estava escrito como 'R$ 44,02'. Re-li essas linhas e não perdi nenhum pedido. Também havia 13 grafias para 3 cidades, tempo com 999 e negativo e distâncias impossíveis. 24 pedidos muito caros eram reais, de empresas; usei a mediana."

## 2:15–5:00 · Cinco achados
1. **Chuva atrasa as entregas em 9 min (mediana).** Com chuva, 35,3% passam de 45 min, contra 11,3% sem chuva; no pior cenário (chuva, pico) chega a 45% (Tarefas 6.8, 9.1 e 10.1).
2. **Demora derruba a avaliação:** até 35 min a nota média é 4,49; acima, 4,20 (ρ = -0,24, Tarefa 9.3). A queda forte começa na faixa de 40–45 min (Tarefa 7.7).
3. **18,4% das entregas quebrariam uma promessa de 45 min** (1.476 pedidos; 90% chegam em até 50 min, Tarefa 5.4).
4. **O cupom traz cliente novo o ano inteiro (H6 = SIM):** fora de julho, 34,7% dos pedidos com cupom são de clientes novos, contra 13,1% sem cupom — 2,7× (p < 0,001; OR ajustado pela campanha 3,7). No Julho de cupons o uso foi 46% (outros meses 18%) e os pedidos/dia variaram 22,9% (Tarefas 6.7 e 9.6).
5. **O pedido típico é R$ 62 e depende da cozinha:** de R$ 38 (Doces) a R$ 108 (Japonesa), ε² = 0,41; 24 pedidos corporativos puxam a média para R$ 72 (Tarefas 4.5 e 9.4).

## 5:00–6:15 · Três recomendações
1. **Plano de chuva: mais entregadores e prazo maior exibido nos dias com previsão de chuva.** Métrica: % acima de 45 min em dias de chuva.
2. **Meta de entrega em até 40 min, com alerta para restaurantes e regiões que passam disso.** Métrica: avaliação média e % de notas abaixo de 4.
3. **Cupom como porta de entrada o ano todo (primeiro pedido), medido com teste A/B antes de repetir o Julho de cupons.** Métrica: % de clientes novos e custo do cupom por cliente novo.

## 6:15–7:00 · Limitação e fechamento
"A base não identifica o cliente, então não sei se quem entrou com cupom voltou. E os dados mostram relação, não causa. O próximo passo é um teste A/B de cupom. Obrigada."
