# Ztimer

this timer in written in vanila javscript;

---



1. > ##### Just Download or clone the current repository in the project directory
2. > ##### File Architechture
    * ztimer
        - ztimer.js
        - ztimer.min.js

---

3. > ##### Example 
```
<html>
    <body>
        <div id="ztimer"><div>
        <!--Add the scripts -->
        <script src="/ztimer.min.js"></script>
        <script>
        new Ztimer({
                starttime:'0,0,0',
                endtime:'0,1,0',
                selector:'#ztimer'
        }).StartTimer();        
        </script>
    </body>
</html>


```
4. ##### Source Code
> To create a timer for 1 minute.
```
<script>
    new Ztimer({
        endtime:'0,1,0',
        selector:'#ztimer'
    }).StartTimer();    
</script>
```
1. > ##### Options
* **starttime**
  type:string,
  default:'0,0,0' 
  
  >'hour,min,sec'
* **endtime**
  type:string,
  >'hour,min,sec'
* **selector**
  type:string,
  >(example)'#ztimer'
