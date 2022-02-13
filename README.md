# gur
Gurbani Automatic Speech Recognition

[Testset](https://archive.org/details/test.tar_202112) available on archive.org. The archive includes the labelled audio and the test results.

A working production model is deployed at [anaad.xyz](https://anaad.xyz) (for best results use audio clips of 20-30s in duration). There is a remote API now available. To use the API make a POST request to https://anaad.xyz/upload with the body: {"audio": <audiodata>}. Any format is acceptable but the file size should be less than 5mb. 

Instructions on how to download and use the final trained pytorch model and reproduce the test results will be added after the paper is published. 
