# swirl courses

This is a collection of interactive courses for use with the swirl R package. You'll find instructions for installing courses further down on this page. Some courses are still in development and we'd love to hear any suggestions you have as you work through them.

## Installation

This is the preferred method of installing courses. It automates the process by allowing you to do everything right from the R console.

1. Make sure you have a recent version version of swirl:

```bash
install.packages("swirl")
```
2. Enter the following from the R console, substituting the name of the course that you wish to install:
```bash
library(swirl)
install_from_swirl("Course Name Here")
swirl()
```
For example, install_from_swirl("R Programming") will install the R Programming course. Please note that course names are case sensitive!

If that doesn't work for you...

## Install and run a course manually

If the automatic course installation method outlined above does not work for you, then there's a simple alternative.

1. Click on the Download ZIP button on the righthand side of this page.

2. Enter the following from the R console, substituting the correct file path to your downloaded file and the name of your desired course:

```python
library(swirl)
install_course_zip("path/to/file/here/swirl_courses-master.zip", multi=TRUE, 
                   which_course="Course Name Here")
swirl()
```
For example, if you download the zip file to ~/Downloads/swirl_courses-master.zip, then the following command will install the R Programming course.
```bash
install_course_zip("~/Downloads/swirl_courses-master.zip", multi=TRUE, which_course="R Programming")
```
Please note that course names are case sensitive!

Although we recommend you install one course at a time, if you omit the which_course argument, then all available courses from this repository will be installed:

```bash
install_course_zip("~/Downloads/swirl_courses-master.zip", multi=TRUE)
```

##Uninstall a course

If you'd like to remove a course at any time, you can use uninstall_course("Course Name Here").

##Using swirl in the classroom

Instructors around the world are using swirl in their classrooms. We think this is awesome. If you're an instructor, please feel free to do the same -- free of charge. While your students may be paying to take your course or attend your institution, we simply ask that you don't charge people directly for the use of our software or instructional content.

If you are not sure about a particular use case, don't hesitate to send us an email at [info@swirlstats.com](info@swirlstats.com).
