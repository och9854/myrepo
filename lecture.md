# Object
---

An Object is an entity having state and behavior (properties and method). 

# Data Object
---

- Date() object
  - getFullYear
  - getMonth
  - getDate
  - getTime
  - etc


# Get Time Difference
----

```JS
// How many days a couple met
<script>
        var now = new Date();
        var start = new Date('2021-12-05');

        var timeDiff = now.getTime() - start.getTime();
        var dayDiff = Math.floor(timeDiff / (1000 * 60 * 60 * 24) + 1);
        
        $('#love').text(dayDiff + 'days');

        console.log(dayDiff);
    </script>
```

```JS
// How many days are left to a anniversary
// valentine
var valentine = new Date('2021-02-14');
var timeDiff2 = valentine.getTime() - now.getTime();
var day2 = Math.floor(timeDiff2 / (1000*60*60*24) + 1);

$('#valentine').text(dayDiff + 'days left');
```



