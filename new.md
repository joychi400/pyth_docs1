"""
a simple code to add two numbers
 """
def func(x, y):
	return x + y


def func2(y):
	""" a generator function to loop through range of numbers and yield result
      """	
	for i in range(y):
		yield(i)