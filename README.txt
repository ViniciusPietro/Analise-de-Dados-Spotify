Análise de Dados de playlists do Spotify utlizando a biblioteca Spotipy para Python 3

Analisa pelo código da playlist obtendo dados das músicas contidas.
Para mais informações acesse 
	https://github.com/plamere/spotipy

Parâmetros a serem analisados
Energy - Medida de 0 a 1, que representa a intensidade da música.
Liveness - Detecta se a música é gravação ao vivo ou não.
Tempo - A estimativa das batidas por minuto.
Speechiness - Detecta a presença de palavras faladas em uma música.
Acousticnnes - Medida de 0 a 1, que representa a acusticidade da música.
Instrumentalness - Detecta se a música possui ou não Vocais.
Time Signature - A assinatura de tempo geral da música. A assinatura mede especificamente quantas tem em barra (medida musical)
Danceability - Descreve o quanto a música é dançavel, baseado em estabilidade de ritmo, batida e regularidade.
Key - Qual a nota musical mais presente na música.
Duration MS - Duração da música em milisegundos.
Loudness - A altura geral da música em decibéis.
Valence - Valor de 0 a 1 que descreve o 'humor' músical. Alta valência, música com o humor mais alegre e baixa valência, músicas com o humor mais triste.
Mode - Indica a modalidade da música se a nota mais presente é Maior ou Menor.
Type - Neste caso o tipo sempre será "audio_features".
Uri - A URI do Spotify, para a música em questão.

Para informações mais detalhadas sobre os parâmetros, acesse 

https://developer.spotify.com/documentation/web-api/ 
