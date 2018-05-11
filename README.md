# Lyrics

This is the repository for CS410 course project - peiyaol2, pj2, xinyigu2

Our main goal is to do topic modeling on the lyrics database given some specific query input.

## Getting started
Important: please log onto google drive with your illinois account and [download our database](https://drive.google.com/file/d/1g8SArnDU4XOSbdUIZvQ1-glQ5cJnFOlF/view?usp=sharing), then put the unzipped csv file in the program directory.

Please also read through the [installing packages section below](https://github.com/peiyaoli2/Lyrics#installing-packages) before running our program.

To run our program, navigate to the project directory and run
```
python lyrics.py <filter_type> <filter_name> <topic_count>
```

### Meaning of parameters
#### filter_type
is the type of filter you want to search for. There are three valid arguments for this parameter: artist, genre or year.

#### filter_name
is either the name of the artist, the name of the genre or the name of the year you want to search for.
For a complete list of valid arguments, please look at
```
valid_artist.txt valid_genre.txt valid_year.txt
```

#### topic_count
is the number of topic you want to search for.
  
### Example runs
For example, to search for backstreet boys for 5 topics, you can run our program with
```
python lyrics.py artist backstreet-boys 5
```

To search for the pop genre with 10 topics, you can run our program with
```
python lyrics.py genre Pop 10
```

To search for year 2008 with 8 topics, you can run our program with
```
python lyrics.py year 2008 8
```

### Interpreting the output
Upon completion of the program, several output will appear inside the program directory.
#### top 20 words
This is the list of the top 20 words ranked by the frequency of appearance with your input parameter. It appears as a .txt file.
#### topic list
This is the list of topics of your specified count. It appears as a .txt file.
#### word distribution for each topic
These are several images demonstrating the word distribution of each topic in the topic list. The amount of images varies base on your input topic_count. They appear as .png files.

## Installing packages
Our program is heavily based on other packages, and here are a few packages that should be installed before running the program:
* [pandas](https://pandas.pydata.org/pandas-docs/stable/install.html)
* [numpy](https://docs.scipy.org/doc/numpy-1.14.0/user/install.html)
* [metapy](https://github.com/meta-toolkit/metapy)
* [scikit-learn](http://scikit-learn.org/stable/install.html)
* [matplotlib](https://matplotlib.org/users/installing.html)

## Implementation

## Contributors

## Resources
