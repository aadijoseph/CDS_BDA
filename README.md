LINEAR SEARCH ALGORITHM

Step 1 : Start.
Step 2 : Define input_1 ( promt ) as a function.
	While user input in invalid :
except valaueError
print “Invalid datatype, Enter an integer”
	end of while
Step 3 : Get user input for number of elements in the list i.e.  ‘ x ’  by calling input_1.
	If x  <  0 :
		print  “  Number of elements cannot be negative ”
	else:
		go to step 4
	end of if
Step 4 : Initialize list1  =  [  ]
	Loop through 1 to x + 1 :
		print “  Enter the elements  “
		‘y’ contains the integer values taken by user by calling input_1
		Append ‘y’ to list1.
	End of loop.
Step 5 : Define liner_search (  list1 ,  target ) as function.
	Initialize list2  =  [  ] 
	Loop through each index of list1 :
		If list1 == target
			Append index i to list2.
			Return list2
		End of if
	End of loop
Step 6 : Call the function input_1 to get user input for the target value and store it in ‘target’
Step 7 : Call the function linear_search ( list1, target ) and store the resultant index value in ‘result’
	If result is not empty:
		print “ Target value found at”,result
	else : 
		print “ Target not found “
	end of if
Step 8 : End.



	
