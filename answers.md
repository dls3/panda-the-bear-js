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
