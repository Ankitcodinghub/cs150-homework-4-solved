# cs150-homework-4-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs150-homework-4-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127979&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS150  Homework # 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
Create a class called “box” that has the following attributes (variables): length, width, height (in inches), weight (in pounds), address (1 line), city, state, zip code. These variables must be private. Create setter and getter functions for each of these variables. Also create two constructors for the box class, one

default constructor that takes no parameters and sets everything to default values, and one which takes parameters for all of the above. Create a calcShippingPrice function that returns the cost of shipping a box, using the following formula:

Shipping price for a single box = (((length + width + height) * $0.50) + (weight * $1.00))

Finally, create a print function that prints length, width, height, address, city, state, zip code and shipping price to the screen.

Main should create an array of 3 boxes. Have the user enter the information for each box, then display the information for all boxes as well as the total shipping price for all boxes combined.

You must use a class file, header file, and main file (3 files with code in them).

Show test run(s) proving that your program works.

Input validation:

Length, width, height, weight should all be positive. If negative or default constructor is used set to 0.

Address needs no input validation, but can have spaces in it (remember getline and ignore), if default constructor is used set to blank (assume all addresses are 1 line only).

City needs no input validation but can have spaces in it, if default constructor is used set to blank.

State should be exactly two characters long. If invalid or default constructor is used set to “XX” (you do NOT need to check if the state is “real”, i.e. “YZ” would be valid input even though there is no state with that abbreviation – Hint: string.length() ).

Zip code should be 5 digits and positive (no leading zeros), if invalid or default constructor is used set to 0.

Input validation should be done in your setter functions and/or constructors as needed to ensure no bad data can get in to the class variables. Invalid input should instead set the value to a default as specified above.

Your program should be split into three files, a .h file for the box class, a .cpp file for the box class, and a .cpp file for main.

Your repl must include the following:

– Your code

– Screenshot(s) of test run(s) of the program showing it being thoroughly tested.

– A flowchart and/or written algorithm showing the design of your code. Make sure nothing in your code results in junk values or causes a segmentation fault.
