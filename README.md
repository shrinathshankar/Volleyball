# Volleyball
Facebook bot for volleyball group

This project will be a bot that will poll, manage, and track volleyball facebook group

1. it will schedule dates in the facebook group with a poll
   the poll will open noon Saturday, and it will close at 6 pm Wednesday
   all the people who voted on the poll for the winning day will be the expected attendance
   the courts cost 60$ per hour to rent, and there are 12 people per court

2. it will track attendance by checking who all voted for the poll
   and +1 will be posted in the comment section,
   +1 will be payed for by commenter
   current system is using a spreadsheet where the first column is name, and rest of the columns are dates
   every time a new date comes out, all columns need to be shifted one to the right such that the most recent date comes right after name
   current date columns show attendance status as well as color for status
   this should be changed to number of people coming for that person
   status of the person(if they showed up/ payed on time) should be indicated by the color
   this will start getting to large to manage

3. payments are currently done through venmo
   we need to be able to read venmo transactions and check to see if the person payed on time(next friday)
   if they payed on time then we mark them as green,
   if they are late we mark them as yellow
   we need to be able to distinguish transactions to phillip(TO) for volleyball vs other things
   we can  use the message of the transaction to see if it is for volleyball
   and match the sender to the person who voted to come
   venmo doesn't allow us to see how much?
   how to solve?
   -> maybe they puty amount in message as well so we can validate?
   maybe we need access to phillips account