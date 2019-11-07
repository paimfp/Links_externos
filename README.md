# Links_externos

Este é um script de validação de links.
Usa-se o código da resposta de requisição do site, se for link do youtube, usa uma API para verificar se o vídeo ainda está disponível.
A chave API do youtube deve estar num arquivo de texto "YoutubeAPI.txt" para ser lido pelo programa.

O pacote openpyxl é usado para ler os dados de uma planilha. O requests é usado para fazer as requisições e análisar o código de resposta.

Esse Script foi usado numa planilha de links externos do Bernoulli no dia 24/10/2019 com sucesso, encontrando vários links errados que puderam ser alterados com antecedência.

Também foram encontrados falsos positivos: sites que por algum motivo acusaram erro, mas que ainda estavam funcionais. Por isso na parte final do script tem a etapa de abrir cada link no navegador com erro para uma última validação manual.
