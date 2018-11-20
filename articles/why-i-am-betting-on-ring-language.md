Why I'm betting on Ring?

Here's my honest list of things that I bet Ring is gonna make a huge impact in terms of modern computing as a general purpose language. Ring pretty much support most of the philosophies that I stand for. Here are few. 

### 1 based array index:

Any language that has 1-based array index gets right. That's right, I said it a aloud. While mathematicians have always stood for natural numbers start with 1, due to the widespread 0 based arrays there rising a new set of [modern mathematicians](https://www.mathsisfun.com/whole-numbers.htm) who start to define naturals numbers start with 0. 

There are even studies who have confirmed that zero-based programming have resulted in mental issues for many people. While imaging arrays elements distance from the base pointer, it might make sense to language like assembly. Even Dennis Ritchie had a great chance of abstracting such a manipulation at compilation level (Where the compiler could offs by 1 while generating machine code). And then C++, Java, Python, Ruby now in 2018 JavaScript they all didn't dare to get rid of such baggage). Thanks to languages like Lua, Julia & Ring. 

### Dynamically typed:
	
Here's my strong opinion. Types are heavily overrated. I don't deny that types exist. But types must be for humans, not for machines. Here are valid types. `email` `url` `date` `datetime` `number` `string` `geolocation` etc. However `int` `smallint` `unsigned int` they are all for machines. A programmer should never keep low levels types in mind. So dynamically typed language is the way to go. 

What makes Ring special is, it's weakly typed. Python should have no reason to complain about this statement  `I'm + 24 + years old`. Isn't it obvious that `24` must be promoted to `string` as typecasting just like integers are upgraded to float if needed. 

### Case in-sensitive:
While case sensitivity isn't an issue for me, a lower case language would be a good choice. Personally my taste is having lower cased variable names and class names. `head_count` is visually more pleasing than `headCount`

### Whitespace Free (Easy Reformatting):
While Ring might look like Python, it's amazingly written where combining the entire program into single line will still work just fine. How Fayed managed to develop such a parser is still a mystery. 

This is important because editors rely on for auto-formatting. Try messing up some Python code up with tabs & spaces, send it in instant messenger and copy back and your code is gone. While languages like C, Java & Ring can just be pasted and transported freely and can be brought to reformatted code by editors with a single click. 

### No GIL (Easy Multi-threading)
This is a huge deal breaker. Coming from Python background, we have `Thread` `Multiprocessin``ThreadPool` `Future` at last `async & await`. So Python end up being there are multiple ways of doing same thing.  That's basically against the [Python's philosophy.](https://zen-of-python.info) 

Ring is so early and has more time & room to grow. Let's wait. Feel free to bring your massive contribution to this amazing community. 