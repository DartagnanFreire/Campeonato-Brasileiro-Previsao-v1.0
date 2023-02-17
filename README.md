# Campeonato-Brasileiro-Previsao
Prevendo o campeão brasileiro com base no aproveitamento do ano de 2021

Este é um código ainda em desenvolvimento, apesar de já conseguir entregar o que se propõe.
Funcionamento:
  - É utilizado como principal parâmetro o aproveitamento do time no ano de 2021.
    - Para isso é utilizado os pontos conquistados / pontos totais disputados (3 pontos para vitória, 1 ponto para empate)
    - Além disso, é utilizado pesos para as competições, sendo elas:
      - Estaduais - Peso 0,5
      - Nacionais - Peso 1
      - Continentais - Peso 2
      - Internacionais - Peso 3 
     - Por exemplo: 10 jogos geram um total de 30 pontos disputados. Caso o time tenha vencido 3 partidas e empatado 2, terá feito 11 pontos e 36.6% de aproveitamento.
  - Levamos em consideração a proporção do maior aproveitamento com o menor aproveitamento, assim estabelecendo um valor mínimo (no caso 50). 


ROADMAP

- Melhorar o código para ser mais clean e de acordo com a PEP8

Atualização: Melhorando o código e trazendo para o ano de 2023, com base no rendimento dos times de 2022. Também foram incluidos os times que subiram de divisão e excluídos os que foram rebaixados.
Para esse ano, decidi não utilizar os pesos dos campeonatos.
Porém, decidi utilizar a proporção de gols feitos/gols tomados, fazendo com que um time que tenha uma razão maior tenha vantagem.
  Exemplo: o Palmeiras fez 139 gols e sofreu 49, o que da uma razão de 65.47 a mais de gols feitos. Já o Flamengo, apesar de ter feito 144 gols no ano, sofreu 70, o que significa que tem uma razão de 51.39, neste caso, o Palmeiras tem uma leve vantagem. Também será utilizado o fator casa, no qual o time jogando no seu estádio, terá um acréscimo de 15% no fator motivacional.
