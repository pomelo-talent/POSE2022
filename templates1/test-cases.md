| leftHandEngineThrust | rightHandEngineThrust | windSpeed | expected return value |
|:--------------------:|:---------------------:|:---------:|:---------------------:|
|         0.0          |         0.0           |   0.0     |         0.0           |
|      -9999.01        |         0.0           |   0.0     |       OVERFLOW        |
|      -9999.0         |         0.0           |   0.0     |         NaN           |
|      -5000.0         |         0.0           |   0.0     |         NaN           |
|        -1.0          |         0.0           |   0.0     |         NaN           |
|       5000.0         |         0.0           |   0.0     |        91.65          |
|       9999.0         |         0.0           |   0.0     |        129.61         |
|       9999.01        |         0.0           |   0.0     |       OVERFLOW        |
|         0.0          |      -9999.01         |   0.0     |       OVERFLOW        |
|         0.0          |      -9999.0          |   0.0     |         NaN           |
|         0.0          |      -5000.0          |   0.0     |         NaN           |
|         0.0          |        -1.0           |   0.0     |         NaN           |
|         0.0          |       5000.0          |   0.0     |        91.65          |
|         0.0          |       9999.0          |   0.0     |        129.61         |
|         0.0          |       9999.01         |   0.0     |       OVERFLOW        |
|       -500.0         |       5000.0          |   0.0     |        86.95          |
|       -500.0         |      -5000.0          |   0.0     |         NaN           |
|       5000.0         |       -500.0          |   0.0     |        86.95          |
|       5000.0         |        500.0          |   0.0     |        96.12          |
|       9999.0         |      9999.0           |   0.0     |        183.29         |
|         0.0          |         0.0           | -9999.01  |       OVERFLOW        |
|         0.0          |         0.0           | -9999.0   |       -9999.0         |
|       9999.0         |       9999.0          | -50.0     |        133.29         |
|       9999.0         |       9999.0          |  50.0     |        233.29         |
|         0.0          |         0.0           |  9999.0   |        9999.0         |
|         0.0          |         0.0           |  9999.01  |       OVERFLOW        |
