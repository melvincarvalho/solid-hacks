# URL Shortening

### Introduction

This hack enables you to use your solid pod as a URL shortener.  There are many reasons you might do this in normal life, however in Solid it becomes even better.  This is because many client side apps derive their content from the query string.  This can be up to 100k big so is impractical to share.

### The Hack

1. Open source tab
2. Create a new file xxx.html in a given directory
3. Add the code

```text
<script>location.href="<URL>"</script>
```

### Pro Tips

Suggested locations are 

```text
ROOT/public/u/
ROOT/u/
```

 Perhaps `u` for URL shortener?  The principle of shortening to keep the saved URL short.

  The shortener can also double as a URL redirector.  This has lots of unexpected reuse, as we shall see later!

### See Also

> Wikipedia article : [https://en.wikipedia.org/wiki/URL\_shortening](https://en.wikipedia.org/wiki/URL_shortening)



