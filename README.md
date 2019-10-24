# Links_externos

Esse é um script de validação de links usando o código da resposta do site, API do Youtube para saber se o vídeo ainda está disponível.
A chave API do youtube deve estar num arquivo de texto "YoutubeAPI.txt" para ser lido pelo programa.
Ele lê os links de uma planilha usando o pacote openpyxl, e usa pacote requests para as requisições.

Esse Script foi usado numa planilha de links externos do Bernoulli no dia 24/10 com sucesso, encontrando vários links errados que puderam ser alterados com antecedência.

Também foram encontrados muitos sites que por algum motivo acusaram erro, mas que ainda estavam funcionais. Por isso na parte final do script tem a etapa de abrir cada link no navegador com erro para uma última validação.
