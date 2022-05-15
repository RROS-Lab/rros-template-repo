# rros_template_repo
the template repository of RROS lab

Recommened prerequist: [create a new ROS package](http://wiki.ros.org/ROS/Tutorials/CreatingPackage)

## Structure

## Change Package Name
If you want to change the package name, here are what you should change:  

- line 2 in CMakeLists.txt  
  `project([new package name])`
- line 3 in package.xml  
  `<name>[new package name]</name>`
- current directory name
- directory name under include folder  
  `include/[new package name]`

or you can just replace all `rros_template_repo` with `[new package name]`