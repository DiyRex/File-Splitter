# File-Splitter


CLI tool to split files into chunks in windows (like split tool in linux)



usage:

split -s [chunk_size] -f [filename.ext] -o [output_name]

options:
  -h, --help           show this help message and exit
  -s , --chunk_size    size of a single part**
  -f , --file_path     source file
  -o , --output_file   out file [no extention]
  
  ** Chunk size can be input as follows,
  
    ⦿ Bytes(B) - 5b or 5B
    ⦿ KiloBytes(KB) - 5k or 5K
    ⦿ MegaBytes(MB) - 5m or 5M
    ⦿ GigaBytes(GB) - 5g or 5G
    ⦿ TeraBytes(TB) - 5t or 5T
  
