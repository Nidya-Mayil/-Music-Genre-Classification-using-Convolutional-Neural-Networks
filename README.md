# Music-Genre-Classification-using-Convolutional-Neural-Networks
Classification of different Genres in the given Music file using Machine Learning.

A Convolutional Neural Network is trained with 7000 sample audios, validated with 2000 sample audios and tested with 1000 audios of 10 different music genres.
  
**Dataset Used to train**: GTZAN Genre Collection dataset by G.Tzanetakis and P.Cook ( http://marsyas.info/downloads/datasets.html )  

**Genres**: Blues, Classical, Country, Disco, Hiphop, Jazz, Metal, Pop, Reggae, Rock  
             
## Usage
$**python3**  Music_Genre_Classification.py ( Give input audio path in the code file at #Get_Genre )
  
### Example
$**cd**  src

$**python3**  Music_Genre_Classification.py

**--> disco**: 62.50%  
**--> rock**:  35.42%  
**--> reggae**: 2.08%  
   
***Note:*** Test audio (test_music.wav) is a Disco song, "Every 1's A Winner" by 'Hot Chocolate'.
