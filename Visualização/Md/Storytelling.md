# Storytelling 🎬

## Dados estáticos Vs. Dados dinâmicos

Para identificar qual tipo de data se encaixa melhor, deve-se analisar alguns fatores como:
- Quão antigo são os dados?
- Em quanto tempo os dados deixam de ser válidos ou confiáveis para a tomada de decisão?
- Os dados precisam de updates constantes para manterem válidos?
  
### Dados estáticos
Dashboards construídos e cima de dados estáticos são como um screenshot daquele dashboard
- **Pontos positivos:**
  - Controle completo da narrativa e insight que os dados proporcionam
  - Permite que análises complexas possam ser apresentadas em detalhes para a audiência
-  **Pontos negativos:**
  -  Perdem o valor com o tempo
  -  Não é possível manter o ritmo das mudanças que os dados sofrem com dashboards estáticos

### Dados dinâmicos
Dashboards construídos conectados com o banco de dados que é atualizado constantemente
- **Pontos positivos:**
  - Podem ser feitos para serem mais dinâmicos e escaláveis
  - Oferece os dados mais recentes sempre que precisar
  - Permite a tomada de decisão imediata
  - Diminui o tempo e recursos despendidos a cada análise
- **Pontos negativos:**
  - Precisa de um trabalho de engenharia para manter o pipeline de dados dinâmico e escalável
  - Pode levar a interpretações erradas, visto que se perde o controle sobre a visualização
  - Pode causar visualizações mentirosas se não for usado corretamente