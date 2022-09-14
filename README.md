<!-- ABOUT THE PROJECT -->
## About The Project
## Recomendação de produtos baseada em análise de sentimentos.

Com o aprimoramento dos sites de comércio eletrônico, dos aplicativos para dispositivos celulares e também uma tendência crescente dos usuários na compra de produtos utilizando a web impulsionados pela pandemia desde o início de 2020, a revisão textual do usuário se tornou uma importante fonte de informações para melhorar o desempenho dos sistemas de recomendação, pois eles contêm opiniões de usuários refinadas que geralmente refletem sua preferência em relação aos produtos. No entanto, a maioria dos sistemas de recomendação clássicos muitas vezes ignoram essas opiniões do usuário e, portanto, falham em capturar com precisão os sentimentos específicos dos usuários sobre os produtos. Assim, para superar os problemas acima, pode-se fazer uso de técnicas de análise de sentimentos (Liu, 2012), alinhadas ao Processamento de Linguagem Natural, na implementação de um sistema de recomendação aprimorado, que utilize as informações presentes nas opiniões dos usuários em comentários na web. Os objetivos deste trabalho foram explorar o uso de técnicas de análise de sentimentos e processamento de linguagem natural sobre comentários da web para aprimorar sistemas de recomendação, visando trabalhar com a língua portuguesa brasileira. A partir de um desejo do usuário, a recomendação e o ranqueamento de produtos foram efetuados com base em extração de aspectos definidos pelos próprios usuários. Para extração dos aspectos, utilizou-se um algoritmo de aprendizado profundo chamado BERT. O sistema de ranqueamento implementado no projeto de pesquisa levou em consideração as opiniões dos usuários e não opiniões de especialistas, tornando o processo de tomada de decisão mais personalizado. Com relação aos resultados, percebe-se que o modelo BERT apresentou uma performance de mais de 90% de acurácia na extração de aspectos dos comentários web. Conclui-se que a utilização de comentários web para recomendar produtos a novos usuários pode ser uma forma interessante e personalizada, pois recomendamos produtos com base em aspectos selecionados pelo próprio usuário, tornando o processo de recomendação singular.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/rmrodarte/MBA-IA-Big_Data
   ```
2. Use the files 
Segue a base de dados que utilizamos: B2W-Reviews01.csv
Seguem os arquivos que utilizamos para realizar o fine-tuning do BERT:

- domain_smartphone_IOB.csv
- domain_camera_IOB.csv
- domain_hotel_IOB.csv
- domain_livro_IOB.csv
Para a reprodução do projeto e trabalho, basta executar o notebook ou o código python em sequência.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Your Name - Rodrigo Meneses Rodarte - meneses.rodarte@gmail.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
