###Solved by bitvijays

**Web Starter: 10 Points**

Web Starter
10

Click for the flag ;). It's totally that easy ;).

http://162.243.0.171/Web.html

On checking the view source for the page we get:
```

<html><head>
<script>
console[String.fromCharCode(0x6c,0x6f,0x67)](String.fromCharCode(0x66,0x6c,0x61,0x67,0x7b,0x44,0x40,0x74,0x5f,0x33,0x70,0x31,0x63,0x5f,0x43,0x30,0x6e,0x73,0x30,0x31,0x65,0x7d));
</script>
</head>
<body>
<button> Click Here For The Flag </button>

</body></html>
```

Converting the 
```
0x66,0x6c,0x61,0x67,0x7b,0x44,0x40,0x74,0x5f,0x33,0x70,0x31,0x63,0x5f,0x43,0x30,0x6e,0x73,0x30,0x31,0x65,0x7d
```
results in flag{D@t_3p1c_C0ns01e}

The same can also be previewed on console
