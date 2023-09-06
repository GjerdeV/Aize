
-------- Notes for automated tests ---------
1.2:
Test is failing due to the {enter}-command is being sent so the new-todo label is already blank when trying to verify what is written inside the blank input field. Removing the {enter} from the previous line and then checking the field of what's written in it then sending the command {enter} then checking.

1.4.1:
This test is failing because doubleclicking does not suffice to start directly writing in the new checked item's label. Therefore, the new line that it wants to look for "Pay water bill" is not visable. I do not know why it is not writing in the new text or deleting the previous one.

1.4.4:
This is failing due to the button being a part of the list, should instead look for on the page not exist then name of button.

1.5:

