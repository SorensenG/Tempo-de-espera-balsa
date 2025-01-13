# Monitoramento do Tempo de Espera da Balsa de Ilhabela

Este programa foi desenvolvido durante uma viagem de férias e tem como objetivo monitorar o tempo de espera na balsa de Ilhabela, ajudando a escolher o melhor horário para viajar. Ele coleta informações do site oficial da Secretaria de Transportes do Estado de São Paulo e gera um gráfico para visualizar o tempo de espera ao longo do dia.
## Como funciona

- O programa coleta o tempo de espera da balsa de Ilhabela de 30 em 30 minutos.
- Ele salva o tempo de espera junto com a hora da coleta.
- Após 12 horas (24 coletas), um gráfico é gerado com o tempo de espera ao longo do dia.
- O gráfico é exibido e salvo como um arquivo de imagem chamado `grafico_tempo_espera.png`.

## Resultado

Ao final da execução, você verá o gráfico que mostra o tempo de espera em minutos ao longo das 12 horas, ajudando a identificar os melhores horários para viajar de Ilhabela para o continente.

## Requisitos

O programa utiliza as seguintes bibliotecas:
- `requests`: para fazer requisições HTTP ao site.
- `BeautifulSoup`: para fazer o parsing do conteúdo HTML.
- `matplotlib`: para gerar o gráfico do tempo de espera.

Instale as bibliotecas necessárias com o seguinte comando:

```bash
pip install requests beautifulsoup4 matplotlib
