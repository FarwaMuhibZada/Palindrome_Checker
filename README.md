
# Palindrome_Checker 🚀

## Project Description 📝

> A  Palindrome Checker is used to check if the word or phrase that can be read the same way forwards and backwards, ignoring punctuation, case, and spacing. take input from users then check multipale conditions when you enter a sentence or a phrase. if the sentense or phrase match the condition it will show an Output and say that the sentence are palindrom if it not match the condition it will show an Output and say that the sentence are  not palindrom. it has the functionality that display an alert box when you submit the empty input. it has a simple and perfect User Interface.
>


```java script
checkButton.addEventListener("click",()=>{
  const lowerReplaced = textInput.value.toLowerCase().replace(/[^A-Za-z0-9]/g,"");
  if (textInput.value === ""){
    alert("Please input a value");
  }

  else if (textInput.value.length === 1){
    result.innerText = `${textInput.value} is a palindrome`;
    textInput.value = "";
  }
});

```



## Demo 📸

life demo link [(https://farwamuhibzada.github.io/Palindrome_Checker/)]

![first page](/Capture.PNG)








## Technologies Used 🛠️

List the technologies or tools that i used to develop this project. 
- HTML
- CSS
- java script


## Installation 💻

for using this project you neet to install 3 things:

- chrombrowser
- an IDE like vscode
- git
- node JS



## Usage 🎯

for using this project you need to know a few commond first clone the repositry in yor local machine then go to the github directory . open the project on your IDE like vscode and start working on it .


go to the cmd and clone the Technical Documentation Page 
using this commond:
```bash

git clone https://github.com/FarwaMuhibZada/Palindrome-Checker.git 
```
go to the githu directory:
```bash

cd>Palindrome_Checker

```
open the project on your IDE like vscode :

```bash

cd>Palindrome_Checker code .

```


## Features ⭐
- take an inpute from user
- check the sentence and phrases.
- has multipal condition 
- give an output 
- return a alert box if there is an empty value 


## FarwaMuhibzada 👩‍💻



- LinkedIn: [(https://www.linkedin.com/in/farwa-muhibzada/)]
- Email: [(farwafarid2017@gmail.com)]

## Contributing 🤝
For contribution you can create a pull request and mention me there.Thank you.


