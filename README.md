# Anti Track Tracker
The ATT (Anti Track Tracker) is a leightweight tool to check up on website visitors and see if they are blocking trackers.

### Get started
To get started you should add the following tag to your html
```html
<script src='https://cdn.jsdelivr.net/gh/Trigstur/ATT/dist/run.min.js'> </script>
```
This script will always depend on jQuery so if you haven't already. be sure to add it before adding the ATT.

Now you've done that you can start executing your scripts. As of now we only support sessionStorage usage,
so use it as followed 

```javascript
if (sessionStorage.getItem("OWA-B") !== true) {
// code you would like to execture
}
```

OWA-B acts as an operator and should be replaced acordingly 

- OWA-B = Open Web Analytics 
- GA-B = Google Analytics
