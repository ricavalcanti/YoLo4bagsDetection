# YoLo4bagsDetection

O objetivo deste projeto é usar a tiny-YoLo para detectar objetos, mais especificamente sacolas, a fim de se obter dados importantes para a análise do [Win-Loss]([https://theanovagroup.com/win-loss-analysis-services/win-loss-analysis/win-loss-analysis-defined/](https://theanovagroup.com/win-loss-analysis-services/win-loss-analysis/win-loss-analysis-defined/)) no varejo físico. 

A rede neural YoLo já tem alguns pesos para detectar objetos (bicicletas, carros, etc) mas as sacolas não estão nessa lista. Dessa forma, foi necessário treinar a RNA e gerar esses pesos. Por se tratar da fase inicial do projeto e pela falta de acessibilidade a uma maquina mais robusta, utilizou-se uma maquina mais simples para treinar a rede; mesmo com as configurações mínimas e um pequeno dataset, esse trabalhou levou em torno de 9 horas para ser concluído. Entretanto os resultados obtidos foram mais que satisfatórios. 
