import os,sys;


filetoread=open(sys.argv[1]);
filetowrite=open(sys.argv[1]+"-mod","w");

for	line	in	filetoread:
	linesvalue=line.split(" ");
	filetowrite.write(linesvalue[0]+"\t"+linesvalue[1]);


