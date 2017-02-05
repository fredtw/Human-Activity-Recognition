# Human-Activity-Recognition-

submission guidelines below assuming the UCI smartphone data set. This data set is organized in a way that makes it hard to use at first. You will need to use several data transformation techniques to put it into a usable, tidy state. Here are some extra guidelines and hints from one of our mentors if you get stuck. Discuss with your mentor if needed!

You should create one R script called run_analysis.R that does the following.

    Merges the training and the test sets to create one data set.
    Extracts columns containing mean and standard deviation for each measurement (Hint: Since some feature/column names are repeated, you may need to use the make.names() function in R)
    Creates variables called ActivityLabel and ActivityName that label all observations with the corresponding activity labels and names respectively
    From the data set in step 3, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
