# nlp_huffman_coding
Scripts to convert rare words to huffman codes. Probably doesn't even work right

'read_file.py' reads a vocabulary and outputs a Huffman Code dictionary in the JSON format, also json dumps a vocabulary. The number of frequent words to save and the Huffman code alphabet size is defined by constants

'squash.py' converts the same file(s) using the dictionary and vocabulary (will combine the two together)
