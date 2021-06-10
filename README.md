# Bem-vindo ao desafio

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Logo-Stone.svg/1200px-Logo-Stone.svg.png" width="300px"/>
</div>


## Documentação útil

1. [Automação Mobile](https://github.com/LuisFelipeSeabra/prova_renner/tree/master/AutomationProject)
2. [Planejamento de Casos de Testes](https://github.com/LuisFelipeSeabra/prova_renner/tree/master/RegresAPI)


## Planejamento de casos de teste
Para o projeto de planejamento de casos de teste, criou-se o fluxo de abertura de conta da fintech Start. Foram criados 17 cenários com o objetivo de apresentar uma boa cobertura de testes do fluxo de criação de conta corrente.
```
Formato: Gherkin
```


## Projeto de Automação mobile
Para automação Mobile utilizou-se: o formato Gherkin para a criação dos cenários, Appium como ferramenta de automatização e RobotFramework como framework de desenvolvimento.
```
Formato: Gherkin
Ferramenta: Appium
Framework: RobotFramework
```


#### Estruturação do Projeto:
```
├── /App                                          # Projeto                                                                                          
    ├── /resources                                #                                                                                                         
        ├── base.robot                            # Estrutura com a base para os testes, os métodos criados aqui, serão executados por todos os testes.
        ├── BDDpt-br.robot                        # Estrutura do BDD
        ├── helper.robot                          # Estrutura com métodos que poderão ser utilizados pelos testes.
    ├── /tests                                    # Pacote de testes
        ├── /.logs                                # Log's das execuções/ Relatório de teste
        ├── garden.robot                          # Testes a serem executados
    ├── sunflower.apk                             # Aplicação a ser homologada
        
```


#### Execução dos Testes
Executar pela linha de comando: 
```
cd C:\app\test
robot -d .logs garden.robot
```


#### Relatório de execução

1. [Relatório](https://github.com/LuisFelipeSeabra/prova_renner/tree/master/AutomationProject)


#### Execuções das Suites:

![image](https://user-images.githubusercontent.com/49051123/121474094-f7d45880-c999-11eb-9c49-f4cbaff55024.png)


#### Tecnologia

Tecnologias utilizadas no projeto:
  * Python 3.8.8
  * Appium
  * Android studio 4.1.3
  * Virtual Device Name: Pixel_3a_API_30_x86 Target: Android 11.0(Google APIs)
  * Visual Studio Code
