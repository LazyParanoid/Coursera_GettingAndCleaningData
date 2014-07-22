README
========

About This Repository
---------

This repositary is a course project for Coursera online course: [Getting and Cleaning Data] [1]. This project uses the [Human Activity Recognition Using Smartphones Data Set] [2] from UCI Machine Learning Repository. This dataset is originally collected in [this study][2.5]. The programming language used in this repository is [R] [2.2]. The author is [Zhixuan Wang] [3]. If you have any comments or advice, please feel free to contact [the author] [4] directly.



Files
--------

### tidy_data.txt
The cleaned dataset requested by the course project, containing 10299 observations of 68 variables. The column names are very long so the best way to read the data is probably to read it in R with the following command:

```sh
data <- read.csv("tidy_data.txt", header=TRUE, sep="\t")
```

It may be a little confusing that I did not save it as a csv file directly. The reason is that txt files are supported as an attachment on Coursera but csv files are not.


### run_analysis.R
The R script requested by the course project. Assuming you have the dataset downloaded and unzipped in your working directory, you can get the tidy data output (*tidy_data.txt*) once you run this script in R.


### Codebook.md
A text file that described what does the data in *tidy_data.txt* mean in detail.  

Notes
-------
I would like to thank out community TA [David Hood][6] (and other TAs also) for their quick and detailed response to our questions on the coursera forum. 





[1]:https://class.coursera.org/getdata-005/human_grading
[2]:http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
[2.2]:http://www.r-project.org/
[2.5]:http://link.springer.com/chapter/10.1007%2F978-3-642-35395-6_30
[3]:https://github.com/LazyParanoid
[4]:moonknight.pku@gmail.com
[6]:https://www.coursera.org/user/i/ec68f3d18579236cd3fa22ce33c35cc2