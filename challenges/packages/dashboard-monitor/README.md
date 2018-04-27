# Dashboard Monitor

## DESCRIÇÃO
---

<!-- https://tabler.github.io/tabler/ -->

![Layout](assets/layout.png)

[code.zip](code.zip)

Mínimo 2 componentes

## COMPONENTES
---

**COMPONENTE 1**

![Layout](assets/component1.png)

```html
<!-- 
  TODO Component 1 
  
  6% 43 New Tickets fa-chevron-up
  -3% 17 Closed Today fa-chevron-down
  9% 7 New Replies fa-chevron-up
  3% 27.3K Followers fa-chevron-up
  -2% $95 Daily Earnings fa-chevron-down
  -1% 621 Products fa-chevron-down
-->
```

```
#cd201f (.text-green)
#5eba00 (.text-red)
```

```
margem inferior 1.5rem (.card)
```

```html
<div class="card">
  <div class="card-body p-3 text-center">
    <div class="text-right text-green">
      6%
      <i class="fa fa-chevron-up"></i>
    </div>
    <div class="h1 m-0">43</div>
    <div class="text-muted mb-4">New Tickets</div>
  </div>
</div>
```

**COMPONENTE 2**

![Layout](assets/component2.png)

```html
<!-- 
  TODO Component 2

  Development Activity
  User	            Commit	                  Date	
  Ronald Bradley	  Initial commit	          May 6, 2018	
  Beverly Armstrong	Left sidebar adjustments	April 15, 2018	
  Bobby Knight	    Topbar dropdown style	    April 8, 2018	
  Sharon Wells	    Fixes #625	              April 9, 2018	 
-->
```

```
img/faces/male/9.jpg
img/faces/female/1.jpg
img/faces/male/4.jpg
img/faces/female/11.jpg
```

```
fa fa-trash
```

**COMPONENTE 3**

![Layout](assets/component3.png)

```html
<!-- 
  TODO Component 3
  
  New feedback 62
  Today profit $652
  New feedback 62
  Today profit $652 
-->
```

```
altura .5rem (progress)
```

```
#cd201f (.bg-green)
#5eba00 (.bg-red)
```

**COMPONENTE 4**

![Layout](assets/component4.png)

```html
<!-- 
  TODO Component 4

  132 Sales     12 waiting payments
  78 Orders     32 shipped
  1,352 Members 163 registered today
  132 Comments  16 waiting 
-->
```

```
#cd201f (.bg-green)
#5eba00 (.bg-red)
#f1c40f (.bg-yellow)
#467fcf (.bg-blue)
```

```
fa fa-dollar
fa fa-shopping-cart
fa fa-users
fa fa-envelope
```