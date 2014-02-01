bread = 17
jelly = 9
peanutButter = 30

# Part 1: Determine if you can make a sandwich
#if bread >= 2 and jelly >= 1 and peanutButter >= 1:
#    print "You can make at least one sandwich."
#else:
#    print "No sandwich for you. :("





# Part 2: How many sandwiches for you?
#sandCount = 0

#while bread >= 2 and jelly >= 1 and peanutButter >= 1:
#    bread = bread - 2
#    jelly = jelly - 1
#    peanutButter = peanutButter - 1
#    sandCount = sandCount + 1

#print "You can make " + str(sandCount) + " sandwiches!"





#Part 3: U can make openface sandwich?
#sandCount = 0

#while jelly >= 1 and peanutButter >= 1:
#    if bread >= 2:
#        bread = bread - 2
#        jelly = jelly - 1
#        peanutButter = peanutButter - 1
#        sandCount = sandCount + 1

#        if bread == 0:
#            print "You have " + str(sandCount) + " full sandwiches."
#        if bread == 1 and peanutButter >= 1 and jelly >= 1:
#            print "You have " + str(sandCount) + " full sandwiches plus an openface."







#Part 4 What ingredients are missing?
#sandCount = 0
#openCount = 0

#while jelly >= 1 and peanutButter >= 1:
#	if bread >= 2:
#		bread = bread - 2
#		jelly = jelly - 1
#		peanutButter = peanutButter -1
#		sandCount = sandCount + 1
# Determines if there is enough for an openface sandwich
#	if bread == 1:
#		if peanutButter >= 1 and jelly >= 1:
#			if peanutButter > 1 and jelly > 1:
#				print "You have " + str(sandCount) + " full sandwiches plus an openface and leftover peanut butter and jelly."
#				openCount = 1
#			if peanutButter == 1 and jelly > 1:
#				print "You have " + str(sandCount) + " full sandwiches plus an openface and leftover jelly."
#				openCount = 1
#			if peanutButter > 1 and jelly == 1:
#				print "You have " + str(sandCount) + " full sandwiches plus an openface and leftover peanutButter."
#		if peanutButter >= 1 and jelly < 1:
#			print "You have " + str(sandCount) + " full sandwiches but lack jelly for an openface."
#		if jelly >= 1 and peanutButter < 1:
#			print "You have " + str(sandCount) + " full sandwiches but lack peanut butter for an openface."
#		break
#		if jelly < 1 and peanutButter < 1: << THIS IS PROBLEM WITH ONLY BREAD. Because like, what if I have a ton of bread?
#			print "You only have bread and need PB&J, poor bugger. But you have " + str(sandCount) + " full sandwiches."
#	if bread == 0:
#		if peanutButter == 0 and jelly == 0:
#			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and no leftovers."
#		if peanutButter >= 1 and jelly >= 1:
#			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and leftover peanut butter and jelly."
#		if peanutButter >= 1 and jelly < 1:
#			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and leftover peanut butter."
#		if peanutButter < 1 and jelly >= 1:
#			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and leftover jelly."
#		break
#
#if peanutButter == 0 or jelly == 0 and bread >= 1:
#	if peanutButter >= 1:
#		print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches, " + str(bread) + " leftover bread slices and " + str(peanutButter) + " leftover peanutButter."
#	if jelly >= 1: 
#		print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches, " + str(bread) + " leftover bread slices and " + str(jelly) + " leftover jelly."
#	else:
#		print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches, " + str(bread) + " leftover bread slices."





#Part 5: Have program make judgy statements about your eating habits. 
sandCount = 0
openCount = 0

while jelly >= 1 and peanutButter >= 1:
	if bread >= 2:
		bread = bread - 2
		jelly = jelly - 1
		peanutButter = peanutButter -1
		sandCount = sandCount + 1
# Determines if there is enough for an openface sandwich
	if bread == 1:
		if peanutButter >= 1 and jelly >= 1:
			if peanutButter > 1 and jelly > 1:
				print "You have " + str(sandCount) + " full sandwiches plus an openface and leftover peanut butter and jelly."
				openCount = 1
			if peanutButter == 1 and jelly > 1:
				print "You have " + str(sandCount) + " full sandwiches plus an openface and leftover jelly."
				openCount = 1
			if peanutButter > 1 and jelly == 1:
				print "You have " + str(sandCount) + " full sandwiches plus an openface and leftover peanutButter."
# Taking the next couple of lines out because they ended up being redundant with the leftovers count.
#		if peanutButter >= 1 and jelly < 1:
#			print "You have " + str(sandCount) + " full sandwiches but lack jelly for an openface."
#		if jelly >= 1 and peanutButter < 1:
#			print "You have " + str(sandCount) + " full sandwiches but lack peanut butter for an openface."
		break


	if bread == 0:
		if peanutButter == 0 and jelly == 0:
			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and no leftovers."
		if peanutButter >= 1 and jelly >= 1:
			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and leftover peanut butter and jelly."
		if peanutButter >= 1 and jelly < 1:
			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and leftover peanut butter."
		if peanutButter < 1 and jelly >= 1:
			print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches and leftover jelly."
		break

#new bit for part 5 basically requires the while loop to break because you ran out of jelly.
if peanutButter >= 1 and bread >= 2:
	print "You have " + str(sandCount) + " full sandwiches and can make a peanut butter and no jelly sandwich, but maybe you shouldn't. Got any bananas?"

if peanutButter == 0 or jelly == 0 and bread >= 1:
	if peanutButter >= 1 and bread == 1:
		print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches, " + str(bread) + " leftover bread slices and " + str(peanutButter) + " leftover peanutButter."
	if jelly >= 1: 
		print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches, " + str(bread) + " leftover bread slices and " + str(jelly) + " leftover jelly."
	if peanutButter == 0 and jelly == 0:
		print "You have " + str(sandCount) + " full sandwiches, " + str(openCount) + " openface sandwiches, " + str(bread) + " leftover bread slices."
