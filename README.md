# Campeonato-Brasileiro-Previsao
Prevendo o campeão brasileiro com base no aproveitamento do ano de 2021

Este é um código ainda em desenvolvimento, apesar de já conseguir entregar o que se propõe.
Atualmente, o código considera apenas vitórias ou derrotas, não ocorrendo nenhum empate.

ROADMAP
- Incluir empates - Será determinado uma diferença mínima (algo parecido com margem de erro) - A ser definido
- Fator Casa (onde o time jogando em casa, tem maiores chances de vitória) - Será acrescentado 10% do valor Motivate para o time da casa.
- Melhorar o algoritimo, para que ele seja mais condizente com a realidade.
  - Foi alterado seguindo o aproveitamento do ano. Também foi levado em conta a dificuldade da competição.
    - Estaduais - Peso 0,5
    - Nacionais - Peso 1
    - Continentais - Peso 2
    - Internacionais - Peso 3 
    
Isso fez com que times como o Atlético Mineiro tivesse mais peso no ano, já que o ranking da CBF leva em conta os últimos 5 anos, favorecendo demais o Palmeiras e o     Flamengo.
- Melhorar o código para ser mais clean e de acordo com a PEP8
