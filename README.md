first of all we have to select all the paragraph <p> tags from the page and print their total count.
for this task we have three different methods to select multiple elements.

first we use document.querySelectorAll("p") to select all the <p> tags from the page.
this method returns a nodelist containing all the matching paragraph elements.
after selecting the paragraphs, we use the .length property to find the total number of selected elements.
finally we print the count using console.log.

in the second method we use document.getElementsByTagName("p").
this method selects all elements that have the <p> tag.
after selecting the elements, we use .length to count the total paragraphs.
finally we print the count using console.log.

in the third method we use document.getElementsByClassName().
first we give the paragraph elements a common class.
then we use getElementsByClassName("paragraph") to select all elements that have this class.
after that we use .length to find the total number of selected elements.
finally we print the count using console.log.
