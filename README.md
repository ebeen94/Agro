# Agro
This paper presents one of the first approaches to provide the understanding of agro (one of the unique eye attracting cues) headlines and thumbnails in online video sharing platform, Youtube. 

We annotated 1,881 headlines and thumbnails, based on agro and the type of agro. 
To sample our corpus, we used Youtube API to collect 10,000 headlines and thumbnails from Korean movie review channels in Youtube. These channels generally summarize the movie by skipping through the important plot with a complementary voice-over. We targeted the Korean movie channels in Youtube because they are noted for having agro headlines and thumbnails. 

Three annotators who were enthusiastic about movies were gathered via one of the private universities in South Korea for the agro labeling task. The annotators labeled the data based on : 'Content': with-content, without-content and 'Delivery': provocative, cliff-hanger

Then, we experimented with machine learning models to classify agro data from the non-agro data. 

With a Bi-LSTM model we achieved 84.35% percent accuracy in detecting agro headlines and 82.80% percent accuracy in detecting agro thumbnails. 



#Environment
Google Colaboratory


#Language
Python
