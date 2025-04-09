# mapa_eleicoes_2018_v2

## Buscar as tabelas nos sites:

# ----------------------------------------------------------

https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html

caminho_shapefile = r'D:\Usuários\Downloads\BR_Municipios_2018\BR_Municipios_2018.shp'

# ----------------------------------------------------------


https://dadosabertos.tse.jus.br/dataset/resultados-2018

df_votacao = pd.read_csv('./dados_eleicao/votacao_candidato_munzona_2018_BR.csv',
                        sep=';', encoding='latin1')
# ----------------------------------------------------------

