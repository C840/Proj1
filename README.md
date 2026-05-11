Shows comparision between CPU vs TPU performance using floyd warshall shortest path algorithm 

Run the html to get a basic understanding of what is happening 


For nodes 100<N<1200
Run benchmark_cpu.py in your pc 
Run benchmark_tpu.py in google colab tpu
You get CSV files 
Run combine combine_results(1).py to get a comparable result 

For nodes 10<N<100
Run floyd_warshall_cpu.py in your pc 
Run floyd_warshall_cpu.py in google colab tpu
You get CSV files 
Run combine combine_results.py to get a comparable result 
