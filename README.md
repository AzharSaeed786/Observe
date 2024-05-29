# Observe
Observe Ka Mafhoom
Observe ek method hai jo LiveData ka hissa hota hai. Ye method aap ko LiveData object ko observe karne ki ijaazat deta hai. Matlab jab bhi LiveData object mein koi data change hota hai, observer automatically notify hota hai aur aap ko updated data milta hai.

Observe Ka Tarika
observe method ko LifecycleOwner (jaise Activity ya Fragment) ke sath call kiya jata hai, aur ye ek Observer object leta hai jo data change hone par callback ko trigger karta hai.
