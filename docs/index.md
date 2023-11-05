## Welcome Nuria

This is an image

![This should be a cat image](images/MT01/cat.jpg)

This is an image scaled

![This should be a cat image](images/MT01/cat.jpg){width=600}

This is a centered image

<figure markdown>
![This should be a cat image](images/MT01/cat.jpg){width=600}
</figure>

This is an image aligned to left: 

<div markdown>

![This should be a cat image](images/MT01/cat.jpg){ align=left }

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
massa, nec semper lorem quam in massa.

</div>


<img src="images/MT01/cat.jpg" alt="drawing" width="800"/>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```
