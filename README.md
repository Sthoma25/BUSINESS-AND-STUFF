BUSINESS-AND-STUFF
==================
def write_it():
    outfile = open("helo.txt", 'w')
    thing = input("Type some shit: ")
    outfile.write(thing)
    outfile.close()
