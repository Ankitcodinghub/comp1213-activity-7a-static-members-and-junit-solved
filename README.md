# comp1213-activity-7a-static-members-and-junit-solved
**TO GET THIS SOLUTION VISIT:** [COMP1213 Activity 7A-Static Members and JUnit Solved](https://www.ankitcodinghub.com/product/comp1213-activity-7a-static-members-and-junit-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95513&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP1213 Activity 7A-Static Members and JUnit Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Activity: Static Members and JUnit

</div>
</div>
<div class="layoutArea">
<div class="column">
Goals:

By the end of this activity you should be able to do the following: Ø Understand and implement static variables and methods Ø Be able to create, compile, and run a JUnit test file

Description:

For this assignment, you will need to download BankLoan.java from the course website and save it to an appropriate folder.

Directions:

Don’t forget to add your Javadoc comments for your classes, constructor, and methods in this activity.

Part 1: Static methods

• You don’t have to read this bullet now, but make sure that you understand it before this week’s quiz and project. Three of the properties of static methods:

o Static methods can be invoked using the name of the class.

o Static methods can be invoked before an object of the class is instantiated.

o Static methods cannot access instance data. This is because the method can be called

before an object is created, which means no instance data would exist. Consider the following examples:

<ul>
<li>§ &nbsp;The trim method of the String class is an instance method. You must create a String object before you call the method so that the method knows what to trim:
String s = ” Red Sox”; System.out.println(s.trim()); Red Sox
</li>
<li>§ &nbsp;The pow method of the Math class has parameters for the values it needs so it
is defined as static. This means that you don’t have to go through the

additional step of creating a Math object before you use the method:

System.out.println(Math.pow(2, 3));

8.0

If a method that you create doesn’t need direct access to instance variables or instance methods in that class, then you should consider making the method static.
</li>
</ul>
• Suppose that you want to add a method to BankLoan that returns true if a loan amount is valid and false otherwise. If the loan amount (a double) is taken as a parameter, then the method would not need direct access to instance data. Create the following method header:

public static ________ isAmountValid(________ amount)

Add code to the method to return true if the amount is greater than or equal to 0 and false

otherwise:

return amount ___ 0;

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Activity: Static Members and JUnit Page 2 of 7

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Make sure that BankLoan.java compiles after you add your isAmountValid method. It will be tested later in this activity.</li>
<li>Now suppose that you need a method that returns true if a loan’s balance is greater than 0 and false otherwise. The user will pass in a BankLoan object as a parameter, and the method will only access this object, which is considered a local variable. Thus, the method can be static.
public static ________ isInDebt(________ loan) {
</li>
<li>Now add an if statement that returns true if the specified object has a balance greater than 0:
if (_________.getBalance() &gt; 0) { return true;

}

return ________;
</li>
<li>Compile your program and test it in the interactions pane:
Part 2: Static variables as fields – a.k.a. class variables as opposed to instance variables
</li>
</ul>
• You don’t have to read this bullet now, but make sure that you understand it before this week’s quiz and project. Properties of static variables / constants:

o Public constants (which are static and final) can be accessed using the name of the class if they are public.

o Public static constants can be accessed before an object of the class is instantiated. System.out.println(Math.PI);

3.141592653589793

o Public static variables (not declared as final) violate encapsulation. Private static variables should be accessed and modified through static or instance methods.

o A static variable is shared among all instances of the class and it can be accessed / modified by any method in the class. Why are constants declared as static as well as final?

If one object modifies a static variable, then it will be modified for all other objects as well because they are all accessing the same variable (i.e., a class variable is shared). If a variable needs to be specific to one object (e.g., each object need its own customer name field), then it should an instance variable (not static) rather than a class variable (static).

• Add a static variable to the BankLoan class that will count the number of BankLoan objects that have ever been instantiated in a program. The value will be initialized to 0 and then be incremented each time a BankLoan object is created.

private static int loansCreated = 0;

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
BankLoan b = new BankLoan(“Bob”, 0.08); BankLoan.isInDebt(b)

false

b.borrowFromBank(1); // borrow $1.00 BankLoan.isInDebt(b)

true

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Activity: Static Members and JUnit Page 3 of 7

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>You want to increment the variable only when an object is instantiated, so you’ll need to add the following code to the constructor:
loansCreated++;
</li>
<li>You’ll also need to add a method to access the variable. The method will only access a static variable, so it can and should be static as well.
public static ________ getLoansCreated() { return loansCreated;

}
</li>
<li>Also add a method that will reset the number of loans created to 0. The method only modifies a static variable, so it can be static and there is no return type.
public static _________ resetLoansCreated() { ________ = _________;

}

Test your class in the interactions pane:
</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
BankLoan.getLoansCreated()

0

BankLoan jane = new BankLoan(“Jane L”, 0.09); BankLoan bob = new BankLoan(“Bob S”, 0.09);

Now open a canvas window (click on the Debug tab), then drag jane and bob onto the canavas. Unfold jane in the Debug tab, and drag loansCreated onto the Canvas. Figure 1 shows the initial canvas. Notice that loansCreated is shown as BankLoan.loansCreated since it is a class variable rather than an instance variable.

BankLoan.getLoansCreated()

2

bob = new BankLoan(“Bob Parker”, 0.02);

Figure 2 shows the canvas after bob has been assigned a new loan and the loansCreated field

has been updated. That is, we have now called the new operator a total of three times.

BankLoan.getLoansCreated()

3

BankLoan.resetLoansCreated(); BankLoan.getLoansCreated()

0

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Activity: Static Members and JUnit Page 4 of 7

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1. Canvas after jane and bob are created

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2. Canvas after bob is reassigned to a new BankLoan

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 4 of 7

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Activity: Static Members and JUnit Page 5 of 7

</div>
</div>
<div class="layoutArea">
<div class="column">
Part 3. JUnit Test Files – NOTE: In order to use JUnit on you own computer, you must download and unzip JUnit (as you did Checkstyle), and then JUnit must be configured in jGRASP (Tools &gt; JUnit &gt; Configure). Note that the following example will work with the unmodified BankLoan.java file.

Now let’s create a JUnit test file to allow us to test (and retest) the method in a class. Suppose we want to test the chargeInterest() method. We’ll need to create a test method that essentially includes the statements that we would enter as interactions to informally test the chargeInterest() method.

<ul>
<li>For example, we could test this method using interactions by entering the following:
BankLoan loan1 = new BankLoan(“Jane”, .10); loan1.borrowFromBank(1000.00); loan1.chargeInterest()

loan1.getBalance()

1100.0
</li>
<li>Create a project file for the BankLoan class. After you have created the project and added BankLoan.java to it, you should see the following in the Open Projects section of the Browse tab.</li>
<li>With BankLoan.java open in the CSD Window, on the Desktop menu click on the Create JUnit Test File button .</li>
<li>This creates a JUnit test file name BankLoanTest.java that is listed in the “Test File category in the Project tab.</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Activity: Static Members and JUnit Page 6 of 7

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>BankLoanTest.java contains a class with the same name. The class contains a setup() method and test method named defaultTest() that asserts that 0 equals 1 which will always fail. This is an example test method that you should comment out, modify, or delete.
/** A test that always fails. **/

@Test public void defaultTest() {

Assert.assertEquals(“Default test added by jGRASP. Delete ”

+ “this test once you have added your own.”, 0, 1);

}
</li>
<li>Either modify the method above or create a new test method as follows. If you create a new method, be sure to delete or comment out the default test method. Note that we won’t be using the setup() method, so it can be deleted or left as is since it has an empty body.
@Test public void chargeInterestTest() {

BankLoan loan1 = new BankLoan(“Jane”, .10); loan1.borrowFromBank(1000.00);

loan1.chargeInterest();

Assert.assertEquals(” “, 1100, loan1.getBalance(), .000001);

}

Note that the third parameter is the “delta” required when two doubles values are compared for equality (i.e, how close do the values have to be to be considered equal; in this case, we have chosen 0.000001).
</li>
<li>After you have entered your test method, you can compile the test file or you can compile and run the test file using JUnit buttons on the Project tab or on desktop menu. You should make sure BankLoanTest compiles successfully before you run it.</li>
<li>A successful test will have output such as the following output in the Run I/O tab and in the JUnit results window
Runing 1 JUnit test. Completed 1 tests 1 passed
</li>
<li>To test other methods in the BankLoan class, you simply create additional @Test methods in BankLoanTest.java using the procedure above. Remember creating a test method is only slightly more effort than manually testing your method in interactions the first time. In fact, many of the same statements used in interactions are used in the test method. These are then followed by an appropriate JUnit assert statement. As you create new methods in a class, you can also create appropriate test methods in the corresponding test class. This helps ensures each new method is correct before you proceed to the next method. Being able re-run all test files with a single click is a huge time saver as you build your program incrementally and make changes during development.</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Activity: Static Members and JUnit Page 7 of 7

</div>
</div>
<div class="layoutArea">
<div class="column">
• If a test method fails, set a breakpoint at or above the assert that failed, then run the test file using the test file debugger button. When the program stops at the breakpoint, drag variables onto the canvas and examine the values. Hopefully, you’ll be able to see the problem and correct the error. Remember that if a test method fails, either the method you are testing has an error or the test method itself has an error. You may need to step in at the statement that calls the method you are testing. For example, stepping in at loan1.chargeInterest() will take you into the chargeInterest method where you can step through it looking for a problem. Figure 3 shows the jGRASP desktop after stopping at the breakpoint and then stepping one time to create loan1. Figure 4A shows the canvas after loan1 has been dragged onto it but before any methods have been called on loan1. Figure 4B shows the canvas after calling the borrowFromBank and chargeInterest methods on loan1.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3. Running BankLoanTest in the Debugger, after stopping at the breakpoint and then stepping one time to create loan1.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 4A. Canvas with loan1 after it was created but before calling borrowFromBank.

</div>
<div class="column">
Figure 4B. Canvas after calling the borrowFromBank and chargeInterest methods.

</div>
</div>
<div class="layoutArea">
<div class="column">
Finally, submit your BankLoan.java and BankLoanTest.java files to the grading system.

Page 7 of 7

</div>
</div>
</div>
