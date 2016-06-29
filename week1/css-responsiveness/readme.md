# Responsive Web Design (RWD)
> Adapting your design to fit different devices

## Purpose
> The purpose of this lecture is to teach students how to accommodate users with different  screen sizes, input devices, or browsers.

Students should learn how to use relative CSS units, such as `%`, `em`, `rem`, `vw`, and `vh`.

References
- [http://lmgtfy.com?q=css+units](CSS Units)
- [http://lmgtfy.com?q=media+queries](Media Queries)

## Lecture Notes

### Why?
- Wide range of devices, capabilities, and sizes

### How are these devices different?
- Network speed and data limits
- Touch/swipe interface vs click/hover
- Display size / pixel density
- Portrait vs landscape
- Aspect Ratio
- Operating system / browser

### Outdated Practice of serving multiple sites
- http://mysite.com
- http://m.mysite.com

### Designers
- Most tools that designers use don't really accommodate for RWD
- Open communication is key

### Mobile-First Development
- Designing a site for mobile primarily
- Progressive Enhancement
    * As the screen size increases, we can add more features or change the layout of our site

### Desktop-First X
- Graceful Degradation
    * often not as graceful as you would like
    * End up ripping out features as the screen gets smaller

### Media Queries
- Apply CSS based on certain conditions
- Mobile/base styles
- Media Queries (min-width) that increase in size

```css
    body {
        background-color:red;
    }
    @media (min-width:768px){
        body {
            background-color:blue;
        }
    }
    @media (min-width:1024px){
        body {
            background-color:blue;
        }
    }
```

### CSS Units

| unit     | description                                                                                            |
|----------|--------------------------------------------------------------------------------------------------------|
| px       | static, end up manually changing them based on screen size                                             |
| em       | refers to the WIDTH the of M character in a font based on the font-size applied to the PARENT element  |
| rem      | refer to the WIDTH of the M character based on the font-size applied to the HTML element               |
| %        | fluid, typically refer to the parent element                                                           |
| vw / vh  | fluid, refer to a percentage of the view width or view height                                          |
