The index files contain a B-Tree managed by this program. Users can create the files, insert key-value pairs, search for keys, load data from the file, and extract the index. The index files have been split into blocks, each of size 512 bytes, with a header and node structure. It contains a magic number in its header, root ID, and the next block ID. Each node block holds keys, values, and child pointers for B-Tree management.

Commands include creating and opening files, inserting and searching keys, printing all pairs, loading data from CSVs, and extracting the tree into a new file. Run the program interactively and follow the on-screen prompts to execute commands.

Submit the project with all code, a devlog detailing the work, and this README in the zipped repository.
