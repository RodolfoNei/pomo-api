# pomo-api

- Problema: organizar meus horários de estudo e de trabalho (e avaliar usar para todo o resto) usando a técnica do pomodoro combinada com todo list

- TDD
- Laravel API
- React/Typescript
- Model
    - Pomodoro   
        - id
        - subject
        - duration
        - datetime
        - level of difficulty / comfort zone
        - review/learning
        - criado em
        - criado por
        - atualizado em
        - atualizado por
    - Level of difficult / Comfort Zone
        - id
        - name
    - Subject    
        - id
        - name
        - criado em
        - criado por
        - atualizado em
        - atualizado por
    - Pomodoro Sauce
        - id
        - pomodoros
        - weekday
        - criado em
        - criado por
        - atualizado em
        - atualizado por
    - Schedule
        - id
        - pomodoro sauce 
        - criado em
        - criado por
        - atualizado em
        - atualizado por
 - UI

## ToDos
- Desenvolver uma versão básica para deploy (estudar maneiras de deploy)
- Terminar modelo lógico
- Pensar na dinâmica de uso de um pomo manager
    - 1
        - Estipular uma meta semanal
        - Usar pomodoros no dia a dia
        - Avaliar no fim da semana os resultados
        - Estipular a meta para a semana seguinte
    - 2
        - Usar pomodoros primeiro em uma agenda mais livre
        - Organizar os pomodoros em uma agenda e avaliar os resultados
        - Adaptar a agenda 
     
