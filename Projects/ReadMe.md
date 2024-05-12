1. Simple Portfolio
2. School web 
3. restro - 1
4. restro - 2
5. Bio graphy
6. Airnb
7. Foodmandu
8. unsplash
9. Menu Food
10. Myntra 



# Var with calc
:root {
  --fixed-nav-size: 50px;
}

.main{
    height: calc(500px - var(--fixed-nav-size))
}


Determining "perfect" CSS breakpoints depends on various factors such as the content, design, and target devices of your website. However, here are some commonly used breakpoints based on typical device sizes:

1. **Extra Small Devices (phones)**: 
   - Typically less than 576px.
   - Example: `@media screen and (max-width: 575.98px) { ... }`

2. **Small Devices (landscape phones, small tablets)**: 
   - 576px to 767px.
   - Example: `@media screen and (min-width: 576px) and (max-width: 767.98px) { ... }`

3. **Medium Devices (tablets)**: 
   - 768px to 991px.
   - Example: `@media screen and (min-width: 768px) and (max-width: 991.98px) { ... }`

4. **Large Devices (desktops, laptops)**: 
   - 992px to 1199px.
   - Example: `@media screen and (min-width: 992px) and (max-width: 1199.98px) { ... }`

5. **Extra Large Devices (large desktops)**: 
   - 1200px and above.
   - Example: `@media screen and (min-width: 1200px) { ... }`
