## Teste Heroku

Um teste mais que simples do sistema da Heroku.

0 - Conta Heroku é criada e vinculada a este repositório
1 - `Procfile` contém o tipo de processo e o comando a ser executado pelo aplicativo Heroku.
2 - `runtime.txt` contém o ambiente de execução a ser dedicado ao aplicativo, neste caso é o python 3.7.0
3 - run.py é o programa a ser rodado pelo 'Dyno' do Heroku, como definido em `Procfile` e usando o ambiente em `runtime.txt`

Existe um CLI recomendado para facilitar a configuração destes aplicativos. Isto foi feito na munheca.

Toda vez que este repositório é atualizado, ocorre uma nova build e entrega instantanea no aplicativo.
Logs e outras coisas pertinentes a execução são disponibilizadas pela plataforma Heroku.

Link : servidorzao.herokuapp.com
