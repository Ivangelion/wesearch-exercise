# wesearch-exercise

1. Since there are more then 100K files in the corpus, it took my laptop more than 40 minutes to upzip it.
2. Some files in the corpus seem not be able to be uploaded. Further check reveals that their file sizes are very small, and their content is very short. Those IngestFailed files are listed in the ingestfailed_files.txt file. 
3. It seems wesearch can only accept the first file in the files parameter of requests.post, if multiple files are specified as a list, as mentioned in the specs (https://docs.python-requests.org/en/latest/user/advanced/#advanced). So I could only specify one file in files parameter. 
