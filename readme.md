# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) ListViews and ListAdapters - MadLibs Android pt. 2

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

In this lab, you will be building a ListView that shows your collection of MadLibs from the last lab. The activity will have buttons to sort the madlibs by genre, number of words, and number of choosable spaces. Each sort will have a different layout for the list item, making the sorted category first on the list item.

## Exercise

#### Requirements

- Make 3 or more madlibs to add to the madlib from the previous lab (so minimum of 4 in total)
- Make a ListView display sorted madlibs
- Show genre, number of words, and choosable spaces for each list item
- On launch, the book shelf must be sorted by genre
- Allow the user to sort by genre, number of words, or choosable spaces
- Program should function as the previous lab when a mablib is chosen

**Bonus:**
- Allow madlibs to be added to the listview
- Make the computer read the madlib aloud when a button is clicked
- Make the computer's voice customizeable so the user can listen to his/her madlib spoken in different ways

#### Starter code

The `starter-code` folder contains an Android project with the following:

- A completed sample app
- An example of how to use a custom comparator in the ExampleComparator.java file

#### Deliverable

The three screenshots below show each sort being used on the list.

<p align="center">
  <img src="./Screen%20Shot%202016-07-07%20at%2011.55.08%20AM.png" width="200">
</p>

## Additional Resources

- [Java Listview](http://docs.oracle.com/javase/tutorial/uiswing/components/list.html)
- [Jave ListAdapters](https://developer.android.com/reference/android/widget/ListAdapter.html)
