# Writing and Running Programs

<img src="https://media.pitchfork.com/photos/5c37770817eefc510f1b3565/16:9/w_1280,c_limit/David-Bowie.jpg" width="500px" />

*David Bowie using a computer, ca. 1994*

## Overview

The following questions will let you practice writing and running some small programs. Use the trinket online environment, the `print` statement, strings and arithmetic.

You can put all of the questions in the same file, one after another. Put a comment (using the `#` sign) before each question with its title and short description.


### McChocolate Potatoes

The Japanese yen currently trades for about $.0064.

I'm a sucker for regional fast food items. It turns out that you ~can~ could get **chocolate fries** at [McDonald's in Japan](https://www.eater.com/2016/1/19/10790586/mcdonalds-chocolate-fries-japan) (they are officially known
as "McChocolate Potatoes"). Are they any good? Maybe not, but they cost only 330 yen as a side item.

<img src="https://cdn.vox-cdn.com/thumbor/WMJG04bu5nCmDiQ5mh0_chXelTY=/247x0:787x405/1820x1213/filters:focal(247x0:787x405):format(webp)/cdn.vox-cdn.com/uploads/chorus_image/image/48592139/McDonald_s_Chocolate_Fries.0.0.jpg" width="300px" />

What is the cost of a side of chocolate fries in dollars? Tip: You only need to write one line that uses a `print` statement to display the result of the calculation.
```
# Cost of a side of chocolate fries in dollars
print(330 * .0064)
```

### Haiku

<img src="https://upload.wikimedia.org/wikipedia/commons/b/bd/Kobayashi_Issa-Portrait.jpg" width="150px" />

Write a program to print the following haiku by the poet Kobayashi Issa, famous for his works focusing on insects and other small creatures.

```
O snail
Climb Mount Fuji,
But slowly, slowly!
```

Use three print statements, one for each line.


### Pool Party

<img src="https://twistedsifter.files.wordpress.com/2012/05/san-alfonso-del-mar-aerial-satellite-from-above-algarrobo-chile-5.jpg" width="300px" />


I love problems that ask you to convert normal units into ridiculous units.

The world's largest swimming pool is at the San Alfonso del Mar resort in Chile. It measures 3323 feet long, covers 20 acres, and contains about 66 million US gallons of water.

A **firkin** is an old unit sometimes used to measure beer and ale in Britain. The British Imperial beer firkin is defined to be equal to 10.8 US gallons. 
Suppose we wanted to fill the San Alfonso del Mar pool with beer, ***because reasons***. How many firkins of beer would be required to accomplish this feat?
Write a program to calculate and print the answer.

Tips:

- To enter 66 million into a program, use `66000000`. Python doesn't want commas in large numbers.
- You have a number of gallons and need to convert to firkins. In this case, you need to **divide** 66 million by 10.8. Use `/` for the division operator.

### Smoots

<img src="https://news.mit.edu/sites/default/files/styles/news_article__image_gallery/public/images/200809/20120822153620-1_0.jpg?itok=ojv_RcSG" width="300px" />

Use all of your powers to answer the following question.

Oliver R. Smoot is an MIT graduate and former head of the American National Standards Institute (ANSI) and the International Organization for Standards (ISO). In 1958, as part of his initiation into ΛXA, Smoot and his brothers measured the entire length of Harvard Bridge over the Charles River in Cambridge, MA, using Smoot’s body as the ruler. He was at the time 170 cm tall (5 feet, 7 inches), and the bridge was declared to be 364.4 Smoots, "plus or minus one ear" (about 2035 feet or 650.7 meters). Since that time, the measurement of Harvard Bridge has always been denominated in Smoots, with the markings repainted each year by the incoming ΛXA pledge class at MIT. The Cambridge police use the Smoot markings to identify the location of accidents on the bridge.

The Lake Pontchartrain Causeway, which connects Metairie, a suburb of New Orleans, to Mandeville, LA, is 23.83 miles long. It holds the record for being the longest continuous bridge over water (there are longer bridges, but they are not built in one continuous span).

What is the length of the Lake Pontchartrain Causeway in Smoots?

Tips:

- Do the entire calculation in one expression. Use a multiplication to get the number of feet, then divide by 5.5833 to get units of Smoots.
- One Smoot is about 5.5833 feet and there are 5280 feet in a mile.


### Beards

<img src="https://upload.wikimedia.org/wikipedia/commons/8/81/Hans_Langseth.jpg" width="300px" />

The beard-second is an incredibly scientific unit of length defined as the distance an average beard grows in 1 second. Google defines the beard-second as 5 nanometers and will perform conversions between beard-seconds and other lengths (try typing “1 foot in beard-seconds” into Google). Using this definition, it would take an average beard 58.8 days to grow 1 inch.

The longest beard in the world is 17 feet long and is housed in the Smithsonian institution. In life, it belonged to Hans Langseth, who immigrated to the U.S. from Norway in 1864; he died in North Dakota in 1927. He would wrap his beard around a corncob and carry it in his pocket.


Under the (completely unrealistic) assumption that Hans Langseth grew his entire beard at the average rate of 1 inch every 58.8 days, how many days would it have taken to him to get 17 feet of facial hair? Write a Python program that **calculates and prints** the answer.


### 1 Barnum = 1 Sucker / Minute

<img src="https://petapixel.com/assets/uploads/2022/01/jonathan-the-190-year-old-tortoise-with-1886-photo.jpg" width="300px" />

P.T. Barnum was a 19th Century showman, promoter, and politician, founder of the Barnum and Bailey Circus. He’s credited with coining the saying, “There’s a sucker born every minute,” although there’s no evidence he actually said this.

Jonathan the tortoise is the oldest known living terrestrial animal. He was hatched in the Seychelles, then transported to the island of Saint Helena in the South Atlantic Ocean in 1882, where he still resides. Measurements show that he was at least 50 years old when he arrived on Saint Helena, so he must have hatched no later than 1832, giving him an estimated age of over 190 years old.

If Barnum’s alleged saying is true, how many suckers have been born during Jonathan’s life? Let’s assume that Jonathan is exactly 190 years old and that each year has 365 days (ignoring leap years). Write a Python program that calculates and prints the answer


### That's So Raven

<img src="https://upload.wikimedia.org/wikipedia/commons/6/62/Paul_Gustave_Dore_Raven14.jpg" width="300px" />

*Illustration by Gustave Doré (1884)*

Python quotes can be delimited using either double quotes, `" "`, or single quotes, `' '`. What if you want to put a literal quote inside a string? There are two ways.

First, you can use single quotes to mark the outside of the string, and use double quotes inside it, or vice-versa, depending on what kind of quote you need. For example,
```
print('Quoth the Raven "Nevermore."')
```
A second approach is to use a special character sequence, `\"`. When Python encounters the `\"` sequence in a string, it will replace it with the regular double quote, `"`.

Think of the `\` as being an "escape" character: it indicates that the following quote character should be treated differently from a regular double quote used to mark the end of a string. For example, the print statement
```
print("Quoth the Raven \"Nevermore.\"")
```
will print
```
Quoth the Raven "Nevermore."
```

Use five print statements and `\"` characters to print the *The Raven* as a limerick:
```
There once was a girl named Lenore
And a bird, and a bust, and a door
And a guy with depression
And a whole lot of questions
And the bird always says "Nevermore"
```
