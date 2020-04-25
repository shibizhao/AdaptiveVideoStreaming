Make sure actual video files are stored in `video_server/video[1-6]`, then run
```
python get_video_sizes
```

Make sure ```results/``` folder exists, if not, run

```
mkdir results
```

 If you want to test the buffer based method, run

```
python bb.py
```

 If you want to test the MPC method without any optimization, run

```
python mpc_naive.py
```

 If you want to test the MPC method with Hamming Distance optimization, run

```
python mpc_optim.py
```

 If you want to generate the offline computed Look up Table, run

```
python gen_lut.py
```

 If you want to test the MPC method with the simple LUT, run

```
python mpc_lut.py
```

If you want to test the MPC method with the vectorization LUT, run

```
python mpc_vec_lut.py
```

If you want to draw the plots, make sure the ```plots``` folder exists, then run

```
python plot.py
```

