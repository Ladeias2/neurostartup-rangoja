# Model Card — Tempo de Entrega RangoJá
- **Uso pretendido:** mostrar ao cliente a previsão de chegada do pedido.
- **Não usar para:** punir ou remunerar entregadores.
- **Dados:** 3000 entregas sintéticas (seed 2026).
- **Modelo:** rede neural (32,), comparada a uma regressão linear.
- **Desempenho no teste:** erra em média 2.5 min (baseline: 4.5 min).
- **Limitações:** não conhece trânsito real nem acidentes; re-treinar com dados reais.
