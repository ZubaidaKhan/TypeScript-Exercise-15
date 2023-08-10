# TypeScript-Exercise-15
## Changing Guest List
: You just heard that one of your guests can’t make the dinner, so you need to send out a new set of invitations. You’ll have to think of 
 someone else to invite.

• Start with your program from Exercise 14. Add a print statement at the end of your program stating the name of the guest who can’t make it.

• Modify your list, replacing the name of the guest who can’t make it with the name of the new person you are inviting.

## Solution:

Let's go step by step to explain the code:

### Step 1:
We have an array called `guestList`, which contains the names of guests invited to a dinner.

### Step 2: 
We define a constant `guestWhoCantMakeIt` with the value "Muhammad Ali Jinnah" to represent the guest who cannot attend the dinner. We then use `console.log` to print a message indicating that this guest can't make it.

### Step 3:
We define another constant `newGuest` with the value "Nelson Mandela", representing the name of the new person we want to invite.

### Step 4:
We find the index of the guest who can't make it using `indexOf()` function and store it in the variable `indexOfGuestWhoCantMakeIt`. If the guest is found (index is not -1), we replace their name in the `guestList` with the name of the new guest using `guestList[indexOfGuestWhoCantMakeIt] = newGuest`.

### Step 5:
We use `console.log` to print the message "Second set of invitation messages:", indicating that we are about to send out the second round of invitations.

### Step 6:
We use the `forEach()` method to iterate over the `guestList` array. For each guest, we use `console.log` to print a personalized invitation message using the template "Dear [guest], You are invited to the dinner."

Overall, the code demonstrates how to manage a guest list for a dinner event by replacing a guest who can't make it with a new guest and sending out personalized invitation messages to the remaining guests.
