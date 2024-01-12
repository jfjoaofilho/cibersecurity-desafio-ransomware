# Ransomware Attack
## Introdução
Este documento fornece informações sobre um projeto em Python relacionado a um ataque de ransomware. O ransomware é uma forma de malware que criptografa os arquivos de um sistema e exige um resgate para descriptografar os dados. Este projeto contém três arquivos principais: **encrypter.py**, **decrypter.py** e **plaintext.txt**. A seguir, detalharemos a função de cada arquivo e forneceremos informações sobre o ataque.

## Ataque de Ransomware
### O que é Ransomware?
O ransomware é um tipo de malware malicioso que criptografa os arquivos em um sistema, tornando-os inacessíveis para o usuário. O atacante, em seguida, exige um pagamento (resgate) para fornecer a chave de descriptografia e restaurar o acesso aos dados.

### Sobre o Ataque
O ataque de ransomware simulado neste projeto visa apenas a fins educacionais e não deve ser utilizado para prejudicar sistemas sem permissão.

O ataque consiste em dois principais componentes: o **encrypter.py** que realiza a criptografia dos arquivos e o **decrypter.py** que descriptografa os arquivos quando a chave de descriptografia é obtida.

## Projeto em Python
### Estrutura do Projeto
- **`encrypter.py`**: Este arquivo contém o script responsável por criptografar os arquivos no sistema de destino.
- **`decrypter.py`**: Este arquivo contém o script responsável por descriptografar os arquivos após obtenção da chave de descriptografia.
- **`plaintext.txt`**: Este arquivo de texto simples representa um exemplo de arquivo que seria criptografado pelo **encrypter.py**.
### Funcionalidade dos Arquivos
* __encrypter.py__: Este script simula a ação de um ransomware, percorrendo os arquivos no sistema e aplicando um algoritmo de criptografia. O algoritmo utilizado foi **AES**, mas, pode variar e é apenas para fins ilustrativos.

* __decrypter.py__: Este script simula o processo de descriptografia após obtenção da chave de descriptografia. Ele restaura os arquivos criptografados ao seu estado original.

* __plaintext.txt__: Este arquivo representa um exemplo de arquivo que seria afetado pelo ransomware. Durante o ataque, este arquivo seria criptografado e, em seguida, descriptografado pelo **decrypter.py** quando a condição adequada for atendida.

## Aviso
- Este projeto é estritamente educacional e destina-se a fornecer informações sobre a natureza dos ataques de ransomware. O uso indevido de tais técnicas é ilegal e pode resultar em sérias consequências legais. Certifique-se de agir sempre em conformidade com as leis locais e globais ao realizar qualquer atividade relacionada à segurança cibernética.
