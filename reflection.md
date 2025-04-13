# Reflection

Student Name:  Jackson Rosenthal
Sudent Email:  jrosen27@syr.edu

## Instructions

Reflection is a key activity of learning. It helps you build a strong metacognition, or "understanding of your own learning." A good learner not only "knows what they know", but they "know what they don't know", too. Learning to reflect takes practice, but if your goal is to become a self-directed learner where you can teach yourself things, reflection is imperative.

- Now that you've completed the assignment, share your throughts. What did you learn? What confuses you? Where did you struggle? Where might you need more practice?
- A good reflection is: **specific as possible**,  **uses the terminology of the problem domain** (what was learned in class / through readings), and **is actionable** (you can pursue next steps, or be aided in the pursuit). That last part is what will make you a self-directed learner.
- Flex your recall muscles. You might have to review class notes / assigned readings to write your reflection and get the terminology correct.
- Your reflection is for **you**. Yes I make you write them and I read them, but you are merely practicing to become a better self-directed learner. If you read your reflection 1 week later, does what you wrote advance your learning?

Examples:

- **Poor Reflection:**  "I don't understand loops."   
**Better Reflection:** "I don't undersand how the while loop exits."   
**Best Reflection:** "I struggle writing the proper exit conditions on a while loop." It's actionable: You can practice this, google it, ask Chat GPT to explain it, etc. 
-  **Poor Reflection** "I learned loops."   
**Better Reflection** "I learned how to write while loops and their difference from for loops."   
**Best Reflection** "I learned when to use while vs for loops. While loops are for sentiel-controlled values (waiting for a condition to occur), vs for loops are for iterating over collections of fixed values."

`--- Reflection Below This Line ---`
In this assignment, we were asked to work with apis from the web, and with those apis, we were asked to create functions to be able to use them more easily. The functions we were using required headers, the data we wanted from those apis, the URL, and our API key to work them, through which we then had to deserialize the data and make it into a json. After that, we were asked to make a long code that was expected to give us the entity sentiments of the reviews of a given google location, so we could judge them. To do this, we had to go through a long process of creating 3 more new functions, use the functions we had previously created to work with the apis and shorten the workload required in the long form functions, and in the long form functions, we were asked to rename columns, create caches, confirm that each row in the original dataset was copied into the new dataframe we were creating called entities_df.
For me, I personally found the original functions easy in the apicalls file, because it was mostly a repetitive process of taking an api url, copying it in, copying the headers and params from previous functions we had made, then posting or getting the url, raising it for status to check for errors, and in the end returning it as a json file to use later. The larger functions were similar in this manner, that you just had to get the information, append it to the new dataframe, and at the end, return it for use at the end to test the created code. The for loops and if/else loops are ones that I have worked with plenty by now to where they are not a problem for me. 

