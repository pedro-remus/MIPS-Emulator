# MIPS-Emulator

Emulador da Arquitetura de Processador MIPS (com algumas simplificações)
Esse programa foi desenvolvido na disciplina de Programação Orientada à Objetos da Escola Politécnica da USP.

# Funcionamento

![image](https://user-images.githubusercontent.com/101821919/209453864-4f80d8b2-a077-4d5b-b2de-c78e3316d566.png)

O programa permite que o usuário altere elementos da Memória, elementos do Banco de Registradores. O usuário também consegue executar a proxima instrução da memória (indicada pelo Program Counter - que por simplificação é apenas uma variável de controle neste emulador) e executar até o Program Counter (PC) indicar a posição 0. Além disso, o usuário consegue Carregar (Load) ou descarregar (Dump) a Memória utilizando arquivos de texto.

# Exemplo de Uso

Os arquivos fatorial.txt e hello.txt contém os dados e instruções necessárias para, respectivamente: calcular o fatorial de um número, imprimindo o resultado; e imprimir "Hello, World!". Para testar o funcionamento desses arquivos basta rodar o arquivo EmuladorMIPS.exe, selecionar a opção Load - digitando o arquivo de onde deseja-se trazer os dados - e executar até PC = 0.
