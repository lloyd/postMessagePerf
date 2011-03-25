this is a simple application to get a rough idea of how postmessage
performs when you send LOTS OF DATA through it.

## Running the test:

1. clone me
2. git submodule init
3. git submodule update
4. open pmtest.html in your favorite browser

## Some sample performance numbers:

To send a gigabyte of data between two frames via postMessage on my 
macbook pro:

  * Firefox 4: 39.5s
  * Chrome 10: 55.8s
  * Safari 5:  15.3s

