There are a few points to note before running the notebook.

- I am using python3 on Jupyter notebook. If you happen to be using python2, make the corresponding changes before running the notebook.

- We can get the tag of each email in the function 'msg-sub-and-tag-of-email'. So to get the tag, we can see which folder the file is in, Ham or Spam.
  As the data is classified as ham or spam, this wouldn't be a difficult task. However, make sure that the number of folders that you have to open from /home/
  to be 7. If not change the value, number-of-folders-to-be-opened. If this is not checked, every email is tagged 0. Make sure (tags == 0).sum() not equal to 
  leng(tags).

- Make sure the following libraries are installed:
	1. numpy.
	2. lxml.
	3. bs4. (BeautifulSoup)
	4. sklearn.
  I guess rest of the libraries come preinstalled with python3

- I guess I have covered the remainig details in the notebook. Have fun classifying!!
