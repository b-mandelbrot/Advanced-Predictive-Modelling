MBA
Instalando o R no Jupyter Notebook

Abrir Anaconda Promt
Navegar Para Pasta do R:

```bash
cd C:\Program Files\R\R-3.5.2\bin\x64
```
Executar o R:
```bash
R.exe
```

Instalar os seguintes pacotes:
```R
install.packages("devtools")
install.packages('IRkernel')
IRkernel::installspec()
```

