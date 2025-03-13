# gguf_convert


Hello, I am sharing code that can convert llama3.2 vision to gguf.  

The overall code is from https://github.com/danbev/llama.cpp/tree/vision-api-mllama-example/examples/simple-vision-mllama, and my repositories only share the modified source code.  

This code is unrefined and very poorly readable.  

However, I am sharing it upon request. Please ignore any code that you do not understand.  

There are many traces of various attempts for conversion, and there are many codes left as they are because I did not feel the need to modify them.  

**Important Note**

For the llama3.2 vision model, you'll need to make a change in the config.json file. Specifically, please adjust the vision_output_dim from its likely current value of 7680 to 4096.
