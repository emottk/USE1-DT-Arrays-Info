#>>ARRAYS

Let's say you're a teacher, and you're trying create a program to keep track of your students grades.		

First things first, we'll need to collect their names. We've learned how to store things in Ruby using variables, so let's try that.

	student1 = "Rebecca"
	student2 = "Eamond"
	student3 = "Cynthia"
	student4 = "Peter"
	student5 = "Katherine"
	...

So we're starting to realize that maybe this isn't the most efficient way to store our students. We're going to write so many different variables, and calling them all is going to be a nightmare.		

Enter: Arrays.		

An array is another datatype, just like a string or an integer/float. It is a collection of similar types of data, indexed for easy use.		

An array looks like this:

	array = [data1, data2, data3]

This creates an array called `array` that is holding `data1`, `data2`, and `data3` inside of it. We can have arrays that hold strings, or integers, or really any datatype we'd like:

	strings = ["string1", "string2", "string3"]
	
	numbers = [1, 2, 3, 4, 5,]
	
	
The brackets are what let Ruby know that we want this data to be held within an array. Now we can group together any similar data for easy use! Let's try it with our students.

	students = ["Rebecca", "Eamond", "Cynthia", "Peter", "Katherine"]

Awesome! Now our next question is, how do we access this data? 		
Above we said that arrays are **indexed** - what does this mean? It means that each piece of data has an index, or number, associated with it.		
One thing to keep in mind - the index starts at 0, not 1. That's right:

	index >>	   0          1          2          3
	strings = ["string1", "string2", "string3", "string4"]

It seems a bit weird, but it's something we'll get used to as we use arrays more and more. 		
Back to our students array - let's say we want to pull up "Eamond", how do we do this using our index?

	students = ["Rebecca", "Eamond", "Cynthia", "Peter", "Katherine"]
	print students[1]
		>> "Eamond"
We write the name of the array, followed directly by two brackets with our index number inside. As we see above, `"Eamond"` is at index 1, so when we call `students[1]`, `"Eamond"` is what is returned.

Take a guess at what these will return!

	students[0]
	students[3]
	students[5]


