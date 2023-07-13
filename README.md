# Trabalho Prático de Segurança em Sistemas
# Universidade Federal do Piauí - UFPI
# Departamento de Computação - DC/CCNN
# Docente: Carlos André Batista de Carvalho
# Discentes: João Pedro Soares do Monte & Angelus Fayran Lima Rocha

# Esse trabalho foi realizado pelos alunos da disciplina, ministrada pelo professor Dr. Carlos André, de Segurança em Sistemas, do curso de Ciência da Computação.

# No presente trabalho é feita a utilização de sistemas de cifragem e decifragem de arquivos. Tal trabalho simula a criação e a abertura de envelopes digitais com algoritmos simétricos (AES, DES, RC4), juntamente com chaves de criptografia aleatórias e simétricas (RSA).

# DOCUMENTAÇÂO:

# Para conseguir executar esse código, é necessário um interpretador python, além de uma extensão para jupyter. Recomenda-se o uso da IDE "Visual Studio Code" com a extensão "Jupyter", pois o código fonte "index" está no formato "ipynb". 

# O trabalho consiste de 5 componentes "macros":

# envelope: Nesse arquivo estão os envelopes criados, utilizando qualquer um dos algoritmos simétricos (AES, DES, RC4). Dentro do arquivo estão contidos 3 outros diretórios (AES, DES, RC4), que possuem, cada um, um diretório de entrada e de saída: "input" e "output", onde, respectivamente, são armazenados a chave pública do destinatário e, no output, a chave de sessão cifrada, juntamente com a mensagem cifrada.

# openEnvelope: Nesse arquivo estão contidos os envelopes abertos, que são classificados segundo o algoritmo simétrico (AES, DES, RC4) que foi utilizado para criá-lo. Cada diretório dentro do openEnvelope (AES, DES, RC4) contém os diretórios: "input", "output" e "process", onde, respectivamente, estão contidos a chave privada do destinatário, a mensagem em claro e a chave de sessão decifrada.

# index: Este é o código fonte da aplicação, onde estão as funcionalidades do algoritmo, sendo possível a utilização dos serviços de criação e abertura de envelopes digitais. Nele é dado um menu, que oferece opções de escolha para trabalhar com os serviços de cifragem e decifragem. Dito isso, também é possível a digitação da mensagem que se deseja cifrar.

# initializationVector: Esse arquivo possui o vetor de incialização, uma vez que os algoritmos de cifra de bloco: DES e AES necessitam do mesmo para realizarem os mecanismos de cifragem.

# message: Nesse arquivo está a mensagem que será cifrada.