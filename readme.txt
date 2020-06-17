Vivian Ellis and William Tadlock
June 13, 2019
CSCD 567 Final Project

Included Documents:

	PowerPoint) During the inclass demo our group did not get a chance to show our powerpoint.
	AWS Comprehend docx) This document describes all the information that Comprehend provides 
				and code samples on how to use AWS Comprehend with Java, we put this
				document together referencing the AWS API.
	project folder) This contains the source code to run the program and the .txt file with
			all the Amazon AAA battery reviews. Note that I hard coded client credentials. 
			Currently detecting sentiment is under construction, the detect entities will 
			work and print results to the screen and detect key phrases will upload the 
			results as a .txt file to the specified s3 bucket.

			To run the code create a folder under the root bucket named "project" and change
			the credentials on line 227...
				static AWSCredentials credentials = new BasicAWSCredentials()
			to your own credentials. then run the program and you will be given two options, 
			detect entities or detect key phrases else end the program.
	keyPhrasesOutput txt) This is the txt file that is generated in the s3 bucket with the output 
				of all the reviews key phrases.
	keyPhrasesRun png) This is a screenshot of the program running option 3, detect key phrases. This
				shows the creation of the above document, keyPhrasesOutput.txt and the snippit
				of code that is extracting the key phrases text.

Documents NOT Included:
	Two page project proposal/ write-up. This was turned in at an earlier date by William Tadlock. This
	document describes the future work (where this project is headed) and gives a purpose as to why we chose
	to extract the key phrases and entities.
	

	