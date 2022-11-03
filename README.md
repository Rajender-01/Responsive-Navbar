# Responsive-Navbar 

* Make a responsive navbar using HTML and CSS only.
* To make responsive utilize the media query.
* Here I utilize the **:checked** psuedo class to let the user toggle the content based on the state of checkbox without using javascript.

---
   
  
      nav ul {
        position: fixed;
        top: 40px;
        left: -100%;
        background: rgb(20, 19, 19);
        height: 14rem;
        width: 100%;
        display: block;
        text-align: center;
        overflow: hidden;
        transition: all 0.3s ease;
    }   
    
    
     #check[type=checkbox]:checked~ul {
        left: 0;

---

## Add a Hamburger Icon
> Add this code to your HTML file above the tiltle.
`    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">    `

> And paste this code between body tag.
` <input type="checkbox" id="check" name="check">
        <label for="check" class="menu-btn">
            <i class="fa fa-bars"></i>
        </label>  `


## Here is the output

![Responsive Navbar1](https://user-images.githubusercontent.com/99115642/199670600-b3cc4c91-e6d9-4bda-8a01-870ac0e2471e.jpg)
![Responsive Navbar2](https://user-images.githubusercontent.com/99115642/199670624-e6bb4cec-ddff-4db3-8efb-4ef71c7480af.jpg)


[Tutorial - Responsive Navbar](https://www.youtube.com/watch?v=nKnrdABs7Zs)
