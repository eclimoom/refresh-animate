# refresh-animate
refresh-animate
in css 
```
@-webkit-keyframes spin2 {
    from { -webkit-transform: rotate(0deg);}
    to { -webkit-transform: rotate(360deg);}
}
@keyframes spin {
    from { transform: scale(1) rotate(0deg);}
    to { transform: scale(1) rotate(360deg);}
}
.glyphicon-refresh-animate {
    -animation: spin .7s infinite linear;
    -webkit-animation: spin2 .7s infinite linear;
}
```

in html
```
<button class="btn btn-warning">
<span class="glyphicon glyphicon-refresh glyphicon-refresh-animate"></span> Loading...
</button>
```
