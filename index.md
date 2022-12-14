# This will be a h1 header.
## This one - h2.
### and
#### so
##### on.
![image in water colors of sunny city](https://i.pinimg.com/originals/4a/d1/4b/4ad14b91f7cbde4aacf074812aee7ab2.jpg)

```
let output = document.querySelector(".output");
output.innerHTML = "";
let i = 10;
while (i >= 0) {
  const para = document.createElement("p");

  if (i === 0) {
    para.textContent = "Blas off!";
  } else if (i === 10) {
    para.textContent = `Countdown ${i}`;
  } else {
    para.textContent = i;
  }
  output.appendChild(para);
  i--;
}
```
- [x] Do HTML section
- [x] Do CSS section
- [x] Do JS section
- [ ] Do Node.js section
- [ ] Do React section
