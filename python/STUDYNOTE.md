## pythonのメモ(備忘録(あとで整理する))

- **Anacondaの仮想環境の確認と有効化**  
    [【Anaconda】 仮想環境の確認・有効化・削除](https://kazu-oji.com/conda-manageenv-etc/)参考。  
  1. Anaconda promptを開く  
  2. `conda info -e`と入力。`*`がついている環境が現在の環境  
  3. `conda activate pythonGIS(環境名)`と入力。これにより環境の変更ができる。


- **Jupyter notebookで仮想環境を作成する**  
  [仮想環境をJupyterNotebookから作成する](https://starpentagon.net/analytics/conda_env_jupyter_notebook/)参考。  
  ##### jupyterのターミナルで実行する    
  1. 仮想環境の作成    
     `conda create -n newPythonEn python=3.8 jupyterlab`  
     `newPythonEn`は仮想環境名  
  2. 仮想環境の有効化  
     `conda activate newPythonEn`  
     これでできない時は、AnacondaNavigatorのhomeで新しい仮想環境を選択する。  
  3. Jupyter notebookのkernelに仮想環境を追加  
     仮想環境にJupyter Notebookを入れる  
        `conda install notebook ipykernel`  
     Jupyter Notebookのkernelに作成した仮想環境を追加  
        `ipython kernel install --user --name newPythonEn`  
  4. Jupyter Notebookのkernelから仮想環境を削除  
     `conda remove -n vir_env --all`

- Jupyter Notebookのmarkdown記法  
  [参考サイト](https://home.hirosaki-u.ac.jp/jupyter/markdown/)
     
- NDVI(Nomalized Difference Vezitation Index)について  
  <a href= "https://sorabatake.jp/5192/#:~:text=%E3%80%8CNDWI(Normalized%20Difference%20Water%20Index,%E3%81%8C%E7%9F%A5%E3%82%89%E3%82%8C%E3%81%A6%E3%81%84%E3%81%BE%E3%81%99%E3%80%82">参考サイト</a>
