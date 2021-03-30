# Deploying a Simple Machine Learning Model into a WebApp using TensorFlow.js

## Steps

1. **Train model.**  With MNIST_on_GPU.ipynb notebbok.
2. **Convert a Keras model to Tensorflow.js.** Run
 
        $ !pip install tensorflowjs
        $ !tensorflowjs_converter --input_format keras ‘./model.h5’ ‘./model’
     
     
3. **HTML5 Canvas file.** Create a simple HTML page that uses the HTML5 Canvas component that lets us draw on it. Call this file “tfjs.html”.
4. **Hooking everything up.** It’s straightforward to test things locally, and you can easily set up an HTTP server for testing with Python:
    
        $ python3 -m http.server 8080
    
 To test on phone:
 
    $ ngrok http 8080
 That opens a tunnel to a URL that you can access from through phone.
 
Or you can just run it throw link:
https://LizaKurilo.github.io/tfjs.html
Or make your one repository named “{username}.github.io”


