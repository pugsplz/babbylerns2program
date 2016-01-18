# babbylerns2program
im learning java and bad, help.

I don't know how to use git but I guess I'll just post things in readme formats lol so bad sorry


/*jshint multistr:true */
var text = "some text Rachel am i doing this right Rachel oh god idk what to do Rachel okay that's it";
var myName = "Rachel";
var hits = [];
for (i = 0; i <= text.length; i++)
    {
        if (text[i] === "R")
        {
            for(var i = 1; i < (myName.length + 1);)
                {
                    hits.push(text[i]);
                }
        }
    };
if (hits.length === 0)
    {
        console.log("Your name wasn't found!");
    }
else
    {
        console.log(hits);
    };



when i run this, it crashes my browser. it's asking me to do this:
Log it!
Perfect! You've now got the engine of your search program running. It will:

Loop through the array,
Compare each letter to the first letter of your name, and if it sees that letter:
It will push that letter and all the letters that follow it to an array, stopping when the number of letters it pushes are equal to the number of letters in your name.
Instructions
Under your existing code (and outside all your loops!), set up an if/else statement. If you don't have any hits, log "Your name wasn't found!" to the console. Otherwise, log the hits array to the console.
halp
