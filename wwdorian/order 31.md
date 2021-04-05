---
subject: Making Interaction
login-link: https://my.griffith.edu.au/
username: s5149045
password: Zb200512
ref-style: 
requirements-1: 在 Miro board 上完成 class exercises 和 completion of at least 5 extra Micro:bit experiments
requirements-2: 准备录制 completion of the replication/transformation project 的视频需要的内容
---
link: [[GU#^7a74d2]]

---

### Transformed Temperature Gauge

#### Idea For The Temperature Gauge

The Idea of such a temperature gauge, replicated from the original and transformed for my idea, is from the experiences of the past year that was inflicted by the COVID-19 pandemic.

Cities were in lockdown all over the world, and Fear has conquered the planet, in 2020. And for safety controls, nearly every country is having test on people when passing security gates, in order to make sure that the person's body temperature falls within the "probably healthy scale", since it is proven that COVID-19-infected patients' body temperature would raise.

So, it became natural to wonder: is there a way to tell the temperature without having to test using a thermometer? After all, though being mostly accurate, it is inefficient when there is an overflow of people.

#### The Completion Process

The initial idea is to use wearable technologies, such as wearable fabrics that can function like screens of our smartphones, to show certain messages when one is going to be tested of his or her body temperature. In order to save time, it should be possible to tell time via the clothes.

The way that humans interact with the environment is quite, in some sense, brutal. We take out a tool, such as a thermometer, and test, and we get results. This interaction involves human in the process, especially at security check points. However, what if our clothes that we wear are able to tell the temperature when needed?

Then there must be a device that could retrieve information about temperature from human skin. But again, it is too brutal to be surrounded by threads and devices. In the near future where wearable technologies are possible, the clothes itself could be the input source, of temperature data. Thinking of that, I didn't add a "if-else" conditional to identify the data source, instead, I went straight to set a new variable "temperature".

The variable is in Celsius degree because I am, personally, not quite familiar with Fahrenheit. Since the variable is automatically set value when the program initiates, I went to an "if" conditional, to be sure it can product expecting results when the temperature is within the normal scale in which we are categoriesed as "normal", or "healthy". And, when a person is tested by the clothes of his or her temperatures, not only he or she may feel more comfortable, but that the convenience would be quite beneficial when there is a traffic jam. I used a "happy" face for this condition.

Then with considerations of the possible range of temperature that could be told by clothes that we wear, I excluded the range of temperature that is "healthy", and set up an "elseif" conditional to ensure that there would at least be some output on the Micro:bit screen when the temperature shows that there is something wrong, with a "sad" face.

#### The Result

The result is quite satisfying. Only when a person's body temperature is within the scale the given standard of "healthy" would there be a "smile" face on the screen. This could be applied to wearable technologies to better the efficiency of human societies, and may possibly solve the problem of people potentially getting infected since they would be able to know other people's body temperatures.


### 5 Other Micro:bit Exercises

#### Paper Scissors
This project is to create a game that could be played be implemented on micro:bit.

The idea is to:

1.  use a indexer to determine a value for "hand", a variable that is within 1 to 3.
2.  3 if-else conditionals to give a certain result on the LED.

The given results would be as in the picture below.

The system is a well functioning game, indicating the underlying principle of program: a design is to split up and find out their relations to create sequences.

#### Dice

There are 3 basic elements that will be used: detecter, picker, and shower, each of which composes one part for the program.

On shake: detecter —> Show Number: shower.

The number could be picked just right before the shower starts to work, so two of the basic elements could be blended in the program.

The outcome is given by the picker, as shown below.

However, what if we use some if-else conditionals? A dice is good, but what about more dices, if we want to play some game?

That contribute to user experiences, too, to consider different situations of the products being used.

#### Snap the Dot

It is possible that we use blocks to create such a program. But it could be concluded that this "forever" loop is within the frame work of "on start", since only when the "on start" gives "sprite" the variable with a value can the loop starts to function — it would only get a "null" if otherwise.

The underlying effect of such a program reminds of the concept of dissecting a process into its tiniest elements, and implement them each, individually. This exercise is exactly such a case.

Hooray design!

#### Light Level Meter
This program has some viable applications, I think. It is simple; the only things it requires in a light sensor.

I think of those octopus that could generate light on their skins, when carrying out this. The idea is that the process is ongoing, and there seems no end: it will always tell what a kind of light level something is on, and it would generate results of the kind. These are applicable, for example, to be used for planting crops at night — farmers would be able to know whether it is suitable for work.

#### Love Meter

This is a fast changing LED display.

I think of those it might be the display methods in which we see those skyscrapers shine at night. They are often bright, colourful, and fun. The idea behind this is to use two conditionals (though not if-else) to create different effects in different situations.