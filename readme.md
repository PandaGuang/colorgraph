


``Use `code` in your Markdown file.``


1 to build:

1.1 installl boost
 ubuntu: `sudo apt install libboost-all-dev`
 mac: `brew install boost`

1.2 compile
mkdir build && cd build
cmake ..
make


2 to run:

cd bin/

./main 9  #run the program on randomly generated graph with size 9
./main (pull a txt file here)  #run the program on the graph in the txt file