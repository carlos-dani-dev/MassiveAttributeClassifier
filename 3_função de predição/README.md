#### O arquivo *pred_func.py* descreve, em linguagem Python, a função de predição final
#### O modelo de machine learning utilizado no arquivo citado acima é *modelo_hybrid_200_2048_1e-05.keras*
#### O dataset utilizado para o treinamento do modelo citado acima é o *Casual Conversations v2*, após ser devidamente balanceado sobre os atributos considerados mais relevantes para a pesquisa e, então, anotado por uma função de predição intermediária, que utiliza um modelo de machine learning intermediário
#### O dataset utilizado para o treinamento do modelo intermediário citado acima é o *CelebA Dataset*, após ser devidamente balanceado sobre os atributos considerados mais relevantes para a pesquisa

### -- IMAGEM EXPLICATIVA --

---

#### Para executar o arquivo *pred_func.py*:
- <strong>Assegure-se de reunir os seguintes arquivos na mesma página: *modelo_hybrid_200_2048_1e-05.keras*, *label_encoders.pkl* e *video_att_mapping_cc_dataset.csv*</strong>
- <strong>Assegure-se ainda de criar as pastas *imagens* e *predições*</strong>
- <strong>Instale as dependências descritas em *requirements.txt* com o gerenciador de ambientes virtuais da sua escolha</strong>
- <strong>Após os passos descritos acima, execute, no prompt de comando, o arquivo devidamente adaptado com o caminho correto da imagem a ser predita com: *python pred_func.py*</strong>