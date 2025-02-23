
                                              **Projecto Ransomaware** 
                                                        
Este desafio de projeto faz parte do conteúdo abordado pelo Santander Bootcamp Cibersegurança, realizado pela DIO em parceria com o Santander Universidades.

Objectivo: incriptar e desincriptar um ficheiro .txt. de forma a o tornar mais seguro usando uma senha de acesso.

                                                    **ATENCÃO** 
Este teste foi executado não utilizando o comando encrypter.py ou decrypter.py
Infelizmente não consegui executar as ordens de processo que o professor apresentou, dando-me sempre um erro ao tentar incriptar o ficheiro .txt, 
não tendo qualquer experiência em python, procurei outras soluções para chegar ao mesmo fim.

                                                   **INSTRUÇÃO**
Para me auxiliar neste processo acessei e baixei um arquivo no github link abaixo
https://github.com/nodesocket/cryptr

No website, iremos em <> Code e copiaremos o link HTTPS

![image](https://github.com/user-attachments/assets/701a415b-98bc-4be0-af75-d9e59a5d5a1d)

No terminal iremos escrever então o seguinte código "git clone link_copiado"

![image](https://github.com/user-attachments/assets/8cd6a6b4-b6b6-404a-bb39-216517c24e8a)

**De volta à página do GitHub, na parte da "Installation" iremos copiar o código realçado**
![image](https://github.com/user-attachments/assets/7b8795af-ad89-460e-8676-bffa5922cdcc)

No terminal iremos escrever o comando sudo e colar o que copiamos anteriormente. Este irá nos permitir utilizar o comando cryptr diretamente do nosso terminal.
sudo ln -s "$PWD"/cryptr/cryptr.bash /usr/local/bin/cryptr

![image](https://github.com/user-attachments/assets/c4c4ef5d-ffe7-4a52-8225-f44d16277fde)

No terminal, para incriptar o ficheiro iremos simplesmente executar o comando "**cryptr encrypt file_name**" e designar uma palavra passe para o nosso ficheiro, isto o tornará mais seguro.
O ficheiro ira ter a terminação de .aes  
Para verificar se o ficheiro foi incriptado, podemos o abrir com o comando "cat file_name".

![image](https://github.com/user-attachments/assets/5b692847-419a-46ec-b38e-bc765f039be0)

![image](https://github.com/user-attachments/assets/b3ee9602-0e5c-45ce-b8ed-d2aef871d52c)

![image](https://github.com/user-attachments/assets/7ee98339-8018-4806-b53a-046121f3a460)

**Para desincriptar o ficheiro iremos utilizar o comando decrypt**

![image](https://github.com/user-attachments/assets/bb74bd64-6b38-44d3-be50-bd166f69434c)

![image](https://github.com/user-attachments/assets/797aded3-6b60-4e9b-9113-6a8f278fea4a)

![image](https://github.com/user-attachments/assets/a9f77548-557b-4110-bb94-fe219a305e4c)






