# Chapter-6-1
Rewrite the following code using a for loop.

```Processing
size(200, 200);
background(255);
int y = 0;

while (y < height) {
  stroke(0);
  line(0, y, width, y);  
  y = y + 10;
}
```
