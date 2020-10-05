# Spark for Big Data

This repo is a collection of assingments/projects and explanations throughout University of California San Diego's (UCSD)  "Big Data with Spark" course.


---
## Week Descriptions:

1. Week 1: RDDs Map Reduce;
2. Week 2: Processing Large Data w/ Map Reduce;

---

## Setup

1. Clone this repository
2. Install *ucsddse230/cse255-dse230* docker's image;
3. Go to [Run](##Run).
---
## Run

To run:

`sudo docker run -it -p 8889:8888 -v {assignment name}:/home/ucsddse230/work ucsddse230/cse255-dse230 /bin/bash`

Example (from my computer):
```sh
sudo docker run -it -p 8889:8888 -v ~/repos/spark_edx/week1/pa1/:/home/ucsddse230/work ucsddse230/cse255-dse230 /bin/bash

jupyter notebook
```

The current port mapping is the standard 8888(docker) to 8889(local) - in case you might be running another local instance of jupyter notebook.

---
## Follow up

If you have any questions that I might be able to answer, feel free to reach me out! =)


---