# Coleta e análise de sentimento de tweets

Nesse projeto eu faço coletas de tweets utilizando a api do Twitter através da biblioteca tweepy e realizo análises de sentimento utilizando a biblioteca TextBlob. 

Inicialmente eu analiso tweets sobre alguns líderes mundiais e mostro a porcentagem de tweets negativos, neutros e positivos para cada um. Em seguida, eu faço uma brincadeira e analiso o sentimento sobre os tweets que mencionam a Peppa Pig e também os tweets sobre o Bob Esponja.  Por fim, eu analiso os tweets sobre as séries Stranger Things e Better Caul Saul.

As análises são realizadas nos textos dos últimos 200 tweets a partir do momento de início da coleta. Um tweet é classificado como: 'Negativo' se a métrica de polaridade fornecida pelo TextBlob é menor do que -0.1, 'Positivo' se a polaridade é maior do que 0.1 e 'Neutro' se encontra-se entre esses valores. 

Esse projeto foi desenvolvido para práticar técnicas de extração de tweets e explorar o uso das biblioteca tweepy e TextBlob. Os resultados obtidos não devem ser utilizados para tomar conclusões sobre as avaliações das pessoas, personagens e séries mencionadas. 

Para desenvolver o projeto eu utilizei as seguintes referências:

* vídeo da Kizzy Terra, do canal Programação Dinâmica (https://www.youtube.com/watch?v=RssGfmtyn4A)
* vídeo do Mehran Shakarami, do canal AI Spectrum (https://www.youtube.com/watch?v=Lu1nskBkPJU&t=11s)
* aulas do professor Tulio Philipe para o curso Cientista de Dados da XP educação.

Os gráficos abaixo mostram os resultados das análises de sentimento.

