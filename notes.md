### YAML
----------------------------------------
Yet another Markup Language  (earlier name)

yaml ain't a markup language. name right now

 	markup language what exactly is markup language?-  
    	yk html? what is html doing?
     		- > it's providing child parent relationship
     		basically yaml is data format it is used to exchange data .
     		similar to xml and json(JavaScript Object Notation) data types.
     		in yaml you can store only data but not commands.

       
    > see what yaml does is  Data serialization : serialization is a process of converting data objects into a complex data structure.

        serialization    : OBJECT    ------>   STREAM/FILE
        DE serialization : stream     ------>  STREAM/FILE




      >  Object is  basically a data storage unit a combination of code + data.

    
### So Yaml is a language used to represent object in those files .Yaml is data serialization language.
### Yaml is not a markup language bcz markup languages stores documents but with yaml you can store data too.

    > Yaml is used in configuration files, docker, logs,caches.

   ->Benifits
    		Yaml is human readable.
   			Simple and easy to read.
   			Indentation is important
   			Easily Convertable to json/xml.
   			More Powerful when representing complex data.

     ### Yaml is case sensitive 
      Apple and apple are two different things in yaml files.
      


   ###  [head out here](http://www.yamllint.com/) to run files. checks if indentation is right.

          #lists
				-apple
				-mango
				-bananana



			            //this is blog style so we have cities and inside it we have a list 
			cities:

				-new delhi
				-mumbai
				-pune
				-gujrat
				-bangalore.

    
         data types in yaml:

         1.string : must be used 

         either you do : or |

         eg :  aim : learn yaml /    aim: |
                                      learn yaml
                                      this is just another sort of example
                                      yeah i did it again :D

        

        ### Writing a single line in multiple lines
             using >
             message: >
             this will 
             all be 
             in one single line 


             #same as
             message: this will all be in one single line 



        ### Specifying Data Type.

        zero: !!int 0
        positiveNum: !!int 45
        negativeNum: !!int -45
        binaryNum: !!int 0b11001
        octalNum: !!int 0x45
        commaValue: int!! +540_000 # 540,000


        ### Floating point numbers
        marks: !!float 56.89
        infinite: !!float .inf


        # null 
        surname: !!null Null # or null Null
        
