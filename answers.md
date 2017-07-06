1a
var profilePicture = document.querySelector('.profile-image')
profilePicture.src = "https://upload.wikimedia.org/wikipedia/commons/3/3a/Toronto_skyline_(2012).jpg"

1b
var skyImage = document.querySelector('#left-image')
skyImage.src = "http://d3exkutavo4sli.cloudfront.net/wp-content/uploads/2013/07/Vancouver-aerial-present-4.jpg"

2
title = document.querySelector('h1.highlight')
title.innerText = 'Doug the Dog'

3
employmentTitle = document.querySelector('#employment h3.info-title')
employmentTitle.innerText = 'Unemployment'

4
body = document.querySelector('body')
body.style.backgroundColor = 'grey'

5
highlight = document.querySelectorAll('.highlight')
highlight.forEach(function(item) {item.style.color = 'blue'})

6
header = document.querySelectorAll('h1')
header.forEach(function(item) {item.style.fontFamily = 'monospace'})

7
roundIcon = document.querySelectorAll('a.action-icon-bg')
roundIcon.forEach(function(item) {item.style.backgroundColor = 'grey'})

8
nameField = document.querySelector('input#name.contact-info')
nameField.placeholder = 'identify yourself'

9
messageField = document.querySelector('textarea#message')
messageField.placeholder = 'state your business'

10
nameField = document.querySelector('input#name.contact-info')
nameField.value = 'your nemesis'

11
emailField = document.querySelector('input#email.contact-info')
emailField.value = 'koalathebear@gmail.com'

12
submitButton = document.querySelector('input#submit')
submitButton.value = 'En garde!'

13
submitButton = document.querySelector('input#submit')
submitButton.disabled = 'disabled'

14
sideBar = document.querySelector('form')
sideBar = sideBar.reset()

------------- PART 2 -------------

1a
skills = document.querySelectorAll('.bar-default')[2]
timeTravel = document.querySelector('#time-travel')
skills.removeChild(timeTravel)

1b
pikachu = document.querySelector('.portfolio-container')
pikaCopy = document.querySelector('.profile-image').cloneNode()
pikachu.appendChild(pikaCopy)

2
pikachu = document.querySelector('.portfolio-container')
for (var i = 0; i < 10; i++) {pikaCopy = document.querySelector('.profile-image').cloneNode();
pikachu.appendChild(pikaCopy)}

3
var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);

var rightSpan = document.createElement('span');
var currentTime = new Date();
var bioInfo = document.querySelector('.bio-info');
bioInfo.appendChild(leftSpan);
rightSpan.innerHTML = currentTime;
bioInfo.appendChild(rightSpan);
