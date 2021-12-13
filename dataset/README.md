# stance-thread-detector - DATASET
Esta carpeta contiene todos los archivos necesarios para entrenar un clasificador para el problema descripto en el README principal.

Hay 3 Archivos
1. Tweets base (dataset.csv)

-created_at = fecha del tweet
- id_str = id del tweet
- full_text = texto del tweet
- in_reply_to_status_id = id_str de su tweet inmediato anterior (al que responde)
- in_reply_to_user_id = user.id de a quien le responde este tweet
- user.id = user autor del tweet.

2. Etiquetas de humanos a los tweets en el dataset

- id_str = tweet id
- label = Etiqueta del tweet con id *id_str*. La etiqueta puede ser {"Apoyo", "Oposición", "Pregunta", "Comentario", "No Relacionado"}

3. Usuarios que retwittearon los tweets del dataset 

- id_str = tweet id
- user_retweeters = Usuarios que hicieron retweet a los tweets con id *id_str* en el dataset
---
---

Thse folder contains all the data necessary to train the problem that I described on the main README.

There are 3 files

1. Raw Tweets with the following fields (dataset.csv=

created_at = tweet's creation date 
id_str = tweet id
full_text = full text on the tweet  
in_reply_to_status_id = tweet id that belongs to the inmediately preceding tweet on the twitter thread
in_reply_to_user_id = user id who wrote the tweet id in "in_reply_to_status_id"
user.id = tweet's author id

2. Manual labels to tweets in the previous dataset

id_str = tweet id
label = label of the tweet with id *id str*. It can belong to {"Apoyo", "Oposición", "Pregunta", "Comentario", "No Relacionado"}

3. Retweets to the tweets in the dataset

id_str = tweet id
user_retweeters = Users that made a retweet to the tweet with id *id str*
