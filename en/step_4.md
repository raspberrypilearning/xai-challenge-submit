## Make: Prototype, test, iterate

Let's look at the next steps of making your idea come to life!

1. **Prototype**: Think of this as a mini-version or a "draft" of your idea. It's like when you draw a rough sketch before making a big painting. You'll make a simple version of your project – don't worry about making it perfect! It's just so you can see how it might work in real life. You'll make an ML model, just like you did before, then link it to an awesome Scratch project your users can interact with.

2. **Test**: This is the fun part! 🚀 Try out your prototype to see how it works. Ask your friends or family to try it too; they might have some cool ideas or notice things you missed! Get feedback from your users about their experience - try the 'two ⭐s and a wish' method!

3. **Iterate**: "Iterate" just means "repeat the process, with the aim of making it better". Based on what you learnt when you and others tested your app, go back and make some changes to your prototype. Maybe you want to add something new or fix a part that didn't work right.

Remember, it's all about trying, learning, and improving. Every time you go through these steps, your idea will get better and cooler! 

Ready to give it a go? Great!

### Gather data
Before you can train your machine learning model, you need to pick a data set for your project. 

--- collapse ---
---
title: Choose a data set
---

**What is a data set?**
A data set is a big collection of information that you can use to train your machine learning model. For example, it could be a list of songs, pictures of animals, or even recordings of different sounds!

**Where can you find data sets?**
1. There are some cool websites that offer open-source data sets for free! Websites like [Kaggle](https://www.kaggle.com/datasets) or [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) have loads of them. You can search these sites for the topic you're interested in.
2. Remember in the previous stage of the challenge where you made your own data set on Machine Learning for Kids? Guess what? You can do that again! Gather your own photos, texts, or sounds and build your unique data set.

**A few things to keep in mind:**
- **Safety first!**: 🛡️ When browsing online, be careful! Some data sets might not be suitable for kids. Always ask an adult or your teacher if you're unsure about using a certain data set.
- **Clean and tidy**: 🧹 Some data sets can be like messy bedrooms. They might have missing pieces or errors. So, always check your data set and make sure it's neat and clean before using it.
- **Size matters**: 📈 Imagine trying to become a Pokémon master with only two Pokémon cards...it's tough, right? In the machine learning world, the more training data (like pictures or sounds) you have, the better your model can become! It's like having a fuller deck of cards to play with. So, while you don't need billions of pieces of data for your model, like ChatGPT, having a good-sized data set can make your model more accurate.

Time to gather your data tools and start making!

--- /collapse ---

[[[make-a-model-ml4k]]]
[[[add-training-data-ml4k]]]

### Train the model
Training an ML model is just teaching a computer by showing it many labelled examples. It learns to recognize patterns and gets better at tasks, like telling cats from dogs, as it sees more examples.

--- collapse ---
---
title: Train the model
---

**What's the trick?**  
You'll be showing your computer tons of examples from your chosen or created dataset. For instance, if you have a collection of pictures of Pokémon, you'll tell the computer which ones are Pikachu and which ones aren't.

**Practise Makes Perfect:**  
The computer will then process each picture, learning and making predictions of what the picture contains. Sometimes it'll get the prediction right, and other times it might mess up. But the more examples you give, the better it'll get at guessing correctly.

**Testing Time!**  
After training your model with lots of examples, you can then show it a new picture and see if it can correctly predict if it's a Pikachu or not. It's like a mini quiz for your computer!

**More Data, Smarter Model:**  
Just like reading more books makes you super smart, the more examples of labelled data you give to your model, the more reliable it gets!

So, grab your chosen or created dataset, and let's start training! Think of yourself as a computer coach, helping your model improve by providing lots of practice and training.

--- /collapse ---

--- collapse ---
---
title: Testing with images
---

Drag and drop an image into the link box (next to the Test with www button):

![](images/test_with_www.png)

Alternatively, you can:

+ Right-click on an image
+ Select Copy image address
+ Paste the image address into the link box

Then, click the **Test with www** button to test your model.

--- /collapse ---


--- collapse ---
---
title: Testing with Audio
---

Click the `Start listening` button to test your machine learning model.
![Image which says 'Try making a sound to see how it is recognised based on your training' with two buttons beneath. A darker blue button reading 'start listening' and a light blue button reading stop listening.](images/start_listening.png)

Say one of the words that you have trained the computer to classify. when your machine learning model processes the sound, it will show a prediction of what you said.

If you’re not happy with how the model is working, go back to the **Train** page (by clicking `back to project` and then `Train`) and add more examples to all the training buckets. Try varying your speed and pronunciation, having other people add samples in their voice... or doing funny voices yourself!

--- /collapse ---

--- collapse ---
---
title: Testing with Text
---

**Text projects need to be retrained after 24 hours:** If you are working on a text-based model, you will need to click the button to Train your model if you have left it overnight. Your training data will be kept online, but the model will time out after 24 hours. The model will need to be retrained at the start of each session.

To see how successful your model is at classifying heroes and villains, test your model by typing a quote into the field that appears.

**IMPORTANT:** Make sure you don't use a quote that already exists in your training data!

Click the **Test** button to test your model. Your model will predict whether the text you entered is heroic or villainous and will tell you the level of confidence the model has in that prediction.

![](images/test_text.png)


--- /collapse ---

### Build in Scratch
Combine the magic of Scratch with the smarts of your trained machine learning model! Turn your smart new model into a game, a helper tool, or even a fun quiz! You've trained your model, tested its accuracy, and now it's showtime! Dive into Scratch, let your creativity run wild, and build something truly amazing.

--- collapse ---
---
title: Pro tip - Save your work!
---

This special version of Scratch allows you to access your machine learning model, as well as use the music database blocks - **if you try to open your project in another version of Scratch online it won’t work**. 

A hack you can use is to save your work to your computer often:

--- task ---

First, give your program a name by typing the name of your program in the project name box at the top of the screen:

![The project name box highlighted.](images/name-annotated.png)

--- /task ---

--- task ---

To save your project, click on **File**, and then on **Save to your computer**:

![Selecting 'Save to your computer' in the 'File' menu.](images/save.png)

Your Scratch `.sb3`  file will be saved to your computer. 

--- /task ---

Once you have the .sb3 file for your project saved you can open it again later, or on another computer:
+ Go to [rpf.io/mlscratch](rpf.io/mlscratch){:target="_blank"} to get to this special fork of Scratch 
+ Once Scratch opens choose File > Load from your Computer
+ Select your file in the window that appears to get back to where you left off

![Image showing the Scratch file menu with the Load from your computer option highlighted](images/load_menu.png)

Save your work as often as you can to make sure you don’t lose any progress!

--- /collapse ---


[[[generic-scratch-backdrop-from-library]]]
[[[generic-scratch3-paint-new-backdrop]]]

[[[generic-scratch-sound-from-library]]]
[[[scratch3-record-sound]]]

[[[generic-scratch3-sprite-from-library]]]
[[[generic-scratch3-add-sprite-from-file]]]
[[[generic-scratch3-draw-sprite]]]
[[[generic-scratch3-add-costume]]]
[[[scratch3-left-right-direction]]]

[[[generic-scratch3-broadcast-message]]]
[[[scratch3-ask-answer-chat]]]
[[[scratch3-copy-code]]]
[[[scratch3-join-text]]]
[[[generic-scratch3-add-variable]]]
[[[generic-scratch3-make-list]]]

### Test and Iterate
You've designed an exciting Scratch application powered by a machine learning model. Now it's time to share it and gather some feedback to make it even better! Here's why feedback matters: think of it as someone telling you which parts of a puzzle look amazing and which pieces might fit better elsewhere.

**1. Two Stars and a Wish 🌟🌟💫:**  
This method is like getting mini-reviews!
- 🌟 **First Star:** What was super cool about your project.
- 🌟 **Second Star:** Another awesome part they enjoyed.
- 💫 **A Wish:** A friendly tip or idea for improvement.

**2. The Stoplight System 🚦:**  
Present your project and then hand out three coloured cards: Red, Yellow, and Green.
- 🟢 Green Card: Parts of your project that are good to go!
- 🟡 Yellow Card: Areas that might need a little bit of tweaking.
- 🔴 Red Card: Things that need a second look.

**3. Picture Storyboard 🖼️:**  
Give them a few blank paper panels and ask them to draw:
- Their favourite part of your application.
- A scene or part where they were a bit confused.
- Any new idea or feature they imagine would be great!

After collecting feedback, hop back into Scratch and fine-tune your project. Adjustments based on what others think can turn your great project into an amazing one! Remember, every piece of advice is a step towards perfection. Keep iterating and have fun! 🚀🎨
