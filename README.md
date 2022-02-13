# gur
Gurbani Automatic Speech Recognition

[Testset](https://archive.org/details/test.tar_202112) available on archive.org. The archive includes the labelled audio and the test results.

A working production model is deployed at [anaad.xyz](https://anaad.xyz) (for best results use audio clips of 20-30s in duration). There is a remote API now available. To use the API make a POST request to https://anaad.xyz/upload with the body: `{"audio": <audiodata>}`. Most audio formats are accepted but the file size should be less than 5mb and for best results stick to 20-30s long audio. Please keep in mind the model is hosted on a VPS with 1GB of RAM and a single core CPU so inferences should take approximately N seconds for a clip of length N seconds. 

The final trained pytorch model will be released with the publication of the paper. 
