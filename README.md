# Benchmark-TensorFlow-Windows
Benchmark TensorFlow Windows (TensorFlow Lite)

To execute, go to a command prompt and run 
```
python evaluate.py
```

Example output:

```
c:\GitHub\Benchmark-TensorFlow-Windows>python evaluate.py
Python version: 3.7.4 (default, Aug  9 2019, 18:34:13) [MSC v.1915 64 bit (AMD64)]
2020-04-26 12:48:37: Initizliaing model
input_details=[{'name': 'normalized_input_image_tensor', 'index': 578, 'shape': array([  1, 192, 192,   3]), 'dtype': <class 'numpy.uint8'>, 'quantization': (0.0078125, 128)}]
2020-04-26 12:48:37: Init done
Img 0, Eval time=356 ms.  Invoke=352.
Img 1, Eval time=339 ms.  Invoke=335.
Img 2, Eval time=338 ms.  Invoke=335.
Img 3, Eval time=310 ms.  Invoke=307.
Img 4, Eval time=315 ms.  Invoke=311.
Img 5, Eval time=333 ms.  Invoke=330.
Img 6, Eval time=303 ms.  Invoke=301.
Img 7, Eval time=360 ms.  Invoke=358.
Img 8, Eval time=293 ms.  Invoke=290.
Img 9, Eval time=231 ms.  Invoke=229.
Img 0, Eval time=244 ms.  Invoke=242.
Img 1, Eval time=223 ms.  Invoke=221.
Img 2, Eval time=220 ms.  Invoke=218.
```
