
# Lab Report 2

## Rohan Upalekar

![Image](Chatservercode.png)

## Screenshot of addmessage 1


![Image](addmessage1.png)


The methods in my code that are called are `handleRequest(URI url)`. The relevant arguments are the `add message` commands in the url: `/add-message?s=Hello&user=jpolitz` etc. These are stored in the `String input` variable. The variables change as new commands get added. `String input` starts as an empty string (""). As more `add` commands are typed, it gets stored in that variable, thus displaying the messages, and future messages when they are added `(jpolitz + ": " + Hello + "\n")`. 

---


## Screen shot of addmessage 2


![Image](addmessage2.png)

The methods in my code that are called are `handleRequest(URI url)`. The relevant arguments are the `add message` commands in the url: `/add-message?s=How are you&user=rupalekar` etc. This argument is stored in the `String input` variable which already contains the previous command. The current value of `input` has changed to: `(jpolitz + ": " + Hello + "\n" + rupalekar + ": " + How are you + "\n")`. 

---

## Screenshot of ieng login wo password

![Image](iengsshwopassword.png)


---


## Public Key path 
`/home/linux/ieng6/oce/5k/rupalekar/.ssh/authorized_keys`


![Image](iengpublickey.png)

 
---

## Private Key path
`/Users/rohanupalekar/.ssh/id_rsa`


![Image](iengprivkey.png)

---

## Something I learned

During the lab in week three I learned about ssh keys to login and some of their functions such as mkdir. It's a way to make a new directory all within the command line. 
