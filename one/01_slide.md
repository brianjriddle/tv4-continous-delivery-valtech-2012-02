!SLIDE 
# One button deploys #

!SLIDE bullets 
# who is tv4?#
* Swedens largest commercial TV channel
* 900~ employees
* 10 channels and 25 local stations

!SLIDE bullets 
# who is tv4 digital media?#
* 4 full time developers
* java, ruby, php, node
* operations and development

!SLIDE bullets 
#who am i
* developer - shackled to a cms 10+ years
* operations
* ruby/jruby since 2007

!SLIDE bullets
* what's this flickr img](flickr img)

!SLIDE bullets
* 2007 one button deploy 
* :( not possible

!SLIDE bullets
* spolsky test (2000)
* Can you make a build in 1 step

!SLIDE bullets
* Continous Compilation
* broken deliveries
* software can't be deployed

!SLIDE bullets
* WELC
* (WELC)[WELC picture]

!SLIDE 
* Continous Testing/metrics
* emma

!SLIDE
* first jenkins machine

!SLIDE bullets
* Compiling JSP
* (resin/tomcat gist)[link]

!SLIDE
* Consitency
* OS
* Build tools (ant/maven)
* Editor (Intellj)
* Same build process local/jenkins

!SLIDE
* 2nd jenkins

!SLIDE
* Deploy till it doesn't hurt (much)
* Prod every 6-8 weks
* Set up Continous Compilation, Continous Unit Testing
* Set up jenkins
* Deploy every week
    * Week 1 feature deploy (2 bug fixes)
    * Week 2 feature deploy (1 bug fix)
    * Week 3 feature deploy (0 bug fixes that couldn't wait)

!SLIDE
* Jenkins The ruby era(greenfield)
* No compile
* More tests
* Better Coverage
* Testing generated HTML(still no ajax)

!SLIDE
* WORDPRESS
* Define boundaries btwn ops/dev
* Deploy only wp-content
* It's just php

!SLIDE
* Mule
* Hot deploy ++
* Testing --
* Groovy (testing possible!)
* Deploy possibility service/system

!SLIDE
* Pragprog
* Only one editor
* Only one deploy system
* ci.sh

!SLIDE 
* cost of deploy
* $50 per deploy
  * $100 from tv4 employee(technical)
  * $100 from tv4 employee(nontechnical)
* if everything goes ok otherwise start over....

!SLIDE
* Async messaging
* I ♥ mail
* user filters.
    * 0 inbox kinda hard w/ 50 mail a day
* only broken or fixed(mail)

!SLIDE
* Not all systems can auto deploy
* CMS(Polopoly)
* Wordpress
* Mule (ihave to copy how many petabytes)
* Ruby (Heroku, warbler, capistrano)
* Avoided db migrations. so far.


!SLIDE center
#thanks#
![brianjriddle](brian.gif)

http://http.tv4.se

@brianjriddle

http://github.com/TV4

http://github.com/brianjriddle
