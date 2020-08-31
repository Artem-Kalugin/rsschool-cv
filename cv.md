# About me
My name is Artem Kalugin. You can contact me by email(aharlo4@gmail.com) or in social networks ([VK](https://vk.com/artyomkalugin)).
# Summary
Nowadays i'm searching for an activity that will be good for me. I'm a 3rd year student of BSUIR, the Informational Communications faculty. I chose JS/Frontend courses because of creative part in websites programming. I'm really want to learn how to create good-looking sites and program it.
# Skills
Intermediate: HTML, CSS, Photoshop<br>
Low: Javascript, PHP, MySQL, C++<br>
Tools: Gulp, Mamp, SASS, Bootstrap, WordPress, Jquerry
# Code Examples

Code for adaptive carousel animation on website:
```javascript
$(".carousel-item-wrapper").click(function(){
    ($('.active>.carouseln-item').index()+1)
      if ($(window).width()<600){
      offset = ($(window).width() - $('.active>.carouseln-item').width())/2 - ($(window).width()/2)*$(this).index();
     }
      else {
      offset = (25 - $(this).index() * 50) + 'vw';}
      $('.carousel-wrapper').animate({
left: offset,
}, 400,"swing", function() {
});
      $('.carousel-item-wrapper').removeClass('active', 1000, "easeOutBounce");
      $(this).addClass('active', 1000, "easeOutBounce");
  });
});
```
# Education
I have passed 400 of 1400 lessons on htmlacademy.ru<br>
I'm also was on Itransition courses, but didn't pass it because of no enthusiasm to php. <br>
I'm a 3rd year student of BSUIR, the Informational Communications faculty.
# English
I Don't have real practice, but my media space is mostly on english. So i can understand the sense of the fluent speech, but my grammar is bad.
My english level, according to EPAM test, is **A2+**.
