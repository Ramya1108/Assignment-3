Name <- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Berine")
ABCpoliticalpollresults <- c(4, 62, 51, 21, 2, 14, 15)
CBSpoliticalpollresults <- c(12, 75, 43, 19, 1, 21, 19) 
results.df <- data.frame(Name,ABCpoliticalpollresults,CBSpoliticalpollresults)

EXPLANATION
In first line, a vector named Name is created, containing the names of political candidates. The c() function is used to concatenate the strings into a vector.
In second line creates a vector named ABCpoliticalpollresults, which contains the polling results for each candidate from the ABC political poll.
Similar to the second line, this one creates a vector named CBSpoliticalpollresults, containing the polling results for each candidate from the CBS political poll.
Here, a dataframe named results.df is created using the data.frame() function. This dataframe has three columns: Name, ABCpoliticalpollresults, and CBSpoliticalpollresults. Each column contains the respective data vectors created earlier.
So, the results.df dataframe organizes the political polling data into a tabular format, where each row represents a candidate, and the columns represent their polling results from the ABC and CBS polls.
	
Name	ABCpoliticalpollresults	CBSpoliticalpollresults
			
1	Jeb            	4                	12
2	Donald	        62	              75
3	Ted	            51              	43
4	Marco	          21              	19
5	Carly	           2	              1
6	Hillary	         14	              21
7	Berine	         15	              19


