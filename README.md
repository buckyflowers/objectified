objectified
===========

### CLASS NAME CONVENTIONS

-------------------
# OBJECTS
class names for pages is just the unique name of the object. Single hyphens for spaces ie: .progress-bar
-------------------

.page {
  height: 100%;
}



-------------------
# EXTENDING OBJECT
## this is how you extend an object. This denotes that it is dependent on the .page styles.
-------------------

.page--quiz {}



-------------------
# ELEMENTS
a child node or element of an object
-------------------

.page-body{

}



-------------------
# EXTENDING ELEMENTS
## extending an child node or element of an object
-------------------

.page--quiz{
  .page-body{}
}

OR

.page-body--narrow{}



