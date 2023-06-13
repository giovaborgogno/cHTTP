```bash
# Install curl library:

sudo apt-get install libcurl4-openssl-dev

# Compile

gcc http.c include/cJSON.c  -lcurl -o http
