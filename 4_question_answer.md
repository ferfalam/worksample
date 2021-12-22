# Question : How to use "singular" and "plural" properly in Rails ?

.singularize and .pluralize is some properties of String class.    
  
.singularize is use to get the singular of some word. This is some examples of using:
  
* 'posts'.singularize            # => "post"  
* 'octopi'.singularize           # => "octopus"  
* 'sheep'.singularize            # => "sheep"  
  
.pluralize is use to get the plural of some word. This is some examples of using:  

* 'post'.pluralize             # => "posts"
* 'octopus'.pluralize          # => "octopi"
* 'sheep'.pluralize            # => "sheep"
* 'words'.pluralize            # => "words"
