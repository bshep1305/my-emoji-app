      Emoji Application

 Fun emoji program I built after learning intermediate level javascript in my bootcamp. 
 
This was right after we learned the concepts of looping through an array to be able to access each item.
Then using document.getElementById() and addEventListener to able to take control of HTML elements using Javascript.
Then displaying the items in the array we looped through, by using textContent if there are pre-existing HTML elements and 
innerHTML if there are no pre-exisiting HTML elelemts.



There are 4 buttons on the screen that the user can interact with which utlilize key javascript methods that will mutate our MyEmojis array:

"Add to end" - uses the push method to add the emoji that is in our input field named, emojiInput, to the end of an array. Uses an if statement
to check if there is an emoji in the input field (emojiInput.value). If there is not the function will not execute.

Add to beginning" - uses the unshift method to add the emoji that is in our input field named, emojiInput, to the beginning of an array.
Uses an if statement to check if there is an emoji in the input field (emojiInput.value). If there is not the function will not execute.

"Remove from End" - uses the pop method to remove the last item that is in the myEmojis array

"Remove from beginning" - uses the shift method to remove the first item that is in the myEmojis array.





