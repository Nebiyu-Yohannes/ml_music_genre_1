# ml_music_genre_1
This is a machine learning implementation that predicts the music genre of people based on their age. More information one the README file. 


WE IMPORTED A MUSIC DATA THAT HAS 3 COLUMNS OF 'AGE', 'MUSIC-GENRE', AND 'SEX'. IT HAS AN ENTRY OF 17 ROWS. 

We imported the pandas library. 
We importred the sklearn library and from it the class DecisionTreeClassifer, the train_test_split function and the accuracy_Score function.

                - FIRST WE Read/LOAD THE DATA USING THE PANDAS LIBRAY TO A VARIABLE.
                
                - THEN WE DEFINE AN INSTANCE /OBJECT/ OF THE DecisionTreeClassifier. THIS OBJECT IS OUR MODEL.
                
                - THEN WE DEFINE WHICH THE INPUT AND OUTPUT DATA SETS WILL BE FROM THE LOADED DATA.
                
                - THEN WE USE THE train_test_split FUNCTION TO SLPIT THE TRAINING AND TESTING DATA.
                         WE ALSO SPECIFY A PARAMETER CALLED test_size THAT WE USE TO DEFINE THE TRAINING AND TESTING DATA SIZE /0 - 1/.
                            // THIS FUNCTION RETURNS A TUPPLE OF FOUR ITEMS; both the input and output data-set is slpit into training and testing data.
                            
                - THEN WE TRAIN THE MODEL USING THE TRAINING INPUT DATA AND TESTING INPUT DATA.
                    WE CAN SAVE THIS TRAINED MODEL BY USING THE JOBLIB CLASS AND METHOD 'dump,' and save it as a '.joblib' file.
                    we CAN LOAD THIS MODEL ANYTIME BY USING THE JOBLIB CLASS AND METHOD 'load'.
                    
                - FINALLY WE CAN MAKE PREDICTIONS ON THE INPUT TEST DATA BASED ON OUR TRAINED MODEL AND PLACE IT ON A VARIABLE.
                
                - WE CAN ALSO CHECK ACCURACY OF THE PRDICTION. WE DO THIS BY USING THE accuracy_score FUNCTION. THIS FUNCTION RETURNS A FLOAT FROM (0.0 - 1.0)
                    THE PARAMETERS OF THE FUNCTION ARE THE OUTPUT TEST DATA AND PREDICTION
