# w1ex4
#Exercise 4  Write a Ruby program that tells you how many minutes there are in a year (do not bother right now about leap years etc.).
#1 year = 365 days = 365*24hours = 365*24*60 minutes
def minutes_in_a_year
#       year*day*minutes
	puts 'There are ' + (364*24*60).to_s + ' minutes in a year.'
end	

minutes_in_a_year
