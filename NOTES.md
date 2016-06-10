### VelocityTemplateToFile NOTES:

With templating, it's super easy to combine multiple input sources with multiple outputs to create a complex web of artifacts. 

**But we're not going to do that here, because it might create a confusing example project!**

Instead, on input source for one output file. As follows.

3 input sources:

 1 file
 1 key-value map 
 1 header, set in compiled code
 
3 output files

 2 Letter to Mom
 2 JSON document
 3 bash script

If you're an automation enthusiast you will immediately want to combine these into more complex projects, but at least this will get you started. See [**jammazwan.maker**](https://github.com/jammazwan/jammazwan.maker) if you prefer a dizzying array of monster templating to confuse yourself with.

### To Run

Run the XauTest unit test

### File -> Letter to Mom

This runs automatically.

```java
from("file://../src/main/etc")...
```

Look for **dearMom.txt** in the root of this project.

### Key-Value Map -> JSON doc

This runs from a template in the unit test. Check the root of the project for **myCity.json**

### Header -> Bash Script

This runs from a template in the unit test. Check the root of the project for **lsMe.sh**
 
