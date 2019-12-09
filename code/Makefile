example1: PhysiCell
	# gets phyiscell if needed
	# then puts custom files in place as needed 
	# then compiles the example 

training-model: PhysiCell
	# gets phyiscell if needed
	# then puts custom files in place as needed 
	# then compiles the training model (without GUI)
	
# depend on something that will get populated 
PhysiCell: physicell.txt
	# call a script to download physicell 
	# once done, create a file that lets us know we already ran this
	touch physicell.txt 
	
clean:
	rm -f physicell.txt 
	# anything else 