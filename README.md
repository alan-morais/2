python
`import  requests`

`# partidos
partidos = requests.get("https://dadosabertos.camara.leg.br/api/v2/partidos")
print(partidos.content)`

`# deputados
partidos = requests.get("https://dadosabertos.camara.leg.br/api/v2/deputados")
print(partidos.content)`

