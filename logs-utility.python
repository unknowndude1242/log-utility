words = []
input_directory = input("what is the file name \n=>") + ".txt" # you can replace the ".txt" by the file type that you want to open
output_file_name = input("what is the output file name \n=>") + ".txt" # same thing you could replace this for the output file extension
with open(input_directory, "r") as cuntent:
    contents = cuntent.readlines()
for line in contents:
    word = line.strip()
    if word not in words:
        words.append(word)
with open(output_file_name,"w") as writes:
    writes.write("\n".join(words))
