# ToolsCollection
小工具收集

# Info
## splits
http://www.fourmilab.ch/splits/
splits infile [ chunksize ] 
On Unix the collection of chunks created with splits can be reassembled with cat. Simply use: 
       cat infile.* >infile
to concatenate all the chunks together into an output file identical to the original splits input file. MS-DOS users can use the: 
       COPY /B infile1+...+infilen outfile
       
## sanur
run.exe /noprofile /user:administrator 'net localgroup administrators abc /add' | sanur password
