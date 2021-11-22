# Agro
This paper presents one of the first approaches to provide the understanding of agro (one of the unique eye attracting cues) headlines and thumbnails in online video sharing platform, Youtube. 

To sample our data, we used Youtube API to collect 10,000 headlines and thumbnails from Korean movie review channels in Youtube. Then, we employed three annotators who are enthusiastic about movies to label the headlines and thumbnails based on agro. The annotators labeled the data based on 
1) 'Agro': agro, non-agro, 
2) 'Type of agro': 
                 'Content': with-content, without-content 
                 'Delivery': provocative, cliff-hanger

Since we asked the participants to label the data only if they have seen the movie, we were left with 1,881 headlines and thumbnails after the annotation. Among 1,881 headlines, 70% (1323) was agro and 30% (558) was non-agro. Within the Agro headlines, 42% (871) was cliff-hanger, 46% was provocative, and 17%(336) was both cliff-hanger and provocative. Within the agro headlines, 52%(986) was with-content, and 18%(337) was without-content.

To examine the reliability of the labeled dataset in detecting agro online, we experimented with machine learning models to classify agro data from the non-agro data. With a Bi-LSTM model we achieved 84.35% percent accuracy in detecting agro headlines and 82.80% percent accuracy in detecting agro thumbnails. 


-- As for the language and environment, we used Python and Google Colaboratory
