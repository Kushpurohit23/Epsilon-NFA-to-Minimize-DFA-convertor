# Epsilon-NFA-to-Minimize-DFA-convertor

In computation theory, dealing with a large number of states and complex transitions in an epsilon-NFA can be challenging. To simplify this
process, we’ve developed a website using the Django framework. It takes Epsilon-NFA states and transitions as input, converting them into a DFA using a graph traversal algorithm with optimization using memorization to avoid repetitive calculation. The DFA is further minimized using the table-filling method. The output at each stage is displayed using a graph visualizer. This website is useful for both academic and professional purposes.

When you first load the site it will show you following page where you can add details of your Epsilon-NFA as mentioned in example of each input field.

![image](https://github.com/Kushpurohit23/Epsilon-NFA-to-Minimize-DFA-convertor/assets/96117695/76859ee6-d300-4ae6-93a6-71786682dbc2)

Once you enter all the details click on "Submit".  You will be redirected to page where you can specify transistion of your Epsilon-NFA by means of simple drop-down menue as shown below.

![image](https://github.com/Kushpurohit23/Epsilon-NFA-to-Minimize-DFA-convertor/assets/96117695/669ae858-e5be-438f-96cd-858524d4d623)

Here drop-down for state shows possible states you entered previously and forsymbol it will show symbol you entered in language field.

![image](https://github.com/Kushpurohit23/Epsilon-NFA-to-Minimize-DFA-convertor/assets/96117695/7d8e302b-102c-4d3c-8f92-a00d2e9d30fa)

Once you enter all transistion click on "show result". You will be redirected to result page where you can see your Epsilon-NFA, NFA, DFA and Minimized DFA in graphical form.

Epsilon-NFA

![image](https://github.com/Kushpurohit23/Epsilon-NFA-to-Minimize-DFA-convertor/assets/96117695/4c023863-abd8-4337-ae11-f0fb13a316d7)

NFA

![image](https://github.com/Kushpurohit23/Epsilon-NFA-to-Minimize-DFA-convertor/assets/96117695/36ecd23d-02f7-4bc5-aeeb-65f871ebcabb)

DFA

![image](https://github.com/Kushpurohit23/Epsilon-NFA-to-Minimize-DFA-convertor/assets/96117695/da102a92-e715-4e09-98c3-ec0d7c43f10e)

Minimized-DFA

![image](https://github.com/Kushpurohit23/Epsilon-NFA-to-Minimize-DFA-convertor/assets/96117695/f0d16cc9-f218-4220-b9fa-0cd49acb43d4)
