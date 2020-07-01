# Mental Calculation Classification
Clasificacion de calculo mental en senales EEG con CNN y CNN + LSTM

## STFT
### Espectrogramas con transformada de Fourier de tiempo corto
ventana = hann <br>
tamano ventana = 512 <br>
puntos superpuestos = 480 <br>
tamano de la FFT = 1024 <br>

### Clasificacion

* `STFT-CNN2D.ipynb`: CNN-2D
* `STFT-CNN2D-GS.ipynb`: CNN-2D Busqueda de cuadricula
* `STFT-CNN2D-Predecir.ipynb`: `CNN-2D Predecir cargando el modelo`
* `STFT-CNN-RNN.ipynb`: CNN-2D + LSTM
* `STFT-CNN-RNN-GS.ipynb`: CNN-2D + LSTM Busqueda de cuadricula
* `STFT-CNN-RNN-Predecir.ipynb`: CNN-2D + LSTM Predecir cargando el modelo

## CWT
### Escalogramas con transformada continua wavelet
wavelet = cmor3-3 <br>
escalas = 8-30Hz cada 0.5Hz <br>

### Clasificacion

* `CWT-CNN2D.ipynb`: CNN-2D
* `CWT-CNN2D-GS.ipynb`: CNN-2D Busqueda de cuadricula
* `CWT-CNN2D-Predecir.ipynb`: CNN-2D Predecir cargando el modelo
* `CWT-CNN-RNN.ipynb`: CNN-2D + LSTM
* `CWT-CNN-RNN-GS.ipynb`: CNN-2D + LSTM Busqueda de cuadricula
* `CWT-CNN-RNN-Predecir.ipynb`: CNN-2D + LSTM Predecir cargando el modelo