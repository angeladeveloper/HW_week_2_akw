# HW_week_2_akw


## Objective

I wanted to create a new portfolio that I could build off of later. 

I restarted this website about 20 times, but I was going through alot of trial and error through layouts and the best practices. 

I decided to go with a grid layout, seeing as my page only had a few cards, though I did my header and footer in Flex

### Color Scheme 

``` css
:root {
    --logo-clr-light: #9F3E73;
    --logo-clr-dark: #3E074E;
    --pink-main-clr: #ecc0dc;
    --whit-main-clr: #F6F0ED;
    --grey-main-clr: #5E5D5C;
    --graident: linear-gradient(210deg, rgba(223, 107, 133, 1) 2%, rgba(187, 46, 123, 1) 32%, rgba(134, 48, 106, 1) 54%, rgba(62, 7, 78, 1) 94%);
    --border-radius: .6rem;
    --box-shadow:  var(--grey-main-clr) 3px 3px 6px;
} 
```

### Hover effect on buttons
 ``` css
 /* Gradient affect */
    background-image: var(--graident);
    background-size: 300%;
    background-position: right;
    transition: ease 500ms;

}

.header-list li:hover {
        background-position: left;
        box-shadow:  var(--logo-clr-light) 2px 2px 2px;
}
```