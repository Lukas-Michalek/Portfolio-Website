# PROBLEMS AND SOLUTION

**Problem 1** <br> How to fill the remainder of empty space in viewport in fixed nav bar(header)?

**Solution**
<br>
As can be seen in CSS I have used the property

```
min-height = 100vh (viewpoint height)
```

in the last div named social-sites in this example

<br>

**Problem 2** <br>
How to put buttons such as dark mode and volume in the top right corner? And how to make sure position will be fixed?

**Solution** <br>
I have used **`float`** for each section. (Left hand fixed position Header has float: left) and those 2 butons I wanted in top right side has float:right. <br>

I also made position: fixed and to make sure buttons will stay to the right I used

```
.top_right_navigation{

    float: right;
    position: fixed;
    right:0;
    top:0;
    width: 150px;
}
```

so **`right`** and **`top`** specifing where I want htem to stay

Great help was this site

https://www.w3schools.com/css/css_positioning.asp
