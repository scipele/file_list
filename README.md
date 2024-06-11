# file_list
Purpose:  Create a list of files in a user input path (recursively) to a csv file, with SHA-1 Hash
          Skips files that are locked for reading to avoid errors in listing          

Outfile:
   - csv text file ("|" delimeter) 
  - Fields:   row|parent_path|file_name|file_Size|sha1_hash|date_time|count(placeholder)   

Notes:
     Hash Code:  Generated using NSA SHA-1_hashing algorithmn created based on the binary content of the file
                 therfore if files have the exact same content they will have the same has code regardless of the file name
